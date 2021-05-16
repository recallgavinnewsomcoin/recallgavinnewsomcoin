
Debian
====================
This directory contains files used to package dogecoind/rgncoin-qt
for Debian-based Linux systems. If you compile dogecoind/rgncoin-qt yourself, there are some useful files here.

## dogecoin: URI support ##


rgncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rgncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rgncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

rgncoin-qt.protocol (KDE)

