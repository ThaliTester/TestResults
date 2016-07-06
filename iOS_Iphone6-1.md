#### Test 7214543121d4f5c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/337145A1-39A8-4BA6-8CA6-5CF2E2EFF74B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/337145A1-39A8-4BA6-8CA6-5CF2E2EFF74B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50877"
,(lldb)     command script import "/tmp/337145A1-39A8-4BA6-8CA6-5CF2E2EFF74B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 13:52:11.159 ThaliTest[6395:19858269] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1FD96116-62A3-4CCF-8C7E-2201A512AC54/Library/Cookies/Cookies.binarycookies
,2016-07-06 13:52:11.387 ThaliTest[6395:19858269] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 13:52:11.388 ThaliTest[6395:19858269] Multi-tasking -> Device: YES, App: YES
,2016-07-06 13:52:11.402 ThaliTest[6395:19858269] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 13:52:12.180 ThaliTest[6395:19858269] Using UIWebView
2016-07-06 13:52:12.182 ThaliTest[6395:19858269] [CDVTimer][handleopenurl] 0.132024ms
2016-07-06 13:52:12.184 ThaliTest[6395:19858269] [CDVTimer][intentandnavigationfilter] 2.127051ms
2016-07-06 13:52:12.184 ThaliTest[6395:19858269] [CDVTimer][gesturehandler] 0.105023ms
2016-07-06 13:52:12.185 ThaliTest[6395:19858269] [CDVTimer][TotalPluginStartup] 2.788961ms
,2016-07-06 13:52:15.376 ThaliTest[6395:19858269] Resetting plugins due to page load.
,2016-07-06 13:52:16.774 ThaliTest[6395:19858269] Finished load of: file:///var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/index.html
,2016-07-06 13:52:16.930 ThaliTest[6395:19858269] JXcore Cordova plugin initializing
,2016-07-06 13:52:17.012 ThaliTest[6395:19858424] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 13:52:23.928 ThaliTest[6395:19858424] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-06 13:52:23.928 ThaliTest[6395:19858424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-06 13:52:23.928 ThaliTest[6395,:19858424] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-06 13:52:23.930 ThaliTest[6395:19858424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C8E9B79-0800-49A2-A36B-6F21F45B24B6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-06 13:52:29.590 ThaliTest[6395:19858269] THREAD WARNING: ['JXcore'] took '5370.197021' ms. Plugin should use a background thread.

```
