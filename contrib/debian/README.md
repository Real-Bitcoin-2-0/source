
Debian
====================
This directory contains files used to package rBTC20d/rBTC20-qt
for Debian-based Linux systems. If you compile rBTC20d/rBTC20-qt yourself, there are some useful files here.

## pivx: URI support ##


rBTC20-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rBTC20-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rBTC20-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

rBTC20-qt.protocol (KDE)

