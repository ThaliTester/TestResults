#### Test 6216742584ac8ae_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EC237C76-D9AE-4EB4-AD14-F27CD8E961B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EC237C76-D9AE-4EB4-AD14-F27CD8E961B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49775"
,(lldb)     command script import "/tmp/EC237C76-D9AE-4EB4-AD14-F27CD8E961B3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 03:03:48.638 ThaliTest[927:1390486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77528673-B6A3-401C-B4D9-7F2BD53CB62A/Library/Cookies/Cookies.binarycookies
,2016-03-09 03:03:48.977 ThaliTest[927:1390486] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-09 03:03:48.978 ThaliTest[927:1390486] Multi-tasking -> Device: YES, App: YES
,2016-03-09 03:03:48.999 ThaliTest[927:1390486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 03:03:50.777 ThaliTest[927:1390486] Using UIWebView
,2016-03-09 03:03:50.783 ThaliTest[927:1390486] [CDVTimer][handleopenurl] 0.410020ms
,2016-03-09 03:03:50.791 ThaliTest[927:1390486] [CDVTimer][intentandnavigationfilter] 7.353008ms
2016-03-09 03:03:50.792 ThaliTest[927:1390486] [CDVTimer][gesturehandler] 0.331998ms
2016-03-09 03:03:50.792 ThaliTest[927:1390486] [CDVTimer][TotalPluginStartup] 9.700954ms
,2016-03-09 03:03:57.557 ThaliTest[927:1390486] Resetting plugins due to page load.
,2016-03-09 03:04:01.283 ThaliTest[927:1390486] Finished load of: file:///var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/index.html
,2016-03-09 03:04:01.446 ThaliTest[927:1390486] JXcore Cordova plugin initializing
,2016-03-09 03:04:01.448 ThaliTest[927:1390708] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 03:04:08.739 ThaliTest[927:1390708] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-09 03:04:08.739 ThaliTest[927:1390708] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-09 03:04:08.739 ThaliTest[927:1390708] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 03:04:08.743 ThaliTest[927:1390708] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B35ACD3F-67A7-463F-B48C-CA3CE8BC1A8E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
