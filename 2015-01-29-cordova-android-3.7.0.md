---
layout: post
author:
    name: Joe Bowser
    url: https://twitter.com/infil00p
title:  "Apache Cordova Android 3.7.0"
categories: announcements
tags: news releases
---

We are happy to announce that `Cordova Android 3.7.0` has been released!

This release has various bug fixes, and will be the default Android version when the cordova-cli 4.1.0 is released.

To upgrade:

    npm install -g cordova
    cd my_project
    cordova platform update android

To add it explicitly:

    cordova platform add android@3.7.0



For non-CLI projects or for pre-3.0 projects, refer to the [upgrade guides](http://cordova.apache.org/docs/en/edge/guide_platforms_index.md.html).

<!--more-->

## What's new in Android

* [CB-8328](https://issues.apache.org/jira/browse/CB-8328) Allow plugins to handle certificate challenges (close #150)
* [CB-8201](https://issues.apache.org/jira/browse/CB-8201) Add support for auth dialogs into Cordova Android
* [CB-8255](https://issues.apache.org/jira/browse/CB-8255) Pass `arch` to gradle regardless of `cdvBuildMultipleApks`
* [CB-8255](https://issues.apache.org/jira/browse/CB-8255) Fix `cordova/build --gradleVar=--foo=bar` stripping off `=bar`
* [CB-8017](https://issues.apache.org/jira/browse/CB-8017) Add support for `<input type=file>` for Lollipop
* [CB-8329](https://issues.apache.org/jira/browse/CB-8239) Cancel outstanding ActivityResult requests when a new startActivityForResult occurs
* [CB-8280](https://issues.apache.org/jira/browse/CB-8280) android: Don't apply SplashScreenDelay when .show() is called explicitly
* [CB-4914](https://issues.apache.org/jira/browse/CB-4914) Fix build whitespace issue
* [CB-8210](https://issues.apache.org/jira/browse/CB-8210) Remove unused onDestroy channel (close #146)
* [CB-8026](https://issues.apache.org/jira/browse/CB-8026) Bumping up Android Version and setting it up to allow third-party cookies.  This might change later.
* [CB-8255](https://issues.apache.org/jira/browse/CB-8255) Use properties rather than environment variables for gradle settings
* [CB-8210](https://issues.apache.org/jira/browse/CB-8210) Drop events from native that occur before start-up
* [CB-8210](https://issues.apache.org/jira/browse/CB-8210) Use PluginResult for various events from native (close #144)
* [CB-8168](https://issues.apache.org/jira/browse/CB-8168) Add support for `cordova/run --list` (closes #139)
* [CB-8210](https://issues.apache.org/jira/browse/CB-8210) Use PluginResult instead of sendJavascript() for keyboard events (close #142)
* [CB-8228](https://issues.apache.org/jira/browse/CB-8228) Gradle: Allow plugins to use Maven dependencies
* [CB-8229](https://issues.apache.org/jira/browse/CB-8229) Gradle: Add CordovaLib as a dependency to all plugin sub-projects
* [CB-7980](https://issues.apache.org/jira/browse/CB-7980) Add --minSdkVersion and --versionCode flags to cordova/build command
* [CB-7980](https://issues.apache.org/jira/browse/CB-7980) Add 9 to versionCode for minSdk 20+ if not multiarch
* [CB-8204](https://issues.apache.org/jira/browse/CB-8204) Reinstate link tasks to avoid gradle build failures
* [CB-8143](https://issues.apache.org/jira/browse/CB-8143) Use gradle 2.2.1 instead of 1.12 to appease Android Studio 1.0 warning-on-startup
* [CB-8143](https://issues.apache.org/jira/browse/CB-8143) Use gradle plugin 1.0.0 for Android Studio 1.0.0
* [CB-8202](https://issues.apache.org/jira/browse/CB-8202) Fix gradle build signing when passwords provided interactively
* [CB-8176](https://issues.apache.org/jira/browse/CB-8176) Update Android SDK search path for Android Studio 1.0
* [CB-8079](https://issues.apache.org/jira/browse/CB-8079) Use activity class package name, but fallback to application package name when looking for splash screen drawable
* [CB-8147](https://issues.apache.org/jira/browse/CB-8147) Have corodva/build warn about unrecognized flags rather than fail
* [CB-7881](https://issues.apache.org/jira/browse/CB-7881) Android tooling shouldn't lock application directory
* [CB-3679](https://issues.apache.org/jira/browse/CB-3679) Move splashscreen logic into splashscreen plugin
* [CB-8143](https://issues.apache.org/jira/browse/CB-8143) Use the correct Android Gradle plugin for the installed Gradle version
* [CB-8119](https://issues.apache.org/jira/browse/CB-8119) Restart adb when we detect it's hung
* [CB-8112](https://issues.apache.org/jira/browse/CB-8112) Turn off mediaPlaybackRequiresUserGesture
* [CB-6153](https://issues.apache.org/jira/browse/CB-6153) Add a preference for controlling hardware button audio stream (DefaultVolumeStream)
* [CB-8081](https://issues.apache.org/jira/browse/CB-8081) Allow gradle builds to use Java 6 instead of requiring 7
* [CB-8031](https://issues.apache.org/jira/browse/CB-8031) Fix race condition that shows as ConcurrentModificationException
* [CB-7976](https://issues.apache.org/jira/browse/CB-7976) Use webView's context rather than Activity's context for intent receiver
* [CB-7974](https://issues.apache.org/jira/browse/CB-7974) Cancel timeout timer if view is destroyed
* [CB-7940](https://issues.apache.org/jira/browse/CB-7940) Disable exec bridge if bridgeSecret is wrong
* [CB-7758](https://issues.apache.org/jira/browse/CB-7758) Allow content-url-hosted pages to access the bridge
* [CB-7726](https://issues.apache.org/jira/browse/CB-7726) fix typo in gitignore: ant-built -> ant-build
* Replacing Math.random() with something a little more random.
* [CB-6511](https://issues.apache.org/jira/browse/CB-6511) Fixes build for android when app name contains unicode characters.
* [CB-7707](https://issues.apache.org/jira/browse/CB-7707) Added multipart PluginResult (close #125)
* [CB-7714](https://issues.apache.org/jira/browse/CB-7714) Teach check_reqs about brew's install location for android SDK
* [CB-6837](https://issues.apache.org/jira/browse/CB-6837) Fix leaked window when hitting back button while alert being rendered
* [CB-7674](https://issues.apache.org/jira/browse/CB-7674)  Added sleep to avoid null error after most recent change to not break API
* [CB-7674](https://issues.apache.org/jira/browse/CB-7674)  move preference activation back into onCreate()
* [CB-7634](https://issues.apache.org/jira/browse/CB-7634)  Detect JAVA_HOME properly on Ubuntu
* [CB-7410](https://issues.apache.org/jira/browse/CB-7410)  update the docs to match the actual title
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Use a standard build.gradle for all plugins
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Make gradle build only a single config for sub-libraries (release vs debug)
* [CB-7579](https://issues.apache.org/jira/browse/CB-7579)  Fix run script's ability to use non-arch-specific APKs
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Fix gradle asking for release password when building for debug
* [CB-7493](https://issues.apache.org/jira/browse/CB-7493)  Adds test-build command to package.json
* [CB-3445](https://issues.apache.org/jira/browse/CB-3445)  Make minSdkVersion and base versionCode settable through env vars
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Make key password optional & prompt for it when missing
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Fix gradle not copying all archs to out/ (broken by prev commit)
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Use aligned apk rather than unaligned apk when sorting
* [CB-7512](https://issues.apache.org/jira/browse/CB-7510)  Speed up gradle builds by building debug or release (not both)
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Add gradle environment vars for signing apks
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Change gradle android plugins from 0.10 -> 0.12
* [CB-7536](https://issues.apache.org/jira/browse/CB-7512)  check_reqs: windows tweaks + sdk manager error message
* [CB-7499](https://issues.apache.org/jira/browse/CB-7499)  support RTL text direction
* [CB-7554](https://issues.apache.org/jira/browse/CB-7554)  Use x86 apk when deploying to an intel device / emulator
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Fix logic for detecting SDK directory
* [CB-7536](https://issues.apache.org/jira/browse/CB-7536)  Tweak Android SDK not installed error message.
* [CB-7536](https://issues.apache.org/jira/browse/CB-7536)  Tweak error messages for missing JDK / SDK / AVDs
* [CB-7511](https://issues.apache.org/jira/browse/CB-7511)  Auto-detect android sdk when using stand-alone sdk installer
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Copy cordova.gradle file to project root on build
* [CB-7330](https://issues.apache.org/jira/browse/CB-7330)  Don't run check_reqs for bin/create.
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Read android target from project.properties if possible
* [CB-7512](https://issues.apache.org/jira/browse/CB-7512)  Determine SDK and build tools version dynamcally at build time
* [CB-7463](https://issues.apache.org/jira/browse/CB-7463)  Adding licence to project template gradle file
* [CB-7511](https://issues.apache.org/jira/browse/CB-7511)  Auto-detect Android SDK when Android Studio is installed
* [CB-7463](https://issues.apache.org/jira/browse/CB-7463)  Looked at the Apache BigTop git, gradle uses C-style comments
* [CB-7463](https://issues.apache.org/jira/browse/CB-7463)  Adding licences.  I don't know what the gradle syntax is for comments, that still needs to be done.
* [CB-7460](https://issues.apache.org/jira/browse/CB-7460)  Fixing bug with KitKat where the background colour would override the CSS colours on the application


