# archlinux-packages

Some packages not worth for AUR but worth keeping track of.

## Usage

First add my public key
```
sudo pacman-key --recv-keys 10D9B77C6D5EFDC0
sudo pacman-key --lsign-key 10D9B77C6D5EFDC0
``` 


Add this to the end of `/etc/pacman.conf`
```
[aoxos]
Server = https://github.com/AOx0/archlinux-packages/releases/download/packages
```