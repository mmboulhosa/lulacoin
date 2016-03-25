
Debian
====================
This directory contains files used to package lulacoind/lulacoin-qt
for Debian-based Linux systems. If you compile lulacoind/lulacoin-qt yourself, there are some useful files here.

## lulacoin: URI support ##


lulacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lulacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lulacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/lulacoin128.png` to `/usr/share/pixmaps`

lulacoin-qt.protocol (KDE)

