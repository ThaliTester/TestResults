#### Test 64613803f00187f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/292E20B3-F936-4DD4-8E2A-E12CFA42E5A0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/292E20B3-F936-4DD4-8E2A-E12CFA42E5A0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49350"
,(lldb)     command script import "/tmp/292E20B3-F936-4DD4-8E2A-E12CFA42E5A0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 14:10:53.147 ThaliTest[1867:4784135] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4759EB0E-138B-42B9-902E-40BAE74A9927/Library/Cookies/Cookies.binarycookies
,2016-03-30 14:10:53.252 ThaliTest[1867:4784135] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-30 14:10:53.254 ThaliTest[1867:4784135] Multi-tasking -> Device: YES, App: YES
,2016-03-30 14:10:53.274 ThaliTest[1867:4784135] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 14:10:54.471 ThaliTest[1867:4784135] Using UIWebView
2016-03-30 14:10:54.474 ThaliTest[1867:4784135] [CDVTimer][handleopenurl] 0.240982ms
,2016-03-30 14:10:54.480 ThaliTest[1867:4784135] [CDVTimer][intentandnavigationfilter] 5.472004ms
2016-03-30 14:10:54.481 ThaliTest[1867:4784135] [CDVTimer][gesturehandler] 0.216007ms
2016-03-30 14:10:54.481 ThaliTest[1867:4784135] [CDVTimer][TotalPluginStartup] 6.806970ms
,2016-03-30 14:10:59.580 ThaliTest[1867:4784135] Resetting plugins due to page load.
,2016-03-30 14:11:01.848 ThaliTest[1867:4784135] Finished load of: file:///var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/index.html
,2016-03-30 14:11:02.054 ThaliTest[1867:4784135] JXcore Cordova plugin initializing
,2016-03-30 14:11:02.181 ThaliTest[1867:4784289] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-30 14:11:16.362 ThaliTest[1867:4784289] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 14:11:16.362 ThaliTest[1867:4784289] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 14:11:16.363 ThaliTest[1867:4,784289] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 14:11:16.365 ThaliTest[1867:4784289] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B664ABC8-CC32-4E13-9893-3081AD5B1367/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup

```
