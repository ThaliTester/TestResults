#### Test 859603041ea1ffb_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/19D8B9AB-9D72-475F-ACAA-9F81A75410D9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/19D8B9AB-9D72-475F-ACAA-9F81A75410D9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/23DB4E66-A4E7-4B6F-8D94-1FF92BE90D82/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51999"
,(lldb)     command script import "/tmp/19D8B9AB-9D72-475F-ACAA-9F81A75410D9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 03:11:35.506 ThaliTest[1181:1531149] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/600BE23F-8EB8-4258-BE71-FC1D00912EC2/Library/Cookies/Cookies.binarycookies
,2016-09-21 03:11:35.852 ThaliTest[1181:1531149] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 03:11:35.854 ThaliTest[1181:1531149] Multi-tasking -> Device: YES, App: YES
,2016-09-21 03:11:35.877 ThaliTest[1181:1531149] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 03:11:36.359 ThaliTest[1181:1531149] Using UIWebView
,2016-09-21 03:11:36.366 ThaliTest[1181:1531149] [CDVTimer][handleopenurl] 0.414014ms
,2016-09-21 03:11:36.374 ThaliTest[1181:1531149] [CDVTimer][intentandnavigationfilter] 7.301986ms
2016-09-21 03:11:36.375 ThaliTest[1181:1531149] [CDVTimer][gesturehandler] 0.314951ms
2016-09-21 03:11:36.375 ThaliTest[1181:1531149] [CDVTimer][TotalPluginS,tartup] 9.609997ms
,2016-09-21 03:11:42.537 ThaliTest[1181:1531149] Resetting plugins due to page load.
,2016-09-21 03:11:42.842 ThaliTest[1181:1531149] Finished load of: file:///var/containers/Bundle/Application/23DB4E66-A4E7-4B6F-8D94-1FF92BE90D82/ThaliTest.app/www/index.html
,2016-09-21 03:11:43.185 ThaliTest[1181:1531149] JXcore Cordova plugin initializing
,2016-09-21 03:11:43.186 ThaliTest[1181:1531355] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 03:11:49.749 ThaliTest[1181:1531355] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 03:11:49.750 ThaliTest[1181:1531355] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 03:11:49.750 ThaliTest[1181:1531355] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 03:11:49.752 ThaliTest[1181:1531355] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 03:11:50.138 ThaliTest[1181:1531355] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004850029945373535
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
