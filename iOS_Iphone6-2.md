#### Test 836273372ac050d_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2274FB19-9D85-4861-8956-82FB10FF4F36/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/2274FB19-9D85-4861-8956-82FB10FF4F36/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C4C864BB-C844-4DF5-B212-6FED2BD20B7D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51910"
,(lldb)     command script import "/tmp/2274FB19-9D85-4861-8956-82FB10FF4F36/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 23:47:57.563 ThaliTest[785:849006] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36E86654-C820-43D2-9C2B-D8C3348B9C11/Library/Cookies/Cookies.binarycookies
,2016-09-14 23:47:57.972 ThaliTest[785:849006] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 23:47:57.974 ThaliTest[785:849006] Multi-tasking -> Device: YES, App: YES
,2016-09-14 23:47:57.998 ThaliTest[785:849006] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 23:47:58.480 ThaliTest[785:849006] Using UIWebView
,2016-09-14 23:47:58.487 ThaliTest[785:849006] [CDVTimer][handleopenurl] 0.452042ms
,2016-09-14 23:47:58.495 ThaliTest[785:849006] [CDVTimer][intentandnavigationfilter] 7.398963ms
2016-09-14 23:47:58.496 ThaliTest[785:849006] [CDVTimer][gesturehandler] 0.350952ms
2016-09-14 23:47:58.497 ThaliTest[785:849006] [CDVTimer][TotalPluginStartup,] 11.002958ms
,2016-09-14 23:48:04.941 ThaliTest[785:849006] Resetting plugins due to page load.
,2016-09-14 23:48:05.232 ThaliTest[785:849006] Finished load of: file:///var/containers/Bundle/Application/C4C864BB-C844-4DF5-B212-6FED2BD20B7D/ThaliTest.app/www/index.html
,2016-09-14 23:48:05.560 ThaliTest[785:849006] JXcore Cordova plugin initializing
,2016-09-14 23:48:05.561 ThaliTest[785:849197] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 23:48:12.106 ThaliTest[785:849197] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 23:48:12.106 ThaliTest[785:849197] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 23:48:12.107 ThaliTest[785:849197,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 23:48:12.108 ThaliTest[785:849197] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
