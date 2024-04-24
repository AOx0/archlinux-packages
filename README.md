# archlinux-packages

My repository of pre-built packages for [pacman](https://wiki.archlinux.org/title/pacman).

| Package                                                  | Description                                                                  |
| -------------------------------------------------------- | ---------------------------------------------------------------------------- |
| [gitkraken-wayland](https://github.com/Azd325/gitkraken) | The intuitive, fast, and beautiful cross-platform Git client.                |
| [helix-git](https://github.com/AOx0/helix)               | (Fork) A text editor written in Rust.                                        |
| [tinymist](https://github.com/Myriad-Dreamin/tinymist)   | Tinymist [ˈtaɪni mɪst] is an integrated language service for Typst [taɪpst]. |
| [typst-git](https://github.com/typst/typst)              | A markup-based typesetting system for the sciences.                          |



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
