
Debian
====================
This directory contains files used to package democoind/democoin-qt
for Debian-based Linux systems. If you compile democoind/democoin-qt yourself, there are some useful files here.

## democoin: URI support ##


democoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install democoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your democoinqt binary to `/usr/bin`
and the `../../share/pixmaps/democoin128.png` to `/usr/share/pixmaps`

democoin-qt.protocol (KDE)

