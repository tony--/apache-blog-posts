

`org.apache.cordova.battery-status@0.2.11`
### 0.2.11 (Sep 17, 2014)
* CB-7249 cordova-plugin-battery-status documentation translation: cordova-plugin-battery-status
* CB-6724 re-add accidental removed of var keyword
* CB-6957 renamed folder to tests + added nested plugin.xml
* added documentation for manual tests
* CB-6957 Style improvements on Manual tests

`org.apache.cordova.camera@0.3.2`
### 0.3.2 (Sep 17, 2014)
* CB-7551 \[Camera\]\[iOS 8\] Scaled images show a white line
* CB-7558 hasPendingOperation flag in Camera plugin's takePicture should be reversed to fix memory errors
* CB-7557 Camera plugin tests is missing a File dependency
* CB-7423 do cleanup after copyImage manual test
* CB-7471 cordova-plugin-camera documentation translation: cordova-plugin-camera
* CB-7413 Resolve 'ms-appdata' URIs with File plugin
* Fixed minor bugs with the browser
* CB-7433 Adds missing window reference to prevent manual tests failure on Android and iOS
* CB-7249 cordova-plugin-camera documentation translation: cordova-plugin-camera
* CB-4003 Add config option to not use location information in Camera plugin (and default to not use it)
* CB-7461 Geolocation fails in Camera plugin in iOS 8
* CB-7378 Use single Proxy for both windows8 and windows.
* CB-7378 Adds support for windows platform
* CB-7433 Fixes manual tests failure on windows
* CB-6958 Get the correct default for "quality" in the test
* add documentation for manual tests
* CB-7249 cordova-plugin-camera documentation translation: cordova-plugin-camera
* CB-4003 Add config option to not use location information in Camera plugin (and default to not use it)
* CB-7461 Geolocation fails in Camera plugin in iOS 8
* CB-7433 Fixes manual tests failure on windows
* CB-7378 Use single Proxy for both windows8 and windows.
* CB-7378 Adds support for windows platform
* CB-6958 Get the correct default for "quality" in the test
* add documentation for manual tests
* Updated docs for browser
* Added support for the browser
* CB-7286 \[BlackBerry10\] Use getUserMedia if camera card is unavailable
* CB-7180 Update Camera plugin to support generic plugin webView UIView (which can be either a UIWebView or WKWebView)
* Renamed test dir, added nested plugin.xml
* CB-6958 added manual tests
* CB-6958 Port camera tests to plugin-test-framework

`org.apache.cordova.console@0.2.11`
### 0.2.11 (Sep 17, 2014)
* CB-7249 cordova-plugin-console documentation translation

`org.apache.cordova.contacts@0.2.13`
### 0.2.13 (Sep 17, 2014)
* CB-7546 \[Contacts\]\[iOS\] pickContact shows exception in the console log
* CB-6374 Fix iOS 6 deprecation warnings in Contacts
* CB-7544 \[Contacts\]\[iOS 8\] Contact picker is read-only in iOS 8
* CB-7523 Fixing "ContactFieldType" error in the config.xml
* CB-6724 Empty may be expected.
* CB-7249 cordova-plugin-contacts documentation translation
* Add missing test, skip some specs on wp
* rm old test folder and merged with renamed tests folder
* CB-7290 Adds support for universal Windows platform.
* Renamed test dir, added nested plugin.xml
* CB-7148 Added manual tests
* Removed js-module for tests from plugin.xml
* Changing cdvtest format to use module exports
* register tests using new style
* convert test to new style
* added documentation for manual tests
* merged changes for test framework plugin

`org.apache.cordova.device@0.2.12`
### 0.2.12 (Sep 17, 2014)
* CB-7471 cordova-plugin-device documentation translation
* CB-7552 device.name docs have not been removed
* \[fxos\] Fix cordova version
* added status box and documentation to manual tests
* \[fxos\] Fix cordova version
* added status box and documentation to manual tests
* Added plugin support for the browser
* CB-7262 Adds support for universal windows apps.

`org.apache.cordova.device-motion@0.2.10`
### 0.2.10 (Sep 17, 2014)
* CB-7471 cordova-plugin-device-motion documentation translation: cordova-plugin-device-motion
* Updated doc for browser
* Added support for the browser
* CB-7249 cordova-plugin-device-motion documentation translation
* [CB-7313] minor tweak to documentation of watchAcceleration function parameters
* CB-7160 move to tests dir, add nested plugin.xml
* Removed js-module for tests from plugin.xml
* CB-7160 added manual tests
* added documentation for manual tests
* Removed js-module for tests from plugin.xml
* CB-7160 added manual tests
* Changing cdvtest format to use module exports
* register tests using new style
* update
* Feature Branch: First attempt at new-style-tests

