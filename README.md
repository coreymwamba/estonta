# estonta
A simple Bash and [Yad](https://sourceforge.net/projects/yad-dialog/)-based appointment system.

It has two scripts: **aldonos** (add an event, using Yad) and **lerta** (list events, in a shell).


![clockwise, from top-left: lerta (in Termite), lerta in Conky, estonta.conf, aldonos](estonta/estonta.png)


## aldonos
aldonos produces iCalendar files in a directory (set in $HOME/.config/estonta.conf).

## lerta
lerta displays a list of events in the directory. You can filter them by category; or find an event by date. It's VERY basic.

## Installation

```
sudo install -p -D aldonos -m 0755 /usr/local/bin/aldonos
sudo install -p -D lerta -m 0755 /usr/local/bin/lerta
install -p -D estonta.conf -m 0644 $HOME/.config/estronta.conf
```

Then use your favourite text editor to edit **estronta.conf**.

## Why?
I got sick--thoroughly sick--of not having a transparent way of making events on my laptop. By transparent I mean making an event that I can then send to something else (like a phone; or my site) without a conversion step. I also needed something that would give me a plain list of events that I could use in Conky.


