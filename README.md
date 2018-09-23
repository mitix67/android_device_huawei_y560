LineageOS 15.1 device configuration for [Huawei Y5](http://konstakang.com/devices/y560/CM14.1).

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/LineageOS/android.git -b lineage-15.1
    curl --create-dirs -L -o .repo/local_manifests/manifest_huawei_y560.xml -O -L https://gist.githubusercontent.com/mitix67/20edf99154c0a8e4ca6f03050f74dd98/raw/357492e86e6ae920b4ed3f1f725ca0ecfadf787c/manifest_huawei_y560.xml
    repo sync

Compile:

    . build/envsetup.sh
    brunch y560