`org.apache.cordova.device-orientation@0.3.9`
### 0.3.9 (Sep 17, 2014)
* CB-7471 cordova-plugin-device-orientation documentation translation: cordova-plugin-device-orientation
* Fixed problem with watchCompass if pressed twice
* CB-7086 Renamed dir, added nested plugin.xml
* added documentation for manual tests
* Fixed problem with watchCompass if pressed twice
* CB-7086 Renamed dir, added nested plugin.xml
* added documentation for manual tests
* Updated docs for browser
* Add support for the browser
* CB-7249 cordova-plugin-device-orientation documentation translation
* CB-6960 Added manual tests
* CB-6960 Port compass tests to plugin-test-framework

`org.apache.cordova.dialogs@0.2.10`
### 0.2.10 (Sep 17, 2014)
* CB-7538 Android beep thread fix Beep now executes in it's own thread. It was previously executing in the main UI thread which was causing the application to lock up will the beep was occurring.  Closing pull request
* Set dialog text dir to locale
* Renamed test dir, added nested plugin.xml
* added documentation for manual tests
* CB-6965 Added manual tests
* CB-6965 Port notification tests to test-framework

`org.apache.cordova.file@1.3.1`
### 1.3.1 (Sep 17, 2014)
* CB-7471 cordova-plugin-file documentation translation
* CB-7272 Replace confusing "r/o" abbreviation with just "r"
* CB-7423 encode path before attempting to resolve
* CB-7375 Fix the filesystem name in resolveLocalFileSystemUri
* CB-7445 \[BlackBerry10\] resolveLocalFileSystemURI - change DEFAULT_SIZE to MAX_SIZE
* CB-7458 \[BlackBerry10\] resolveLocalFileSystemURL - add filesystem property
* CB-7445 \[BlackBerry10\] Add default file system size to prevent quota exceeded error on initial install
* CB-7431 Avoid calling done() twice in file.spec.109 test
* CB-7413 Adds support of 'ms-appdata://' URIs
* CB-7422 \[File Tests\] Use proper fileSystem to create fullPath
* CB-7375 \[Entry\] get proper filesystem in Entry
* Amazon related changes.
* CB-7375 Remove leading slash statement from condition
* Refactored much of the logic in FileMetadata constructor.  Directory.size will return 0
* CB-7419 \[WP8\] Added support to get metada from dir
* CB-7418 \[DirectoryEntry\] Added fullPath variable as part of condition
* CB-7417 \[File tests\] added proper matcher to compare fullPath property
* CB-7375 Partial revert to resolve WP8 failures
* Overwrite existing file on getFile when create is true
* CB-7375 CB-6148: Ensure that return values from copy and move operations reference the correct filesystem
* CB-6724 changed style detail on documentation
* Added new js files to amazon-fireos platform.
* Adds Windows platform
* Fixes multiple mobilespec tests errors
* Removed test/tests.js module from main plugin.xml
* CB-7094 renamed folder to tests + added nested plugin.xml
* added documentation for manual tests
* CB-6923 Adding support to handle relative paths
* Style improvements on Manual tests
* CB-7094 Ported File manual tests

`org.apache.cordova.file-transfer@0.4.6`
### 0.4.6 (Sep 17, 2014)
* CB-7471 cordova-plugin-file-transfer documentation translation
* CB-7249 cordova-plugin-file-transfer documentation translation
* CB-7423 fix spec28,29 lastProgressEvent not visible to afterEach function
* Amazon related changes.
* Remove dupe file windows+windows8 both use the same one
* CB-7316 Updates docs with actual information.
* CB-7316 Adds support for Windows platform, moves \*Proxy files to proper directory.
* CB-7316 Improves current specs compatibility:
* added documentation for new test
* CB-6466 Fix failing test due to recent url change
* CB-6466 created mobile-spec test
* Renamed test dir, added nested plugin.xml and test
* Fixed failing spec.19 on wp8
* added documentation to manual tests
* CB-6961 port file-transfer tests to framework

`org.apache.cordova.geolocation@0.3.10`
### 0.3.10 (Sep 17, 2014)
* CB-7556 iOS: Clearing all Watches does not stop Location Services
* CB-7158 Fix geolocation for ios 8
* Revert CB-6911 partially (keeping Info.plist key installation for iOS 8)
* CB-6911 - Geolocation fails in iOS 8
* CB-5114 Windows 8.1 - Use a new proxy as old geolocation methods is deprecated
* CB-5114 Append Windows 8.1 into plugin.xml + Optimize Windows 8 Geolocation proxy
* Renamed test dir, added nested plugin.xml
* added documentation for manual tests
* CB-7146 Added manual tests
* Removed js-module for tests from plugin.xml
* Changing cdvtest format to use module exports
* register tests using new style
* Convert tests to new style
* Removed amazon-fireos code for geolocation.

