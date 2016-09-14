The Android Open Source Project Nougat 7.0.0_r6
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/aosp-msm8960/manifest.git -b master
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
. build/envsetup.sh
lunch                 -> (device number)
make -j8 otapackage
```
