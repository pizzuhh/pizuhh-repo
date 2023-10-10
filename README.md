# pizuhh-repo
# THE REPO HAS BEEN MOVED!
You can still use this one but it won't be updated regularly

My arch repo for my stuff

# How to add
1. Make a backup of your pacman.conf just in case ``sudo cp /etc/pacman.conf /etc/pacman.conf.back``
2. paste this at the end of ``/etc/pacman.conf``
```
[pizuhh-repo]
# Old
# Server = https://raw.githubusercontent.com/pizzuhh/pizuhh-repo/main/$arch/
# New
Server = https://repo.pizzuhh.dev/pizuhh-repo/x86_64/
SigLevel = Optional TrustAll
```
3. run ``pacman -Sy`` if there are any errors make [`issue`](https://github.com/pizzuhh/pizuhh-repo/issues)
