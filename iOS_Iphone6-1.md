#### Test 64613803717efd7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BFDF4C13-C7E2-4318-BB75-5525D0A043A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BFDF4C13-C7E2-4318-BB75-5525D0A043A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49699"
,(lldb)     command script import "/tmp/BFDF4C13-C7E2-4318-BB75-5525D0A043A9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 12:57:23.745 ThaliTest[2512:4681885] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68EFF596-92D5-45E7-B8C1-15692A0C7056/Library/Cookies/Cookies.binarycookies
,2016-03-31 12:57:23.979 ThaliTest[2512:4681885] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 12:57:23.980 ThaliTest[2512:4681885] Multi-tasking -> Device: YES, App: YES
,2016-03-31 12:57:23.996 ThaliTest[2512:4681885] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 12:57:24.781 ThaliTest[2512:4681885] Using UIWebView
2016-03-31 12:57:24.783 ThaliTest[2512:4681885] [CDVTimer][handleopenurl] 0.119984ms
2016-03-31 12:57:24.785 ThaliTest[2512:4681885] [CDVTimer][intentandnavigationfilter] 2.124012ms
2016-03-31 12:57:24.785 ThaliTest[2512:4681885] [CDVTimer][gesturehandler] 0.093997ms
2016-03-31 12:57:24.786 ThaliTest[2512:4681885] [CDVTimer][TotalPluginStartup] 2.756000ms
,2016-03-31 12:57:27.926 ThaliTest[2512:4681885] Resetting plugins due to page load.
,2016-03-31 12:57:29.315 ThaliTest[2512:4681885] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/index.html
,2016-03-31 12:57:29.483 ThaliTest[2512:4681885] JXcore Cordova plugin initializing
,2016-03-31 12:57:29.484 ThaliTest[2512:4682059] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 12:57:36.540 ThaliTest[2512:4682059] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 12:57:36.540 ThaliTest[2512:4682059] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 12:57:36.541 ThaliTest[2512:4682059] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 12:57:36.543 ThaliTest[2512:4682059] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE968B1-C36B-4EFE-99F0-6F1942E2FD7C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
