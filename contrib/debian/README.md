
Debian
====================
This directory contains files used to package unnd/unn-qt
for Debian-based Linux systems. If you compile unnd/unn-qt yourself, there are some useful files here.

## unn: URI support ##


unn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install unn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unnqt binary to `/usr/bin`
and the `../../share/pixmaps/unn128.png` to `/usr/share/pixmaps`

unn-qt.protocol (KDE)

