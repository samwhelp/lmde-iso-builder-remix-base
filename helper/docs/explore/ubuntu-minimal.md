

# Explore




## ubuntu-minimal

run

``` sh
apt-cache show ubuntu-minimal
```

show


```
Package: ubuntu-minimal
Source: ubuntu-meta
Priority: important
Section: metapackages
Installed-Size: 14
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Architecture: amd64
Version: 1.570
Recommends: rsyslog
Depends: adduser, apt, bsdutils, chrony | time-daemon, console-setup, debconf, debconf-i18n, dhcpcd-base, e2fsprogs, eject, init, iproute2, iputils-ping, kbd, kmod, less, locales, login, lsb-release, mawk, mount, netbase, netcat-openbsd, netplan.io, passwd, procps, python3, sensible-utils, sudo, sudo-rs, tzdata, ubuntu-keyring, ubuntu-pro-client, udev, vim-tiny, whiptail
Breaks: initramfs-tools (<< 0.142ubuntu9~)
Filename: pool/main/u/ubuntu-meta/ubuntu-minimal_1.570_amd64.deb
Size: 8500
MD5sum: aa62d8b0481242ece03ef2eb6120637e
SHA1: 0777697d579a02a033be78c948ecdc9b8a1337ae
SHA256: 9b6b62134b1f6fd2a9db458245a005fe3000d213363278f18072968090e671db
SHA512: c5984aaffca77ce0b40706136d14ade63e11e9386a256e10b52e8a53c64fabaccc6f2569855fa4a064b14ba8f47d2b58cf9679ea640ec9461d453a20f7aac8c1
Description-en: Minimal core of Ubuntu
 This package depends on all of the packages in the Ubuntu minimal system,
 that is a functional command-line system with the following capabilities:
 .
 - Boot
 - Detect hardware
 - Connect to a network
 - Install packages
 - Perform basic diagnostics
 .
 It is also used to help ensure proper upgrades, so it is recommended that
 it not be removed.
Description-md5: a9d15f68618ac3645a89a4af8b55d48d
Origin: Ubuntu
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Task: minimal
```
