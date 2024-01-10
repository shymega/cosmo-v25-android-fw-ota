Cosmo Communicator: Android V25 OTA package
===========================================

This is an the OTA package for Cosmo Communicator Android (NOT rooted)
firmware, V25.

## Things to know

You must be using Android V23, which you can get from [here][v23-community]
(using Fastboot to flash - the bootloader must be unlocked!), or from
[here][v23-planet] (using the custom multi-boot recovery functionality to
flash; requires V19 FW minimum).

You should also be booted into NON-rooted Android on your Cosmo Communicator.
Remember to flash the V25 rooted Android boot image when the OTA update is
complete.

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

[v23-community]: https://github.com/planet-community-org/cosmo-v23-android-stock-fw
[v23-planet]: https://support.planetcom.co.uk/index.php/Cosmo_Android_Firmware_Manual_Installation
