# TWRP Samsung Galaxy A50s
![Galaxy A50s](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a50s.jpg "Galaxy A50s")
# How-to install dependencies
```
# How-to clone source and device tree:

mkdir -p ~/twrp && cd ~/twrp

$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone a50s repo
```
$ git clone https://github.com/topser9/twrp_device_samsung_a50s.git device/samsung/a50s
```
Sync
```
$ repo sync
```
# How-to build:
```
$ export ALLOW_MISSING_DEPENDENCIES=true
 . build/envsetup.sh
 lunch omni_a50s-eng
 mka recoveryimage
```
## How to find the image built
```
`cd /out/target/product/a50s`
```
see recovery.img
```
# Device Tree for Samsung Galaxy A50s (SM-A507FN/DS)

Device Tree Made by topser99
```
