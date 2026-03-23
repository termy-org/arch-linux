# arch-linux

Arch Linux packaging for [Termy](https://termy.dev) - A minimal GPU-powered terminal written in Rust.

## Installation

Install Termy from the AUR using your preferred helper:

```bash
# Using paru
paru -S termy-bin

# Using yay
yay -S termy-bin
```

Or manually clone and build:

```bash
git clone https://aur.archlinux.org/termy-bin.git
cd termy-bin
makepkg -si
```

## PKGBUILD

This repository contains the PKGBUILD and related files for packaging Termy for Arch Linux.

## Updating

To update Termy:

```bash
paru -Syu termy-bin
```

---

For more information, visit [termy.dev](https://termy.dev)
