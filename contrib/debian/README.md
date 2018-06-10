
Debian
====================
This directory contains files used to package piped/pipe-qt
for Debian-based Linux systems. If you compile piped/pipe-qt yourself, there are some useful files here.

## pipe: URI support ##


pipe-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pipe-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pipe-qt binary to `/usr/bin`
and the `../../share/pixmaps/pipe128.png` to `/usr/share/pixmaps`

pipe-qt.protocol (KDE)

