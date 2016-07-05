#### Test 7214543196063dc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543196063dc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/521D80E1-D7BA-47C7-9AA7-DAA9BCBAFA59/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/521D80E1-D7BA-47C7-9AA7-DAA9BCBAFA59/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543196063dc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543196063dc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50263"
,(lldb)     command script import "/tmp/521D80E1-D7BA-47C7-9AA7-DAA9BCBAFA59/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 14:01:43.331 ThaliTest[3679:13598388] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/093424E1-E7E6-48D5-A5CC-FB982C5131ED/Library/Cookies/Cookies.binarycookies
,2016-07-05 14:01:43.559 ThaliTest[3679:13598388] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 14:01:43.559 ThaliTest[3679:13598388] Multi-tasking -> Device: YES, App: YES
,2016-07-05 14:01:43.572 ThaliTest[3679:13598388] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 14:01:44.370 ThaliTest[3679:13598388] Using UIWebView
,2016-07-05 14:01:44.372 ThaliTest[3679:13598388] [CDVTimer][handleopenurl] 0.105977ms
,2016-07-05 14:01:44.374 ThaliTest[3679:13598388] [CDVTimer][intentandnavigationfilter] 1.948953ms
2016-07-05 14:01:44.374 ThaliTest[3679:13598388] [CDVTimer][gesturehandler] 0.095963ms
2016-07-05 14:01:44.374 ThaliTest[3679:13598388] [CDVTimer][TotalPluginStartup] 2.593994ms
,2016-07-05 14:01:47.594 ThaliTest[3679:13598388] Resetting plugins due to page load.
,2016-07-05 14:01:48.991 ThaliTest[3679:13598388] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/index.html
,2016-07-05 14:01:49.128 ThaliTest[3679:13598388] JXcore Cordova plugin initializing
,2016-07-05 14:01:49.128 ThaliTest[3679:13598565] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-05 14:01:55.610 ThaliTest[3679:13598565] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-05 14:01:55.610 ThaliTest[3679:13598565] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-05 14:01:55.610 ThaliTest[3679:13598565] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-05 14:01:55.611 ThaliTest[3679:13598565] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB4D6776-2DD9-4E58-9A14-A4A699713632/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-05 14:02:00.829 ThaliTest[3679:13598388] THREAD WARNING: ['JXcore'] took '4943.793213' ms. Plugin should use a background thread.

```
