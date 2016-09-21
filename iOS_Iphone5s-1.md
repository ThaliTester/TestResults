#### Test 85960304e9d96a8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3B918083-C070-4B8A-AE19-FFF3D01357D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3B918083-C070-4B8A-AE19-FFF3D01357D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B61C8E5-7527-46D5-812A-862396A0AE1A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55136"
,(lldb)     command script import "/tmp/3B918083-C070-4B8A-AE19-FFF3D01357D9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:04:23.352 ThaliTest[2755:5804162] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/540D9F14-6F68-4A8B-B89F-0F9F3678E4DD/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:04:23.639 ThaliTest[2755:5804162] Apache Cordova native platform version 4.2.1 is starting.
2016-09-21 13:04:23.640 ThaliTest[2755:5804162] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:04:23.661 ThaliTest[2755:5804162] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:04:24.472 ThaliTest[2755:5804162] Using UIWebView
2016-09-21 13:04:24.475 ThaliTest[2755:5804162] [CDVTimer][handleopenurl] 0.135005ms
,2016-09-21 13:04:24.478 ThaliTest[2755:5804162] [CDVTimer][intentandnavigationfilter] 2.819002ms
2016-09-21 13:04:24.478 ThaliTest[2755:5804162] [CDVTimer][gesturehandler] 0.168979ms
2016-09-21 13:04:24.478 ThaliTest[2755:5804162] [CDVTimer][TotalPluginStartup] 3.725946ms
,2016-09-21 13:04:27.513 ThaliTest[2755:5804162] Resetting plugins due to page load.
,2016-09-21 13:04:28.936 ThaliTest[2755:5804162] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B61C8E5-7527-46D5-812A-862396A0AE1A/ThaliTest.app/www/index.html
,2016-09-21 13:04:29.124 ThaliTest[2755:5804162] JXcore Cordova plugin initializing
,2016-09-21 13:04:29.125 ThaliTest[2755:5804353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:04:36.965 ThaliTest[2755:5804353] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 13:04:36.965 ThaliTest[2755:5804353] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 13:04:36.966 ThaliTest[2755:5804353] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 13:04:36.969 ThaliTest[2755:5804353] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:04:37.342 ThaliTest[2755:5804353] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.004579007625579834
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
