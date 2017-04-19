## OpenWrt Chaos Calmer 15.05.1 firmware and packages for TP-Link Archer C7

Firmware is built from chaos_calmer branch of original OpenWrt source code
([9a1fd3e](https://github.com/openwrt/openwrt/tree/9a1fd3e313cedf1e689f6f4e342528ed27c09766))
with support of new Archer C7 v2.0 flash chip

[Manufacturer page](http://www.tp-link.com/en/products/details/cat-9_Archer-C7.html)

[Device page on OpenWrt Wiki](https://wiki.openwrt.org/toh/tp-link/archer-c5-c7-wdr7500)

Apart from firmware itself this repository contains over 4000 packages which is almost all packages available in openwrt

Firmware contains minimum changes comparing to original configuration:
* packages url is changed to point to this repository
* full wget and ca-certificates packages are included in firmware to allow downloading packages from this repository via https
* luci web ui is included in firmware

### Firmware

* [factory](https://zgmnkv.github.io/openwrt-dist/ar71xx/openwrt-15.05.1-ar71xx-generic-archer-c7-v2-squashfs-factory.bin) 
(for flashing from stock firmware to OpenWrt)
* [sysupgrade](https://zgmnkv.github.io/openwrt-dist/ar71xx/openwrt-15.05.1-ar71xx-generic-archer-c7-v2-squashfs-sysupgrade.bin)
(for flashing from another OpenWrt firmware to this one)
