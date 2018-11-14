# typealong
Practice typing on any text

Usage:
* ./typealong example.epub
* Typing text brings you forward.
* Press '1' to quit.
* Press '2' to rewind a chapter.
* Press '3' to rewind a paragraph.
* Press '4' to rewind a word.
* Press '5' to rewind a character.
* Press '6' to jump a character.
* Press '7' to jump a word.
* Press '8' to jump a paragraph.
* Press '9' to jump a chapter.
* State is saved upon quit.

UIs:
* Terminal based

Supported formats:
* epub

Pre-requisites:
* Linux (see special windows notes below)
* Python3
* pip

Windows usage:
* Ensure that you have python 3.7 and download applicable wheel file from here: https://www.lfd.uci.edu/~gohlke/pythonlibs/#curses
* Use "pip install curses....whl" to install it
* python typealong example.epub
