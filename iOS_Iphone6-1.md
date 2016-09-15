#### Test 829140738877506_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6A84D185-F436-4014-8CC9-BD9C8AD6AC24/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6A84D185-F436-4014-8CC9-BD9C8AD6AC24/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DED4FD72-256C-4CDE-92D7-A133150B06A7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52898"
,(lldb)     command script import "/tmp/6A84D185-F436-4014-8CC9-BD9C8AD6AC24/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 14:02:39.444 ThaliTest[714:865042] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C19C8CE7-F1FF-4D62-8D07-C4A67749878D/Library/Cookies/Cookies.binarycookies
,2016-09-15 14:02:39.518 ThaliTest[714:865042] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 14:02:39.520 ThaliTest[714:865042] Multi-tasking -> Device: YES, App: YES
,2016-09-15 14:02:39.539 ThaliTest[714:865042] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 14:02:39.976 ThaliTest[714:865042] Using UIWebView
,2016-09-15 14:02:39.984 ThaliTest[714:865042] [CDVTimer][handleopenurl] 0.373006ms
,2016-09-15 14:02:39.992 ThaliTest[714:865042] [CDVTimer][intentandnavigationfilter] 7.102013ms
2016-09-15 14:02:39.992 ThaliTest[714:865042] [CDVTimer][gesturehandler] 0.318050ms
2016-09-15 14:02:39.993 ThaliTest[714:865042] [CDVTimer][TotalPluginStartup,] 9.420037ms
,2016-09-15 14:02:45.302 ThaliTest[714:865042] Resetting plugins due to page load.
,2016-09-15 14:02:45.655 ThaliTest[714:865042] Finished load of: file:///var/containers/Bundle/Application/DED4FD72-256C-4CDE-92D7-A133150B06A7/ThaliTest.app/www/index.html
,2016-09-15 14:02:45.996 ThaliTest[714:865042] JXcore Cordova plugin initializing
,2016-09-15 14:02:45.997 ThaliTest[714:865217] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1088384a0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-15 14:03:04.686 ThaliTest[714:865042] BTM: attaching to BTServer
,2016-09-15 14:03:05.824 ThaliTest[714:865042] BTM: local device power state changed
2016-09-15 14:03:05.825 ThaliTest[714:865042] BTM: power is now off
,2016-09-15 14:03:06.579 ThaliTest[714:865042] BTM: local device power state changed
2016-09-15 14:03:06.603 ThaliTest[714:865042] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  13.08860200643539
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
