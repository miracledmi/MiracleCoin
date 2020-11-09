
Debian
====================
This directory contains files used to package miraclecoind/miraclecoin-qt
for Debian-based Linux systems. If you compile miraclecoind/miraclecoin-qt yourself, there are some useful files here.

## miraclecoin: URI support ##


miraclecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install miraclecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your miraclecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/miraclecoin128.png` to `/usr/share/pixmaps`

miraclecoin-qt.protocol (KDE)

