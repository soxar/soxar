
Debian
====================
This directory contains files used to package soxard/soxar-qt
for Debian-based Linux systems. If you compile soxard/soxar-qt yourself, there are some useful files here.

## soxar: URI support ##


soxar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install soxar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your soxar-qt binary to `/usr/bin`
and the `../../share/pixmaps/soxar128.png` to `/usr/share/pixmaps`

soxar-qt.protocol (KDE)

