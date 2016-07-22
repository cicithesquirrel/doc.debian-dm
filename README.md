# About this document

This is a simple procedure list of how to add a desktop environment on a bare Debian Jessie system.

# Installing desktop environments

## LXDE

```
sudo apt install lxde-core lightdm
```

## Cinnamon

```
sudo apt install xserver-xorg xserver-xorg-core xfonts-base xinit --no-install-recommends
sudo apt install cinnamon-core lightdm libgl1-mesa-dri x11-xserver-utils --no-install-recommends
```

## XFCE

```
sudo apt install xfce4
```

# Options

## Terminal emulator

When missing a nice terminal emulator:

```
sudo apt install gnome-terminal --no-install-recommends
```
