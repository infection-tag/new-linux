# new-linux
Minimum requirements for a new linux box.

## Prerequisites

Currently I only have an installer for debian-based systems. Since there are a lot of different systems wih a lot of different pre-installed softwares, it helps to make sure you have everything.

`curl` should be automatically installed. However, for some lighter operating systems, it almost never is.

**Before doing anything, update your installer!**

```sh
sudo apt update # debian-based
sudo yum check-update # red-hat based
```

To install, run:
```sh
sudo apt install curl # debian-based
sudo yum curl # red-hat based
```

## Installing

To install, simply run:

```sh
curl https://github.com/infection-tag/new-linux/debinstaller.sh # debian
```

Note: I will try to add a RHEL-based installer.

## What am I installing?
* VIM
* Python
* Pip
* Jupyter
* Flathub (repo)
* Universe (repo)
* Git
* Snap Store
* Gnome-tweaks

It also adds some nice vim customizations.
