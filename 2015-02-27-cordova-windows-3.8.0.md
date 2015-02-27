---
layout: post
author:
    name: Sergey Grebnov
    url: https://twitter.com/sgrebnov
title:  "Apache Cordova Windows 3.8.0"
categories: announcements
tags: news releases
---

We are happy to announce that `Cordova Windows 3.8.0` has been released!

This release adds support for new Visual Studio 2015 Tools and has various other improvements. It will be the default Windows version when the cordova-cli 4.3.0 is released.

To upgrade:

    npm install -g cordova
    cd my_project
    cordova platform update windows

To add it explicitly:

    cordova platform add windows@3.8.0



For non-CLI projects or for pre-3.0 projects, refer to the [upgrade guides](http://cordova.apache.org/docs/en/edge/guide_platforms_index.md.html).

<!--more-->

## What's new in Windows

* [CB-7985](https://issues.apache.org/jira/browse/CB-7985) windows platform does not build with Visual Studio 14 CTP tools
* [CB-8515](https://issues.apache.org/jira/browse/CB-8515) Support DefaultLanguage selection for Windows
* [CB-8321](https://issues.apache.org/jira/browse/CB-8321) Add supported orientations config.xml preference handling for windows platform
* [CB-8525](https://issues.apache.org/jira/browse/CB-8525) Fix audit-license-headers check on Windows
* [CB-8400](https://issues.apache.org/jira/browse/CB-8400) Enable jshint for Windows platform and fix all jshint issues
* [CB-8417](https://issues.apache.org/jira/browse/CB-8417) moved platform specific js into platform
* [CB-8330](https://issues.apache.org/jira/browse/CB-8330) Added new unit tests
* [CB-8136](https://issues.apache.org/jira/browse/CB-8136) Implemented prototype for end to end and unit tests via Jasmine
