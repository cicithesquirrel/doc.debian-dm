# About this document

This is a simple procedure list of how to add a desktop environment on a bare Debian Jessie system.

# Installing desktop environments

## LXDE

```
sudo apt install lxde-core lightdm
```

Includes XTerm terminal emulator.

## Cinnamon

```
sudo apt install xserver-xorg xserver-xorg-core xfonts-base xinit --no-install-recommends
sudo apt install cinnamon-core lightdm libgl1-mesa-dri x11-xserver-utils --no-install-recommends
```

Includes XTerm terminal emulator.

## XFCE

```
sudo apt install xfce4
```

Includes XTerm terminal emulator.

## MATE

```
sudo apt install mate-desktop-environment-core lightdm
```

Includes MATE terminal emulator.

## Gnome

```
sudo apt install gnome-core
```

Includes Gnome terminal emulator.

# Options

## Terminal emulator

When missing a nice terminal emulator:

```
sudo apt install gnome-terminal --no-install-recommends
```
