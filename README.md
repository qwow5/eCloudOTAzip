# eNextcloudOTAzip
An Android OTA flashable zip that contains the Account Manager and eDrive apps from /e/.

Requies Android 7.0 or later.

## Installation

### Android 7.x

Download the OTA zip for Android 7.x [here](https://github.com/qwow5/eNextcloudOTAzip/releases/download/v1.0/eNextcloudOTAzip7.zip)

Flash using your preferred recovery.

### Android 8.0 and later

Download the OTA zip for Android 8.0+ [here](https://github.com/qwow5/eNextcloudOTAzip/releases/download/v1.0/eNextcloudOTAzip8.zip)

Flash using your preferred recovery.

#### Important note for A/B devices

OTA zips may not install properly on A/B devices. For A/B devices, it is recomended to push the apks manually instead.

Run the commands below to push the apks manually.
1. `git clone https://github.com/qwow5/eNextcloudOTAzip.git`
2. `cd eNextcloudOTAzip/Android8.0+`
3. `adb push ./system/priv-app/eDrive /system/priv-app/eDrive`
4. `adb push ./system/app/AccountManager /system/app/AccountManager`
