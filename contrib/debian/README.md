
Debian
====================
This directory contains files used to package x6coind/x6coin-qt
for Debian-based Linux systems. If you compile x6coind/x6coin-qt yourself, there are some useful files here.

## x6coin: URI support ##


x6coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install x6coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your x6coinqt binary to `/usr/bin`
and the `../../share/pixmaps/x6coin128.png` to `/usr/share/pixmaps`

x6coin-qt.protocol (KDE)

