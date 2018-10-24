# typealong
Practice typing on any text

Usage:
* ./typealong example.epub
* Typing text brings you forward.
* Press 'n' to jump a paragraph.
* Press 'c' to jump a chapter.
* Press 'q' to quit.
* State is saved upon quit.
* Note: currently no way to rewind except deleting example.epub.pickle

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
