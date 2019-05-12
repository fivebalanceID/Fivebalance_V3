
Debian
====================
This directory contains files used to package fivebalanced/fivebalance-qt
for Debian-based Linux systems. If you compile fivebalanced/fivebalance-qt yourself, there are some useful files here.

## fivebalance: URI support ##


fivebalance-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fivebalance-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fivebalanceqt binary to `/usr/bin`
and the `../../share/pixmaps/fivebalance128.png` to `/usr/share/pixmaps`

fivebalance-qt.protocol (KDE)

