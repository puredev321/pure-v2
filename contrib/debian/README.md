
Debian
====================
This directory contains files used to package pured/pure-qt
for Debian-based Linux systems. If you compile pured/pure-qt yourself, there are some useful files here.

## pure: URI support ##


pure-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pure-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pureqt binary to `/usr/bin`
and the `../../share/pixmaps/pure128.png` to `/usr/share/pixmaps`

pure-qt.protocol (KDE)

