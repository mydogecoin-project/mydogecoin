
Debian
====================
This directory contains files used to package mydogecoind/mydogecoin-qt
for Debian-based Linux systems. If you compile mydogecoind/mydogecoin-qt yourself, there are some useful files here.

## mydogecoin: URI support ##


mydogecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mydogecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mydogecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/mydogecoin128.png` to `/usr/share/pixmaps`

mydogecoin-qt.protocol (KDE)

