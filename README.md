# Cordova Wake Lock plugin

For iOS, by [Varsity Software](https://github.com/VarsitySoftware)

## Description

This plugin sets the wake lock permission for Android devices.  

## Installation

```
cordova plugin add https://github.com/VarsitySoftware/cordova-plugin-android-wake-lock
```

## Usage

There is nothing to do. Just add this plugin and the wake lock permission will automatically be added.  

This plugin was created because of a bug in Android 4.4.2 (KitKat) devices playing HTML5 videos in Cordova.  Playing these videos would cause the app to crash.  Checking the debug log, there was a message that the android.permission.WAKE_LOCK was missing.  This plugin adds that permission so that the AndroidManifest.xml files does not have to be manually edited.
