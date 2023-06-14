# archlinux-packages

My repository of pre-built packages for [pacman](https://wiki.archlinux.org/title/pacman).

| Package        | Description                                     |
| -------------- | ----------------------------------------------- |
| helix-git-aoxo | A text editor written in rust                   |
| kmonad-git     | An advanced keyboard manager written in Haskell |
| synchroma      | A general purpose syntax highlighter in pure Go |

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
