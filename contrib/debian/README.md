
Debian
====================
This directory contains files used to package scribed/scribe-qt
for Debian-based Linux systems. If you compile scribed/scribe-qt yourself, there are some useful files here.

## scribe: URI support ##


scribe-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scribe-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your scribe-qt binary to `/usr/bin`
and the `../../share/pixmaps/scribe128.png` to `/usr/share/pixmaps`

scribe-qt.protocol (KDE)

