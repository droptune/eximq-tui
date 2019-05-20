# eximq-tui
Exim queue TUI manager written in Python.

This is a ncurses-based text UI frontend for Exim MTA queue management.

## Installation
Python 2.6/Python 3.0 or newer required.

Just copy [eximq-tui](https://raw.githubusercontent.com/droptune/eximq-tui/master/eximq-tui) somewhere in your PATH and launch it.

If your Exim puts log files in non-default folder you may need to put main log location in `EXIM_LOG` variable. It is used for *'grep exim log file for message ID'* function.

![screenshot](https://user-images.githubusercontent.com/2103126/58049914-a65c9500-7b56-11e9-9793-23de5c29dd6b.png)
