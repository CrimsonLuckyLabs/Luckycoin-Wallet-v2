
Debian
====================
This directory contains files used to package bellsd/bells-qt
for Debian-based Linux systems. If you compile bellsd/bells-qt yourself, there are some useful files here.

## dogecoin: URI support ##


bells-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bells-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bells-qt binary to `/usr/bin`
and the `../../share/pixmaps/dogecoin128.png` to `/usr/share/pixmaps`

bells-qt.protocol (KDE)

