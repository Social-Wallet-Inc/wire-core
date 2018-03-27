
Debian
====================
This directory contains files used to package wired/wire-qt
for Debian-based Linux systems. If you compile wired/wire-qt yourself, there are some useful files here.

## wire: URI support ##


wire-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wire-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wireqt binary to `/usr/bin`
and the `../../share/pixmaps/wire128.png` to `/usr/share/pixmaps`

wire-qt.protocol (KDE)

