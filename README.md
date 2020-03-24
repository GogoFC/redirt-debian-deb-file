# redirt-debian-deb-file

Removed libudev0 dependency from ../DEBIAN/control file and
Repackaged deb file to include old Ubuntu libudev0 library for Debian Buster as Buster comes with libudev1
`/reditr/reditr_3.0.0.0_amd64/lib/x86_64-linux-gnu/libudev.so.0.13.0 libudev.so.0`
Where ls -l `libudev.so.0 -> libudev.so.0.13.0` is symbolic link points to library.
`sudo apt install libpango1.0-0` is still needed to install the dpkg file

Works on my Debian version 10.3 Buster
