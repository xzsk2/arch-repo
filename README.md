## Sakari's Pacman Repository

Personal use ArchLinux package repository

### Usage

Add following entry to `/etc/pacman.conf`

```conf
[sakari-aur]
SigLevel = Optional
Server = https://raw.github.com/xzsk2/arch-repo/main/repo
```

And `pacman -Sy` to update repositories

### Related Repos

[PKGBUILDs for packages](https://github.com/xzsk2/PKGBUILDS)
