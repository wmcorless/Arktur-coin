
Debian
====================
This directory contains files used to package arkturd/arktur-qt
for Debian-based Linux systems. If you compile arkturd/arktur-qt yourself, there are some useful files here.

## arktur: URI support ##


arktur-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install arktur-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your arkturqt binary to `/usr/bin`
and the `../../share/pixmaps/arktur128.png` to `/usr/share/pixmaps`

arktur-qt.protocol (KDE)

