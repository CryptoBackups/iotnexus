
Debian
====================
This directory contains files used to package iotnexusd/iotnexus-qt
for Debian-based Linux systems. If you compile iotnexusd/iotnexus-qt yourself, there are some useful files here.

## iotnexus: URI support ##


iotnexus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install iotnexus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your iotnexusqt binary to `/usr/bin`
and the `../../share/pixmaps/iotnexus128.png` to `/usr/share/pixmaps`

iotnexus-qt.protocol (KDE)

