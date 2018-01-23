
Debian
====================
This directory contains files used to package vsyncd/vizee-qt
for Debian-based Linux systems. If you compile vsyncd/vizee-qt yourself, there are some useful files here.

## vizee: URI support ##


vizee-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vizee-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vsyncqt binary to `/usr/bin`
and the `../../share/pixmaps/vsync128.png` to `/usr/share/pixmaps`

vizee-qt.protocol (KDE)

