
Debian
====================
This directory contains files used to package jmagcoind/jmagcoin-qt
for Debian-based Linux systems. If you compile jmagcoind/jmagcoin-qt yourself, there are some useful files here.

## jmagcoin: URI support ##


jmagcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install jmagcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your jmagcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/jmagcoin128.png` to `/usr/share/pixmaps`

jmagcoin-qt.protocol (KDE)

