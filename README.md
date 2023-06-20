# archlinux-packages

My repository of pre-built packages for [pacman](https://wiki.archlinux.org/title/pacman).

| Package                                            | Description                                                             |
| -------------------------------------------------- | ----------------------------------------------------------------------- |
| [helix-git](https://github.com/helix-editor/helix) | A text editor written in Rust                                           |
| [kmonad-git](https://github.com/kmonad/kmonad)     | An advanced keyboard manager written in Haskell                         |
| [hyprland-git](https://github.com/hyprwm/Hyprland) | A dynamic tiling Wayland compositor that doesn't sacrifice on its looks |

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
