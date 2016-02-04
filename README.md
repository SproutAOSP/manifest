### SproutAOSP

This is the manifest for SproutAOSP

To sync and build

``` repo init -u https://github.com/SproutAOSP/manifest.git -b 6
	repo sync
	source build/envsetup.sh
	lunch aosp_sprout4-userdebug
	make -j$(nproc) otapackage
```