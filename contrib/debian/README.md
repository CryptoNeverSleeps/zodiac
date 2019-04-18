
Debian
====================
This directory contains files used to package zodiacd/zodiac-qt
for Debian-based Linux systems. If you compile zodiacd/zodiac-qt yourself, there are some useful files here.

## zodiac: URI support ##


zodiac-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zodiac-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zodiacqt binary to `/usr/bin`
and the `../../share/pixmaps/zodiac128.png` to `/usr/share/pixmaps`

zodiac-qt.protocol (KDE)

