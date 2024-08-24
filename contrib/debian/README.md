
Debian
====================
This directory contains files used to package bellsd/luckycoin-qt
for Debian-based Linux systems. If you compile bellsd/luckycoin-qt yourself, there are some useful files here.

## bells: URI support ##


luckycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install luckycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your luckycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bells128.png` to `/usr/share/pixmaps`

luckycoin-qt.protocol (KDE)

