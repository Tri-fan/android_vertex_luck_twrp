TWRP Device Tree for Vertex Impress Luck # rev. VLCK091864498
===========
Unoffical Build for MT6580 TWRP 
------------------

Compiling on Ubuntu 20.10
```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-8.1

repo sync -c

git clone https://github.com/tri-fan/android_device_vertex_luck_twrp device/Vertex/Luck

. build/envsetup.sh

lunch omni_Luck-eng

export LC_ALL=C

mka recoveryimage
```
