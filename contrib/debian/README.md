
Debian
====================
This directory contains files used to package boad/boa-qt
for Debian-based Linux systems. If you compile boad/boa-qt yourself, there are some useful files here.

## boa: URI support ##


boa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install boa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your boa-qt binary to `/usr/bin`
and the `../../share/pixmaps/boa128.png` to `/usr/share/pixmaps`

boa-qt.protocol (KDE)

