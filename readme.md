# xdg-tools
Utilize XDG-based system packages such as to discover icon names or run a ".desktop" file.


## Requirements
The following system packages are necessary before setup will work.

### Python 2
The python2 dev package must be installed for pip to be able to compile the Python packages in requirements-python2.txt, otherwise the packages will not install (may work if "wheel" is installed if a binary wheel for Python 2 is still available on pypi).

#### Debian-based (such as Ubuntu)
- python2-dev

### Python 3

#### RPM-based (such as Fedora)
- gtk-devel

#### Debian-based distros (such as Ubuntu)
- libgtk-3-dev


## Using icon names
An icon name obtained using `xdg-icon-list` such as "folder" can be used as follows in an XDG ".desktop" file's "[Desktop Entry]" section:
```
Icon=folder
```
