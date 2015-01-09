---
layout: post
author:
    name: Steve Gill
    url: https://twitter.com/stevesgill
title:  "Tools Release: January 08, 2015"
categories: news
tags: release tools
---
New versions of cordova tools are now live!

* [cordova-lib@4.2.0](https://www.npmjs.org/package/cordova-lib)
* [cordova@4.2.0](https://www.npmjs.org/package/cordova)
* [plugman@0.22.17](https://www.npmjs.org/package/plugman)
* [cordova-js@3.7.3](https://www.npmjs.org/package/cordova-js)

To update your tools:

  * If you have `cordova` installed:

        npm install -g cordova

  * If you have `plugman` installed:

        npm install -g plugman

# Changes include
<!--more-->

## Platform updates
When adding these platforms to your project, the following versions are now used by default.
These platform versions were released recently, and the tools' defaults were updated:

* Cordova Ubuntu 4.0.0
* Cordova WP8 3.7.1
* Cordova BlackBerry10  3.7.0

## cordova-lib

* `ConfigParser`: refactor `getPreference()`
* Parsers: add base parser (`parser.js`) and make platform parsers inherit from it
* Parsers: assign methods without overriding the prototype
* CB-8225 Add Unit Tests for `platform.js/add` function (closes #138)
* CB-8230 Make `project.properties` optional for **Android** sub-libraries
* CB-8215 Improve error message when `<source-file>` is missing `target-dir` on **Android**
* CB-8217 Fix `plugin add --link` when plugin given as relative path
* CB-8216 Resolve plugin paths relative to original `CWD`
* CB-7311 Fix tests on **Windows** for `iOS parser`
* CB-7803 Allow adding any platform on any host OS (close #126)
* CB-8155 Do not fail plugin installation from `git url` with `--link` (close #129)
* Updates `README` with description of npm commands for this package
* CB-8129 Adds `npm run cover` command to generate tests coverage report (close #131)
* CB-8114 Specify a cache-min-time for plugins (closes #133)
* CB-8190 Make `plugman config/cache` directory to be customizable via `PLUGMAN_HOME` (close #134)
* CB-7863 Fixed broken test run on **Windows 8.1** caused by incorrect use of promises (close #132, close #112)
* CB-7610 Fix `cordova plugin add d:\path` (or any other non-c: path) (close #135)
* CB-8179 Corrected latest **WP8** version
* CB-8158 added `hasModule` check to browserify code
* CB-8173 Point to the latest **Ubuntu** version
* CB-8179 Point to the latest **WP8** version
* CB-8158 adding `symbolList` to `cordova.js`
* CB-8154 Fix errors adding platforms or plugins
* browserify: updated require to use `symbollist`
* Amazon related changes. Added a type named `gradleReference` in framework
* CB-7736 Update `npm` dep to promote `qs module` to 1.0
* Added a missing "else" keyword.
* CB-8086 Fixed framework tests.
* CB-8086 Prefixed subprojects with package name.
* CB-8067 externalized `valid-identifier` it is it's own module
* Added identifier checking for app id, searches for `java+C#` reserved words
* [CB-6472] Adding content to `-Info.plist` - Unexpected behaviour
* CB-8053: Including a project reference in a plugin fails on **Windows** platform.
* Pass the `searchpath` when installing plugins
* Add a type named `gradleReference` in framework

## cordova

* CB-6756 use `cordova_lib.binname` instead of `cordova`
* Fixed `jshint` issues with `cli.js` (close #199)
* CB-8211 Add `--link` option to `cordova plugin add` (close #191)
* CB-8129 Adds `npm run cover` command to generate tests coverage report
* `searchpath` option is added to restore

## cordova-js

* CB-8210 Use the correct plugin for `App/CoreAndroid` plugin based on platformVersion
* CB-8210 **Android**: Fire events from native via message channel (close #97)
* CB-8158 updated browserify dependency
* CB-8210 **Android**: Add message channel for events (closes #96)
* CB-8129 Adds `cover` grunt task to generate tests coverage report (close #95)
* **BlackBerry**: revert 4176a7d48b5d236613062fe2c8ba8655fd7b7c12
* **BlackBerry**: update grunt config to match coho platform name
* **Amazon** related change: `base64.toArrayBuffer` to convert `base64` strings
* CB-8158 removed extra `symbolList` declartion
* reverting license header
* CB-8158 populating `symbolList`

## plugman

* fixing broken link to **Chrome** plugins

## Pinned Platform Versions for Cordova CLI 4.2.0

* Cordova Amazon-FireOS: 3.6.3
* Cordova Android: 3.6.4
* Cordova BlackBerry10: 3.7.0
* Cordova Browser: 3.6.0
* Cordova FirefoxOS: 3.6.3
* Cordova iOS: 3.7.0
* Cordova Ubuntu: 4.0.0
* Cordova Windows: 3.7.1
* Cordova WP8: 3.7.1
