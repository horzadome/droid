OTA update channel for Prestigio PAP 4040
=====

Installation
--------------

I would not recommend anyone using anything here yet, because it's all totally untested and only works for me.

At the time, you have to be rooted and have ClockWork Mod Recovery installed on your phone.
After that, you should:

Step 1: Append this to your phone's /system/build.prop
```java
### OTA Updater
otaupdater.otaid=h01pap404001
otaupdater.otaver=001
otaupdater.otatime=20130101-0001
otaupdater.sdcard.recovery=emmc
```
Step 2:
Install the "OTA Update Center" application from https://play.google.com/store/apps/details?id=com.otaupdater

For convenience, here is also a QR to that play store page:

![OTA Update Center on Google Play](http://chart.googleapis.com/chart?cht=qr&chs=150x150&choe=UTF-8&chld=H&chl=http://goo.gl/sT38E)
