##### Disclaimer: The available resources and files from this repo are uploaded from many contributors. The files are unverified, untested, and could have not been officially released from Apple. So please consider your own risk before using any of them, We'll not bear any responsiblities toward your use under any circumstances.

# Xcode developer disk images

This repository is provided to host all developer disk images for iOS, tvOS, watchOS. If you need one of them, look it up here for convenience.

# DEVELOPER MODE required in iOS 16+

With device running iOS 16, DEVELOPER MODE is required, so that XCode can sync up with the iDevice.
To enable this, on the iDevice, Go to Settings > Privacy & Security > Developer Mode to show the Developer Mode toggle, and enable it.


## What's available?

### iOS - [release note](https://developer.apple.com/documentation/ios-ipados-release-notes)
* 16.4
* 16.1
* 16.0
* 15.5
* 15.4
* 15.2
* 15.0
* 14.7
* 14.6
* 14.5
* 14.4
* 14.3
* 14.2
* 14.0
* 13.7
* 13.6
* 13.5
* 13.4
* 13.3
* 13.2
* 13.1.2
* 13.1
* 13.0
* 12.3
* 12.2
* 12.1
* 12.0
* 11.4
* 11.3
* 11.2
* 11.1
* 11.0
* 10.3
* 10.2
* 10.1
* 10.0
* 9.3
* 9.2
* 9.1
* 9.0
* 8.4
* 8.3
* 8.2
* 8.1
* 8.0


### tvOS - [release note](https://developer.apple.com/documentation/tvos-release-notes)
* 16.4
* 16.1
* 16.0
* 15.6
* 15.4
* 15.2
* 15.0
* 14.7
* 14.6
* 14.5
* 14.4
* 14.3
* 14.2
* 14.0
* 13.4
* 13.3
* 13.2
* 13.0
* 12.3
* 12.2
* 12.1
* 12.0
* 11.4
* 11.3
* 11.2
* 11.1
* 11.0
* 10.2
* 10.1
* 10.0
* 9.2
* 9.1
* 9.0

### WatchOS - [release note](https://developer.apple.com/documentation/watchos-release-notes)
* 9.4
* 9.1
* 9.0
* 8.7
* 8.5
* 8.3
* 8.0
* 7.4
* 7.3
* 7.2
* 7.1
* 7.0
* 6.2
* 6.1
* 6.0
* 5.2
* 5.1
* 5.0
* 4.3
* 4.2
* 4.1
* 4.0
* 3.2
* 3.1
* 3.0
* 2.2
* 2.1
* 2.0

## Why We need disk images?

When your Apple device is upgraded to a new operating system, the current version of Xcode you have been using may not have the appropriate disk image matching that OS version. Consequently, you may encounter failures when attempting to push the build to the device using Xcode.
![Why We need disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/Why%20do%20you%20need%20to%20update%20disk%20image.png)

## Where to put the new disk images?

To locate the Xcode app, navigate to the Applications folder in Finder. Open the Xcode app and access its contents. From there, locate the target platform for which you intend to upgrade with the new disk image.

For convenience, you can immediately jump to these paths in Finder by the hotkey Cmd+Shift+G :

* iOS: /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport
* tvOS: /Applications/Xcode.app/Contents/Developer/Platforms/AppletvOS.platform/DeviceSupport
* watchOS: /Applications/Xcode.app/Contents/Developer/Platforms/WatchOS.platform/DeviceSupport

![Where is Xcode disk images](https://raw.githubusercontent.com/haikieu/xcode-developer-disk-image-all-platforms/master/where%20is%20my%20developer%20disk%20images.png)
