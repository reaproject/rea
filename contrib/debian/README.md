
Debian
====================
This directory contains files used to package read/rea-qt
for Debian-based Linux systems. If you compile read/rea-qt yourself, there are some useful files here.

## rea: URI support ##


rea-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rea-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your reaqt binary to `/usr/bin`
and the `../../share/pixmaps/rea128.png` to `/usr/share/pixmaps`

rea-qt.protocol (KDE)

