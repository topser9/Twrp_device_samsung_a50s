# TWRP Samsung Galaxy A50s
![Galaxy A50s](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a50s.jpg "Galaxy A50s")
# How-to install dependencies
```
# How-to clone source and device tree:

mkdir -p ~/twrp && cd ~/twrp

repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone a50s repo
```
git clone https://github.com/topser9/twrp_device_samsung_a50s.git device/samsung/a50s
```
Sync
```
repo sync
```
# How-to build:
```
export ALLOW_MISSING_DEPENDENCIES=true
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

Device Tree Made by topser9
```
# Specs
|---------------------------------------------------------------------------------|
|      Component        |          Specification                                  |
|:----------------------|:--------------------------------------------------------|
| Dimensions            | 158.5 x 74.7 x 7.7 mm (6.24 x 2.94 x 0.30 in)           |
| Weight                | 166 g (5.86 oz)                                         |
| Type                  | Super AMOLED                                            |
| Size                  | 6.4 inches, 100.5 cm2 (~84.9% screen-to-body ratio)     |
| Resolution            | 1080 x 2340 pixels, 19.5:9 ratio (~403 ppi density)      |
| OS                    |  Android 9.0 (Pie), One UI                              |
| Chipset               | Exynos 9611 (10nm)                                     |
| CPU                   | Octa-core (4x2.3 GHz Cortex-A73 & 4x1.7 GHz Cortex-A53)|
| GPU                   | Mali-G72 MP3                                            |
| Internal              | 64GB 4GB RAM, 128GB 6GB RAM UFS 2.1                                  |
| USB                   | USB Type-C 2.0, USB On-The-Go                           |
| Battery               | Li-Po 4000 mAh, non-removable                           |
| charging              | Fast charging 15W                                       |
| Status                | Available. Released 2019, September                      |
|---------------------------------------------------------------------------------|
