Cosmo Communicator: Android V25 OTA package
===========================================

This is an the OTA package for Cosmo Communicator Android (NOT rooted)
firmware, V25.

## Things to know

You must be using Android V23, which you can get from [here][v23-gdrive]
(using Fastboot to flash - the bootloader must be unlocked!), or from
[here][v23-planet] (using the custom multi-boot recovery functionality to
flash; requires V19 FW minimum). 

**Attempts to update from any Android firmware version OTHER THAN V23 are not
supported!**

You should also be booted into NON-rooted Android on your Cosmo Communicator.
Remember to flash the V25 rooted Android boot image when the OTA update is
complete.

## Downloads?

You need to download this [file][v25-github] of the V25 OTA.

## Usage

The ZIP file should be named 'Updatepackage.zip' - all one word - and copy it to
the internal Cosmo storage. This should not be the SD card. It must be internal
storage, and in the top-level directory (also known as: root-level directory) of
internal storage.

The ZIP file can be installed by going to the usual 'Wireless Update' in the
Cosmo Settings on Android. Once you get to that screen, tap the top-right
menu, and click on 'Install from local storage'. The OTA updater should
automatically find the correct file, if it has been copied correctly, and prompt
you to update.

When your Cosmo is plugged in, and has enough battery, begin the update.

[v23-gdrive]: https://drive.google.com/drive/folders/129BJt4sGV0qQ1dG1txQVBpJopJ19px-3?usp=sharing
[v23-planet]: https://support.planetcom.co.uk/index.php/Cosmo_Android_Firmware_Manual_Installation
[v25-github]: https://github.com/shymega/cosmo-v25-android-fw-ota/raw/main/Updatepackage.zip
