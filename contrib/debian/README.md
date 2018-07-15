
Debian
====================
This directory contains files used to package shmnd/shmn-qt
for Debian-based Linux systems. If you compile shmnd/shmn-qt yourself, there are some useful files here.

## shmn: URI support ##


shmn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install shmn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your shmnqt binary to `/usr/bin`
and the `../../share/pixmaps/shmn128.png` to `/usr/share/pixmaps`

shmn-qt.protocol (KDE)

