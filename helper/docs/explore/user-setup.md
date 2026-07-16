

# user-setup




## Explore

``` sh
apt-cache show live-config
```

```
Package: live-config
Version: 11.0.5
Installed-Size: 117
Maintainer: Debian Live Maintainers <debian-live@lists.debian.org>
Architecture: all
Depends: live-config-systemd | live-config-backend
Recommends: iproute2 | iproute, keyboard-configuration, live-config-doc, live-tools, locales | locales-all, sudo, user-setup
Suggests: pciutils, wget
Description-en: Live System Configuration Components
 The Debian Live project maintains the components to build Debian based Live
 systems and the official Debian Live images themselves.
 .
 live-config contains the components to configure a live system during the boot
 process (late userspace).
 .
 In addition to live-config, a backend for an init system is required, such as
 live-config-systemd.
Description-md5: 7b5c6a3c9d088e25e7d3fa33b230c875
Homepage: https://salsa.debian.org/live-team/live-config
Section: misc
Priority: optional
Filename: pool/main/l/live-config/live-config_11.0.5_all.deb
Size: 16256
MD5sum: 4ce2e10232a070e636dceb2ea040e008
SHA256: 2fba42fd76b60455714f23cfdd2998fcc632de9dd4c3d16f81b5e31855004304

```




## Notice

to run at chroot

``` sh
	apt install -y \
		live-boot \
		live-config \
		live-config-systemd \
	--install-recommends
```


**using `--install-recommends` , make sure `live-tools` and `user-setup` installed for `login`.**


* `apt-cache show live-config`
* `dpkg -l '*live*'`
* `dpkg -l 'user-setup'`
