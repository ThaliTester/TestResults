#### Test 7578926851a8f91_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4FF6D087-5173-4480-BC44-B7AEB38DED5A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4FF6D087-5173-4480-BC44-B7AEB38DED5A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64900"
,(lldb)     command script import "/tmp/4FF6D087-5173-4480-BC44-B7AEB38DED5A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 12:49:29.623 ThaliTest[6050:18835706] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB10E905-4CF6-4DB2-AD46-67B58F9BEEBC/Library/Cookies/Cookies.binarycookies
,2016-06-30 12:49:30.032 ThaliTest[6050:18835706] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 12:49:30.033 ThaliTest[6050:18835706] Multi-tasking -> Device: YES, App: YES
,2016-06-30 12:49:30.055 ThaliTest[6050:18835706] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 12:49:31.884 ThaliTest[6050:18835706] Using UIWebView
,2016-06-30 12:49:31.891 ThaliTest[6050:18835706] [CDVTimer][handleopenurl] 0.425041ms
,2016-06-30 12:49:31.899 ThaliTest[6050:18835706] [CDVTimer][intentandnavigationfilter] 7.470012ms
2016-06-30 12:49:31.900 ThaliTest[6050:18835706] [CDVTimer][gesturehandler] 0.331998ms
2016-06-30 12:49:31.901 ThaliTest[6050:18835706] [CDVTimer][TotalPlug,inStartup] 9.801030ms
,2016-06-30 12:49:39.314 ThaliTest[6050:18835706] Resetting plugins due to page load.
,2016-06-30 12:49:42.465 ThaliTest[6050:18835706] Finished load of: file:///var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/index.html
,2016-06-30 12:49:42.760 ThaliTest[6050:18835706] JXcore Cordova plugin initializing
,2016-06-30 12:49:42.762 ThaliTest[6050:18835923] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 12:49:50.293 ThaliTest[6050:18835923] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 12:49:50.294 ThaliTest[6050:18835923] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 12:49:50.294 ThaliTest[6050,:18835923] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 12:49:50.296 ThaliTest[6050:18835923] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A0BE7FD-8D6C-4999-88B1-AF97297E8E53/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 12:49:56.399 ThaliTest[6050:18835706] THREAD WARNING: ['JXcore'] took '5795.588867' ms. Plugin should use a background thread.
2016-06-30 12:49:56.400 ThaliTest[6050:18835706] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-06-30 12:49:56.400 ThaliTest[6050:18835706] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore293795499","JXcore","Test",[]]

```
