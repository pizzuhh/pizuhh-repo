# pizuhh-repo
My arch repo for my stuff

# How to add
1. Make a backup of your pacman.conf just in case ``sudo cp /etc/pacman.conf /etc/pacman.conf.back``
2. paste this at the end of ``/etc/pacman.conf``
```
[pizuhh-repo]
Server = https://raw.githubusercontent.com/pizzuhh/pizuhh-repo/main/$arch/
SigLevel = Optional TrustAll
```
3. run ``pacman -Sy`` if there are any errors make [`issue`](https://github.com/pizzuhh/pizuhh-repo/issues)
