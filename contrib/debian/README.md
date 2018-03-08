
Debian
====================
This directory contains files used to package funbyted/funbyte-qt
for Debian-based Linux systems. If you compile funbyted/funbyte-qt yourself, there are some useful files here.

## funbyte: URI support ##


funbyte-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install funbyte-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your funbyte-qt binary to `/usr/bin`
and the `../../share/pixmaps/funbyte128.png` to `/usr/share/pixmaps`

funbyte-qt.protocol (KDE)

