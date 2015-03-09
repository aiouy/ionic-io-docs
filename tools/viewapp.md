---
layout: default
---

<img src="/img/viewapp-logo.png">

Ionic View App
-----

<a href="https://itunes.apple.com/us/app/ionic-view/id849930087?mt=8&uo=4" target="itunes_store" style="display:inline-block;overflow:hidden;background:url(https://linkmaker.itunes.apple.com/htmlResources/assets/en_us//images/web/linkmaker/badge_appstore-lrg.png) no-repeat;width:135px;height:40px;@media only screen{background-image:url(https://linkmaker.itunes.apple.com/htmlResources/assets/en_us//images/web/linkmaker/badge_appstore-lrg.svg);}"></a>
<a href="https://play.google.com/store/apps/details?id=com.ionic.viewapp" style="margin-left: 20px">
  <img alt="Get it on Google Play"
       src="https://developer.android.com/images/brand/en_generic_rgb_wo_45.png" />
</a>

The Ionic View app makes it easy to test your Ionic apps on multiple devices without having to build
and distribute application binaries. For example, you can send a test build to a client
immediately, as long as the client downloads and installs the Ionic View app on an iOS or Android device.

## Supported plugins

The following is a list of plugins supported by View:

- com.brodysoft.sqlitePlugin 1.0.3 "Brodysoft SQLitePlugin"
- com.ionic.keyboard 1.0.3 "Keyboard"
- com.phonegap.plugins.barcodescanner 1.1.0 "BarcodeScanner"
- org.apache.cordova.battery-status 0.2.12 "Battery"
- org.apache.cordova.camera 0.3.4 "Camera"
- org.apache.cordova.console 0.2.12 "Console"
- org.apache.cordova.device 0.2.13 "Device"
- org.apache.cordova.device-motion 0.2.11 "Device Motion"
- org.apache.cordova.device-orientation 0.3.10 "Device Orientation"
- org.apache.cordova.dialogs 0.2.11 "Notification"
- org.apache.cordova.geolocation 0.3.11 "Geolocation"
- org.apache.cordova.globalization 0.3.3 "Globalization"
- org.apache.cordova.network-information 0.2.14 "Network Information"
- org.apache.cordova.vibration 0.3.12 "Vibration"
- org.chromium.zip 1.0.0 "Zip"

## Logging in

After you've installed the View app on iOS and/or Android, open it and either create a new Ionic account if you
don't have one, or log in with your existing account. This is the same login you use at <https://apps.ionic.io/>.

<img src="/img/viewapp/accounts-page.png" style="width: 200px">
<img src="/img/viewapp/login-page.png" style="width: 200px">
<img src="/img/viewapp/signup-page.png" style="width: 200px">

## First run

When you first open the app, you might see this screen, if you haven't uploaded any apps yet:

<img src="/img/viewapp/empty-state-page.png" style="width: 200px">

## Sharing apps

To share an app, you first need to `upload` it to the Ionic Platform. To do this, run:

```bash
$ ionic upload
```

in the root of your Ionic app code.

## Viewing apps

There are two ways to view apps: Have them in your account and view it from the master app list, or preview
one through an appid or QR code.

Tapping "Preview a shared app" lets you enter or scan a QR code to view that app. This is what a client or customer
will use to test your app:

<img src="/img/viewapp/preview-shared-app-page.png" style="width: 200px">

If you've uploaded an app into your account, and you are logged in, you should see your app in the app list on launch (pull-to-refresh to reload the data):

<img src="/img/viewapp/apps-list-page.png" style="width: 200px">

Tap one to view the app.

## App viewing controls

When viewing an app, the app will take up the full screen. To exit the app, swipe three fingers down:

<img src="http://a2.mzstatic.com/us/r30/Purple5/v4/d6/f2/76/d6f276b5-84e8-21fb-75cc-26b5a481a494/screen568x568.jpeg" style="width: 200px">
