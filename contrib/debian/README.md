
Debian
====================
This directory contains files used to package berycoind/berycoin-qt
for Debian-based Linux systems. If you compile berycoind/berycoin-qt yourself, there are some useful files here.

## berycoin: URI support ##


berycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install berycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your berycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

berycoin-qt.protocol (KDE)

