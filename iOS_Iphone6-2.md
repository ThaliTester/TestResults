#### Test 836273372e7ca3d_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B7F42D28-C0B8-4C4A-86F6-54E89F6214B7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B7F42D28-C0B8-4C4A-86F6-54E89F6214B7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C41E675E-1CE5-47D6-A1C8-B225E639E95A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59919"
,(lldb)     command script import "/tmp/B7F42D28-C0B8-4C4A-86F6-54E89F6214B7/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 00:16:03.043 ThaliTest[550:610445] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21B51553-3CFD-4FF1-B09F-CEF9B4F67FE8/Library/Cookies/Cookies.binarycookies
,2016-09-13 00:16:03.338 ThaliTest[550:610445] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 00:16:03.340 ThaliTest[550:610445] Multi-tasking -> Device: YES, App: YES
,2016-09-13 00:16:03.364 ThaliTest[550:610445] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 00:16:03.922 ThaliTest[550:610445] Using UIWebView
,2016-09-13 00:16:03.932 ThaliTest[550:610445] [CDVTimer][handleopenurl] 0.394046ms
,2016-09-13 00:16:03.939 ThaliTest[550:610445] [CDVTimer][intentandnavigationfilter] 7.214010ms
2016-09-13 00:16:03.940 ThaliTest[550:610445] [CDVTimer][gesturehandler] 0.324011ms
2016-09-13 00:16:03.940 ThaliTest[550:610445] [CDVTimer][TotalPluginStartup] 9.555042ms
,2016-09-13 00:16:09.662 ThaliTest[550:610445] Resetting plugins due to page load.
,2016-09-13 00:16:10.196 ThaliTest[550:610445] Finished load of: file:///var/containers/Bundle/Application/C41E675E-1CE5-47D6-A1C8-B225E639E95A/ThaliTest.app/www/index.html
,2016-09-13 00:16:10.593 ThaliTest[550:610445] JXcore Cordova plugin initializing
,2016-09-13 00:16:10.593 ThaliTest[550:610648] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 00:16:17.135 ThaliTest[550:610648] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 00:16:17.135 ThaliTest[550:610648] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 00:16:17.136 ThaliTest[550:610648] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 00:16:17.137 ThaliTest[550:610648] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
