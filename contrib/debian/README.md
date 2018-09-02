
Debian
====================
This directory contains files used to package kingscoind/kingscoin-qt
for Debian-based Linux systems. If you compile kingscoind/kingscoin-qt yourself, there are some useful files here.

## kingscoin: URI support ##


kingscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kingscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kingscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/kingscoin128.png` to `/usr/share/pixmaps`

kingscoin-qt.protocol (KDE)

