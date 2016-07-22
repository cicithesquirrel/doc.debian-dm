# About this document

This is a simple procedure list of how to add a desktop environment on a bare Debian Jessie system.

# Installing desktop environments

## LXDE

```
sudo apt install lxde-core lightdm
```

Terminal emulators:
* Included: XTerm, UXTerm
* Suggested: LXTerminal

Browser:
* Included: None
* Suggested: Firefox-ESR

Resources:
* Hard drive space: 1.8 GB
* Memory: 169 MB

## Cinnamon

```
sudo apt install xserver-xorg xserver-xorg-core xfonts-base xinit --no-install-recommends
sudo apt install cinnamon-core lightdm libgl1-mesa-dri x11-xserver-utils --no-install-recommends
```
Requires video hardware acceleration.

Terminal emulators:
* Included: XTerm, UXTerm
* Suggested: ???

Resources:
* Hard drive space: 2.4 GB
* Memory: 608 MB

## XFCE

![XFCE screenshot](/xfce.png)

```
sudo apt install xfce4
```

Terminal emulators:
* Included: XTerm, UXTerm
* Suggested: XFCE4-Terminal

Resources:
* Hard drive space: 1.6 GB
* Memory: 280 MB

## MATE

```
sudo apt install mate-desktop-environment-core lightdm
```

Terminal emulators:
* Included: MATE terminal emulator

Resources:
* Hard drive space: 1.9 GB
* Memory: 284 MB
* 

## Gnome

```
sudo apt install gnome-core
```

Terminal emulators:
* Included: Gnome terminal emulator

Resources:
* Hard drive space: 2.8 GB
* Memory: 370 MB
