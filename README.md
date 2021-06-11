## catdevz-arch-repo

catdevz-arch-repo is a repository of packages for Arch Linux containing software I and my friends create, along with my custom configs and builds of software such as DWM, DWMBlocks, exc. If you have any concerns with the packages supplied by the repository feel free to open an issue, and if you have any packages you think would fit in the repository feel free to open a pull request.

## How to add (install) the repository

To add the repository to your arch install add the following to the end of your `/etc/pacman.conf`

```
[catdevz-arch-repo]
SigLevel = Optional DatabaseOptional
Server = https://github.com/CatDevz/$repo/raw/master/$arch
```

After appending that run `pacman -Syyu` as root to sync your repositories.

Then you can install any software you need like you normally would with pacman (eg. `pacman -S dwm-catdevz-git`)

## Packages in the repository

- dmenu-catdevz-git ([Source](https://github.com/CatDevz/dmenu-catdevz))
- dwm-catdevz-git ([Source](https://github.com/CatDevz/dwm-catdevz))
- dwmblocks-catdevz-git ([Source](https://github.com/CatDevz/dwmblocks-catdevz))
