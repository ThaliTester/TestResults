#### Test 8362733705cfec3_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/58EBD588-071F-47A0-8F58-F4FDD1774B8C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/58EBD588-071F-47A0-8F58-F4FDD1774B8C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/07AABD0B-9622-4286-927B-C215FD60F1F7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56694"
,(lldb)     command script import "/tmp/58EBD588-071F-47A0-8F58-F4FDD1774B8C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 04:55:40.953 ThaliTest[504:522404] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5432FBF2-13D4-45A7-B34D-E6BEAF94491A/Library/Cookies/Cookies.binarycookies
,2016-09-12 04:55:41.512 ThaliTest[504:522404] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 04:55:41.515 ThaliTest[504:522404] Multi-tasking -> Device: YES, App: YES
,2016-09-12 04:55:41.558 ThaliTest[504:522404] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 04:55:42.276 ThaliTest[504:522404] Using UIWebView
2016-09-12 04:55:42.282 ThaliTest[504:522404] [CDVTimer][handleopenurl] 0.346005ms
,2016-09-12 04:55:42.292 ThaliTest[504:522404] [CDVTimer][intentandnavigationfilter] 9.308994ms
2016-09-12 04:55:42.293 ThaliTest[504:522404] [CDVTimer][gesturehandler] 0.310004ms
2016-09-12 04:55:42.293 ThaliTest[504:522404] [CDVTimer][TotalPluginStartup,] 11.379957ms
,2016-09-12 04:55:49.450 ThaliTest[504:522404] Resetting plugins due to page load.
,2016-09-12 04:55:50.071 ThaliTest[504:522404] Finished load of: file:///var/containers/Bundle/Application/07AABD0B-9622-4286-927B-C215FD60F1F7/ThaliTest.app/www/index.html
,2016-09-12 04:55:50.480 ThaliTest[504:522404] JXcore Cordova plugin initializing
,2016-09-12 04:55:50.481 ThaliTest[504:522623] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 04:55:57.057 ThaliTest[504:522623] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-12 04:55:57.057 ThaliTest[504:522623] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-12 04:55:57.058 ThaliTest[504:522623] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-12 04:55:57.060 ThaliTest[504:522623] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
