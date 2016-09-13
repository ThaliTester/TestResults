#### Test 8362733700cd7fa_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7DD94DBA-0AD5-49D1-9BE4-035C05178E09/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7DD94DBA-0AD5-49D1-9BE4-035C05178E09/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D953EC1A-8E87-49B7-88F5-4B41ACCD4D38/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54165"
,(lldb)     command script import "/tmp/7DD94DBA-0AD5-49D1-9BE4-035C05178E09/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-13 03:55:36.573 ThaliTest[586:630979] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CE55DB89-937F-48F8-A11B-EE586E24F812/Library/Cookies/Cookies.binarycookies
,2016-09-13 03:55:36.915 ThaliTest[586:630979] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 03:55:36.917 ThaliTest[586:630979] Multi-tasking -> Device: YES, App: YES
,2016-09-13 03:55:36.942 ThaliTest[586:630979] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 03:55:37.468 ThaliTest[586:630979] Using UIWebView
,2016-09-13 03:55:37.475 ThaliTest[586:630979] [CDVTimer][handleopenurl] 0.573039ms
,2016-09-13 03:55:37.482 ThaliTest[586:630979] [CDVTimer][intentandnavigationfilter] 7.261992ms
2016-09-13 03:55:37.483 ThaliTest[586:630979] [CDVTimer][gesturehandler] 0.312030ms
2016-09-13 03:55:37.483 ThaliTest[586:630979] [CDVTimer][TotalPluginStartup,] 9.711981ms
,2016-09-13 03:55:43.338 ThaliTest[586:630979] Resetting plugins due to page load.
,2016-09-13 03:55:43.797 ThaliTest[586:630979] Finished load of: file:///var/containers/Bundle/Application/D953EC1A-8E87-49B7-88F5-4B41ACCD4D38/ThaliTest.app/www/index.html
,2016-09-13 03:55:44.193 ThaliTest[586:630979] JXcore Cordova plugin initializing
,2016-09-13 03:55:44.194 ThaliTest[586:631169] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 03:55:50.789 ThaliTest[586:631169] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 03:55:50.790 ThaliTest[586:631169] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 03:55:50.790 ThaliTest[586:631169] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 03:55:50.792 ThaliTest[586:631169] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
