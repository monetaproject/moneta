
Debian
====================
This directory contains files used to package monetad/moneta-qt
for Debian-based Linux systems. If you compile monetad/moneta-qt yourself, there are some useful files here.

## moneta: URI support ##


moneta-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install moneta-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your moneta-qt binary to `/usr/bin`
and the `../../share/pixmaps/moneta128.png` to `/usr/share/pixmaps`

moneta-qt.protocol (KDE)

