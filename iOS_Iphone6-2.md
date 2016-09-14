#### Test 83627337e0b549f_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/40397DE2-F801-4C29-9983-B005270BDF12/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/40397DE2-F801-4C29-9983-B005270BDF12/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/19CBB72A-993C-48CB-81F8-18A22FC2154A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57615"
,(lldb)     command script import "/tmp/40397DE2-F801-4C29-9983-B005270BDF12/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 00:26:37.000 ThaliTest[665:730183] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F8E65000-B857-46E0-A8CA-5FEC5CD4567F/Library/Cookies/Cookies.binarycookies
,2016-09-14 00:26:37.355 ThaliTest[665:730183] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 00:26:37.356 ThaliTest[665:730183] Multi-tasking -> Device: YES, App: YES
,2016-09-14 00:26:37.378 ThaliTest[665:730183] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 00:26:37.883 ThaliTest[665:730183] Using UIWebView
,2016-09-14 00:26:37.890 ThaliTest[665:730183] [CDVTimer][handleopenurl] 0.544012ms
,2016-09-14 00:26:37.898 ThaliTest[665:730183] [CDVTimer][intentandnavigationfilter] 7.266998ms
2016-09-14 00:26:37.899 ThaliTest[665:730183] [CDVTimer][gesturehandler] 0.338972ms
2016-09-14 00:26:37.900 ThaliTest[665:730183] [CDVTimer][TotalPluginStartup,] 9.899974ms
,2016-09-14 00:26:43.970 ThaliTest[665:730183] Resetting plugins due to page load.
,2016-09-14 00:26:44.264 ThaliTest[665:730183] Finished load of: file:///var/containers/Bundle/Application/19CBB72A-993C-48CB-81F8-18A22FC2154A/ThaliTest.app/www/index.html
,2016-09-14 00:26:44.608 ThaliTest[665:730183] JXcore Cordova plugin initializing
,2016-09-14 00:26:44.609 ThaliTest[665:730384] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 00:26:51.255 ThaliTest[665:730384] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 00:26:51.255 ThaliTest[665:730384] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 00:26:51.255 ThaliTest[665:730384] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 00:26:51.257 ThaliTest[665:730384] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
