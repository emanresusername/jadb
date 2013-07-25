#JADB#
ADB client implemented in pure Java.

The Android Debug Bridge or ADB for short it a client-server architecture used to install android apps from an IDE or command line and to debug apps, etc.

The Android SDK Tools is available for the major platforms (Mac, Windows & Linux) and in there is a command line tool called adb that implements the ADB protocol.

This projects aims at providing an up to date implementation of the ADB protocol.

## Example ##
Usage cannot be simpler. Just create a `JadbConnection` and off you go.

    JadbConnection jadb = new JadbConnection();
	List<AndroidDevice> actual = jadb.getDevices();

## Protocol Description ##

An overview of the protocol can be found here: [Overview](https://github.com/cgjones/android-system-core/blob/master/adb/OVERVIEW.TXT)

A list of the available commands that a ADB Server may accept can be found here:
[Services](https://github.com/cgjones/android-system-core/blob/master/adb/SERVICES.TXT)


## Author ##
Samuel Carlsson <samuel.carlsson@gmai.com>