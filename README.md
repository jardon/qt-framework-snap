# QT Framework Snap
This repository contains the packaging metadata for creating a snap of the QT framework built from the official QT [sources]() hosted on Github. For more information on snaps, visit [snapcraft.io](https://snapcraft.io/). 

## Installing the Snap
The snap can be installed directly from the Snap Store. Follow the link below for more information.
<br>

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/qt-framework-6-5)

## Building the Snap
### Clone Repository
```bash
git clone https://github.com/jardon/qt-framework-snap.git
cd qt-framework
```
### Installing and Configuring Prerequisites
```bash
sudo snap install snapcraft --classic
sudo snap install lxd
sudo lxd init --auto
```
### Packing and Installing the Snap
```bash
snapcraft pack
sudo snap install ./qt-framework*.snap --devmode
```

## License
The QT Framework Snap is free software, distributed under the Apache
Software License, version 2.0. See
[LICENSE](https://github.com/canonical/qt-framework-snap/blob/6.5/LICENSE)
for more information.

## Trademark Notice
QT is a trademark or registered trademark of The QT Company.
Other trademarks are property of their respective owners.
