# termux-fedora
A script to install a Fedora chroot into Termux.

Currently it supports Fedora 32 ARM64 and Fedora 31 ARM64.

Starting from Fedora 28, Container image for 32bit ARM is no longer provided.

# Instructions

Supported images:

- f31_arm64
- f32_arm64

```
pkg install wget -y && /data/data/com.termux/files/usr/bin/wget https://raw.githubusercontent.com/nmilosev/termux-fedora/master/termux-fedora.sh

sh termux-fedora.sh [desired image]
```

For example:

```
sh termux-fedora.sh f32_arm64
```

To uninstall:

```
sh termux-fedora.sh uninstall
```
