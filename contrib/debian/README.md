
Debian
====================
This directory contains files used to package faustd/faust-qt
for Debian-based Linux systems. If you compile faustd/faust-qt yourself, there are some useful files here.

## faust: URI support ##


faust-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install faust-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your faustqt binary to `/usr/bin`
and the `../../share/pixmaps/faust128.png` to `/usr/share/pixmaps`

faust-qt.protocol (KDE)

