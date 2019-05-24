# PinkFox OS for Android-x86
Pinkfox OS on Android-x86 platform

Based on https://github.com/ric96/lineagex86 

## Instructions

$ mkdir android-x86

$ cd android-x86

$ repo init -u git://git.osdn.net/gitroot/android-x86/manifest -b marshmallow-x86

replace cm.xml .repo/manifests

$ repo init -m cm.xml

$ repo sync --no-tags --no-clone-bundle