# MultiWindow SDK

[![Latest Stable Version](https://img.shields.io/badge/version-1.3.2-green.svg)](http://developer.samsung.com/galaxy/edge)

> __Note:__ 

> 1) Android N added support for Multi-Window. Hence, Samsung MultiWindow SDK is deprecated on those devices running on Android N (API Level 24) or higher.
In order to support Multi-Window on these OS versions, you must use the Android Multi-Window APIs in your application.
See the link below for more information about Android Multi-Window:
[https://developer.android.com/guide/topics/ui/multi-window.html](https://developer.android.com/guide/topics/ui/multi-window.html)
> 2) If you want to have MultiWindow support on Android N (API Level 24) and below, you must use both Android N Multi-Window APIs and Samsung MutliWindow SDK(ver 1.3.1 or higher) in your application.

MultiWindow SDK allows you to run multiple resizable applications simultaneously. You can add your application to the MultiWindow UI by declaring your application a MultiWindow application. Using MultiWindow user interface, users can run your application with other applications at the same time.

MultiWindow SDK supports Split Style, which divides screens equally, and Free Style, which enables the resizing of applications as desired.

![MultiWindow](http://developer.samsung.com/sd2_images/galaxy/content/SMS_MultiWindow_01_0902.jpg)

MultiWindow SDK provides the following features:

- Recent App
- MultiWindow Traybar
- Multi-Instance
- Paired Window
- Resize and Function

## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:ocean-services-multiwindow:1.3.2'
}
```

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
