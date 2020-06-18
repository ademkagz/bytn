
Debian
====================
This directory contains files used to package bytncoind/bytncoin-qt
for Debian-based Linux systems. If you compile bytncoind/bytncoin-qt yourself, there are some useful files here.

## bytncoin: URI support ##


bytncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bytncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bytncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bytncoin128.png` to `/usr/share/pixmaps`

bytncoin-qt.protocol (KDE)

