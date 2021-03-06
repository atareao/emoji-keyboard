# Emoji keyboard

Virtual keyboard-like emoji picker for linux.

This project uses artwork and data from the excellent [EmojiOne project](http://emojione.com/).

## Installation

### Dependencies

You'll need Python 3 GObject bindings and python3-xlib package.
If you're on a debian based distro you can install them with

`sudo apt install python3-gi gir1.2-gtk-3.0 gir1.2-glib-2.0 gir1.2-appindicator3-0.1 python3-xlib`

### App

There are several ways to install the app, you can install from deb you can
find on [releases page](https://github.com/OzymandiasTheGreat/emoji-keyboard/releases).

You can install with pip

`sudo pip3 install https://github.com/OzymandiasTheGreat/emoji-keyboard/archive/master.zip`

Or you can download the tarball, extract and run

`sudo setup.py install`

## Usage

Selecting `Show Keyboard` from the app indicator menu or, if your desktop
environment supports it, middle-clicking app indicator will toggle the visibility
of the picker. When the picker is visible simply clicking on emoji will type it
into focused application.

If you want to toggle the visibility of the picker with a hotkey, use your
desktop environment's native hotkey utility to assign a hotkey to `emoji-keyboard`.
