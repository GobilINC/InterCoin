
Debian
====================
This directory contains files used to package intercoind/intercoin-qt
for Debian-based Linux systems. If you compile intercoind/intercoin-qt yourself, there are some useful files here.

## intercoin: URI support ##


intercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install intercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your intercoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

intercoin-qt.protocol (KDE)
