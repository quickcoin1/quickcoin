
Debian
====================
This directory contains files used to package quickcoind/quickcoin-qt
for Debian-based Linux systems. If you compile quickcoind/quickcoin-qt yourself, there are some useful files here.

## quickcoin: URI support ##


quickcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quickcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quickcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/quickcoin128.png` to `/usr/share/pixmaps`

quickcoin-qt.protocol (KDE)

