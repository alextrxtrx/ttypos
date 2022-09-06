https://ubuntuhandbook.org/index.php/2022/03/install-kernel-5-13-ubuntu-18-04/

ttyPos driver for PAX bank pinpads
===

This version 3.03 modified to run on modern kernels


To build localy

```
cd src
make all
sudo make install
```

To make package for Debian or Ubuntu

```
apt install build-essential dkms debhelper
dpkg-buildpackage
```
