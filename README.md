# eCloudOTAzip
An Android OTA flashable zip that contains the Account Manager and eDrive apps from /e/.

This allows non-/e/ ROMS (e.g LineageOS) to integrate with /e/ Cloud and Nextcloud servers.

Requies Android 7.0 or later.

More information [here](https://doc.e.foundation/what-s-e#3-description-of-e-online-services-at-ecloudglobal)

## Installation

### Android 7.x

Download the OTA zip for Android 7.x [here](https://github.com/qwow5/eCloudOTAzip/releases/download/v1.0/eCloudOTAzip7.zip)

Flash using your preferred recovery.

### Android 8.0 and later

Download the OTA zip for Android 8.0+ [here](https://github.com/qwow5/eCloudOTAzip/releases/download/v1.0/eCloudOTAzip8.zip)

Flash using your preferred recovery.

#### Important note for A/B devices

OTA zips may not install properly on A/B devices. For A/B devices, it is recomended to push the apks manually instead.

Run the commands below to push the apks manually.
1. `git clone https://github.com/qwow5/eCloudOTAzip.git`
2. `cd eCloudOTAzip/Android8.0+`
3. `adb push ./system/priv-app/eDrive /system/priv-app/eDrive`
4. `adb push ./system/app/AccountManager /system/app/AccountManager`

## Sources

The apks are sourced directly from /e/ [here](https://gitlab.e.foundation/e/os/android_prebuilts_prebuiltapks)