`org.apache.cordova.globalization@0.3.1`
### 0.3.1 (Sep 17, 2014)
* CB-6490 \[BlackBerry10\] Use hyphen instead of underscore in getLocaleName().
* CB-7548 \[BlackBerry10\] Allow any numeric type as date in dateToString method.
* Hold the information if L10n was ready before.
* CB-7233 \[BlackBerry10\] Globalization is now supported
* Renamed test dir, added nested plugin.xml
* Clean-up: removed duplicate code
* Added test to complete CB-7064, added tests that check for W3C compliance in language tags generated from PreferredLanguage and GetLocale methods
* CB-6962 Ported globalization tests to framework

`org.apache.cordova.inappbrowser@0.5.2`
### 0.5.2 (Sep 17, 2014)
* CB-7471 cordova-plugin-inappbrowser documentation translation: cordova-plugin-inappbrowser
* CB-7490 Fixes InAppBrowser manual tests crash on windows platform
* CB-7249 cordova-plugin-inappbrowser documentation translation: cordova-plugin-inappbrowser
* CB-7424 Wrong docs: anchor tags are not supported by the InAppBrowser
* CB-7133 clarify that anchor1 doesn't exist
* CB-7133 more fixup of tests on Android
* CB-7133 fix up the tests for Android
* Add just a bit more logging
* CB-7133 port inappbrowser to plugin-test-framework
* phonegap events supported for \_blank target
* inappbrowser \_blank target position is fixed
* amazon-fireos related changes.

`org.apache.cordova.media@0.2.13`
### 0.2.13 (Sep 17, 2014)
* CB-6963 renamed folder to tests + added nested plugin.xml
* added documentation for manual tests
* CB-6963 Port Media manual & automated tests
* CB-6963 Port media tests to plugin-test-framework

`org.apache.cordova.media-capture@0.3.3`
### 0.3.3 (Sep 17, 2014)
* Renamed test dir, added nested plugin.xml
* added documentation for manual tests
* CB-6959 Added manual tests
* CB-6959 Port capture tests to plugin-test-framework

`org.apache.cordova.network-information@0.2.12`
### 0.2.12 (Sep 17, 2014)
* CB-7471 cordova-plugin-network-information documentation translation
* Fix network information type exception on fxos 2
* Added support for the browser
* CB-6724 added documentation for manual tests
* remove reference to test assets, they are optional
* Renamed test dir and added nested plugin.xml
* CB-6964 ported manual tests
* Port network tests to plugin-test-framework
* Fix naviagtor typo

`org.apache.cordova.splashscreen@0.3.3`
### 0.3.3 (Sep 17, 2014)
* CB-7249 cordova-plugin-splashscreen documentation translation
* Renamed test dir, added nested plugin.xml
* added documentation for manual tests
* CB-7196 port splashscreen tests to framework

`org.apache.cordova.statusbar@0.1.8`
### 0.1.8 (Sep 17, 2014)
* CB-7549 \[StatusBar\]\[iOS 8\] Landscape issue
* CB-7486 Remove StatusBarBackgroundColor intial preference (black background) so background will be initially transparent
* Renamed test dir, added nested plugin.xml
* added documentation for manual tests, moved background color test below overlay test
* CB-7195 ported statusbar tests to framework

`org.apache.cordova.vibration@0.3.11`
### 0.3.11 (Sep 17, 2014)
* CB-7249 cordova-plugin-vibration documentation translation
* CB-6724 documented Windows support for vibrate with pattern and cancel vibrate in manual test doc and moved tests to tests dir
* add longer pattern sequence for testing, change expected result for old vibrate with pattern test
* added more test cases, changed vibrate with pattern durations, changed where vibrateOn is set to true
* clear settimeout when user cancels vibration
* add setTimeout function to update vibrateOn var if user doesn't cancel vibrate, add note about iOS
* on/off button for cancel tests, add results box and msgs
* added tests for old vibrateWithPattern and cancelVibration calls
* added 'Android only' to buttons for specific tests, changed where console.log is executed for user to see earlier
* added tests to ensure compliance with w3c spec
* CB-6963 ported vibration automated & manual tests
* CB-6966 renamed folder to tests + added nested plugin.xml
* CB-6966 Ported Vibration automated & manual tests
* removed duplicate messaging
* CB-5459 slight change to the vibration documentation for pattern due to merge issue
* changes to how 0 is getting added to array in order to align with w3c spec
* changes to vibration.java to align with w3c, changes to vibration.js for backwards compatibility
* changes made to align with w3c spec
* Updated doc with Windows support for vibrate with pattern
* Added note to doc about w3c alignment and min time for Windows
* update doc with another way to cancel vibration
* update doc to show vibrate(\[num\]) is a standard vibrate
* vibrate(\[num\]) is treated as a vibrate not vibrate with pattern
* added new example to documentation
* updated doc for w3c alignment
* changes to how 0 is getting added to array in order to align with w3c spec
* changes to vibration.java to align with w3c, changes to vibration.js for backwards compatibility
* changes made to align with w3c spec
