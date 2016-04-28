#### Test 68102130b92179b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/55FA2E47-7D84-446B-A761-B873E79EB654/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/55FA2E47-7D84-446B-A761-B873E79EB654/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54939"
,(lldb)     command script import "/tmp/55FA2E47-7D84-446B-A761-B873E79EB654/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 10:51:40.780 ThaliTest[1311:3911388] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A0127366-0BB7-42D1-9967-8F857EA9335A/Library/Cookies/Cookies.binarycookies
,2016-04-28 10:51:41.174 ThaliTest[1311:3911388] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 10:51:41.175 ThaliTest[1311:3911388] Multi-tasking -> Device: YES, App: YES
,2016-04-28 10:51:41.193 ThaliTest[1311:3911388] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 10:51:43.354 ThaliTest[1311:3911388] Using UIWebView
,2016-04-28 10:51:43.361 ThaliTest[1311:3911388] [CDVTimer][handleopenurl] 0.400007ms
,2016-04-28 10:51:43.370 ThaliTest[1311:3911388] [CDVTimer][intentandnavigationfilter] 8.811951ms
,2016-04-28 10:51:43.371 ThaliTest[1311:3911388] [CDVTimer][gesturehandler] 0.381947ms
,2016-04-28 10:51:43.371 ThaliTest[1311:3911388] [CDVTimer][TotalPluginStartup] 11.231005ms
,2016-04-28 10:51:51.063 ThaliTest[1311:3911388] Resetting plugins due to page load.
,2016-04-28 10:51:54.730 ThaliTest[1311:3911388] Finished load of: file:///var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/index.html
,2016-04-28 10:51:54.943 ThaliTest[1311:3911388] JXcore Cordova plugin initializing
,2016-04-28 10:51:54.944 ThaliTest[1311:3911658] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 10:52:01.534 ThaliTest[1311:3911658] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-28 10:52:01.535 ThaliTest[1311:3911658] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 10:52:01.535 ThaliTest[1311:3911658] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 10:52:01.536 ThaliTest[1311:3911658] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3E144945-9FD7-4E28-8FBF-99942AA3EB5A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 10:52:06.800 ThaliTest[1311:3911388] THREAD WARNING: ['JXcore'] took '4989.693359' ms. Plugin should use a background thread.

```
