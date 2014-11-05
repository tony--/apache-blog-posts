---
layout: post
author:
    name: Shazron Abdullah
    url: https://twitter.com/shazron
title:  "Apache Cordova iOS 3.7.0"
categories: announcements
tags: news releases
---

We are happy to announce that `Cordova iOS 3.7.0` has been released!

This release has various bug fixes, and will be the default iOS version when the cordova-cli 4.1.0 is released.
This release also requires Xcode 6.

To upgrade:

    npm install -g cordova
    cd my_project
    cordova platform update ios

To add it explicitly:

    cordova platform add ios@3.7.0



For non-CLI projects or for pre-3.0 projects, refer to the [upgrade guides](http://cordova.apache.org/docs/en/edge/guide_platforms_index.md.html).

<!--more-->

## What's new in iOS

* CB-7882 - viewDidUnload instance method is missing [super viewDidUnload] call
* CB-7872 - XCode 6.1's xcrun PackageApplication fails at packaging / resigning Cordova applications (closes #115)
* CB-6510 - Support for ErrorUrl preference on iOS
* CB-7857 - Load appURL after plugins have loaded
* CB-7606 - handleOpenURL handler firing more than necessary
* CB-7597 - Localizable.strings for Media Capture are in the default template, it should be in the plugin
* CB-7818 - CLI builds ignore Distribution certificates (closes #114)
* CB-7729 - Support ios-sim 3.0 (Xcode 6) and new targets (iPhone 6/6+) (closes #107)
* CB-7813 - Added unit test
* CB-7813 - CDVWebViewDelegate fails to update the webview state properly in iOS
* CB-7812 - cordova-ios xcode unit-tests are failing from npm test, in Xcode it is fine
* CB-7643 - made isValidCallbackId threadsafe
* CB-7735 - Update cordova.js snapshot with the bridge fix
* CB-2520 - built interim js from cordova-js for custom user agent support
* CB-2520 - iOS - "original" user agent needs to be overridable (closes #112)
* CB-7777 - In AppDelegate, before calling handleOpenURL check whether it exists first to prevent exceptions (closes #109)
* CB-7775 - Add component.json for component and duo package managers (closes #102)
* CB-7493 - Add e2e test for 'space-in-path' and 'unicode in path/name' for core platforms (moved from root folder).
* CB-7493 - Adds test-build command to package.json
* CB-7630 - Deprecate CDV_IsIPhone5 and CDV_IsIPad macro in CDVAvailability.h
* CB-7727 - add resolution part to 'backup to icloud' warning message
* CB-7627 - Remove duplicate reference to the same libCordova.a.
* CB-7648 - [iOS 8] Add iPhone 6 Plus icon to default template
* CB-7632 - [iOS 8] Add launch image definitions to Info.plist
* CB-7631 - CDVUrlProtocol - the iOS 8 NSHttpUrlResponse is not initialized with the statuscode
* CB-7596 - [iOS 8] CDV_IsIPhone5() Macro needs to be updated because screen size is now orientation dependent
* CB-7560 - Tel and Mailto links don't work in iframe
* CB-7450 - Fix deprecations in cordova-ios unit tests
* CB-7546 - [Contacts][iOS] Prevent exception when index is out of range
* CB-7450 - Fix deprecations in cordova-ios unit tests (interim checkin)
* CB-7502 - iOS default template is missing CFBundleShortVersionString key in Info.plist, prevents iTunes Connect submission
* Changed CordovaLibTests to run in a xcworkspace, and runnable from the command line
* Move CordovaLibTests into tests/
* Add ios-sim version check (3.0) to cordova/lib/list-emulator-images
* Fix cordova/lib/install-emulator to pass in the correct prefix for ios-sim --devicetypeid
* Fix cordova/lib/list-started-emulators for Xcode 6
* Remove non-working applescript to start emulator, use Instruments to start iOS Simulator now.
* Add support for the iPod in cordova/lib/list-devices script.
* Remove "Valid values for --target" in script headers. Use "cordova/lib/list-emulator-images" to get the list.
* Update cordova/lib/list-emulator-images for ios-sim 3.0
* Increment ios-deploy min version to 1.2.0 and ios-sim min version to 3.0
* Updated cordova/build script to use specific SHARED_PRECOMPS_DIR variable.
* Update .gitignore to not ignore .xcworkspace files
