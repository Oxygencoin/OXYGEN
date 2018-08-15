
Debian
====================
This directory contains files used to package oxygend/oxygen-qt
for Debian-based Linux systems. If you compile oxygend/oxygen-qt yourself, there are some useful files here.

## oxygen: URI support ##


oxygen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install oxygen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your oxygenqt binary to `/usr/bin`
and the `../../share/pixmaps/oxygen128.png` to `/usr/share/pixmaps`

oxygen-qt.protocol (KDE)

