
Debian
====================
This directory contains files used to package flcoind/flcoin-qt
for Debian-based Linux systems. If you compile flcoind/flcoin-qt yourself, there are some useful files here.

## flcoin: URI support ##


flcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install flcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/flcoin128.png` to `/usr/share/pixmaps`

flcoin-qt.protocol (KDE)

