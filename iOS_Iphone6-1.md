#### Test 721454319a152ff_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DB53634C-4BBB-470C-950F-30EFE9FF1CEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DB53634C-4BBB-470C-950F-30EFE9FF1CEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50368"
,(lldb)     command script import "/tmp/DB53634C-4BBB-470C-950F-30EFE9FF1CEA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 15:04:16.373 ThaliTest[6325:19702814] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88F6D9DD-BA35-460D-ABE2-920DB41353F7/Library/Cookies/Cookies.binarycookies
,2016-07-05 15:04:16.606 ThaliTest[6325:19702814] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 15:04:16.607 ThaliTest[6325:19702814] Multi-tasking -> Device: YES, App: YES
,2016-07-05 15:04:16.622 ThaliTest[6325:19702814] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 15:04:17.411 ThaliTest[6325:19702814] Using UIWebView
2016-07-05 15:04:17.413 ThaliTest[6325:19702814] [CDVTimer][handleopenurl] 0.123978ms
,2016-07-05 15:04:17.417 ThaliTest[6325:19702814] [CDVTimer][intentandnavigationfilter] 3.495991ms
2016-07-05 15:04:17.417 ThaliTest[6325:19702814] [CDVTimer][gesturehandler] 0.120997ms
2016-07-05 15:04:17.417 ThaliTest[6325:19702814] [CDVTimer][TotalPlug,inStartup] 4.243970ms
,2016-07-05 15:04:20.537 ThaliTest[6325:19702814] Resetting plugins due to page load.
,2016-07-05 15:04:21.959 ThaliTest[6325:19702814] Finished load of: file:///var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/index.html
,2016-07-05 15:04:22.107 ThaliTest[6325:19702814] JXcore Cordova plugin initializing
,2016-07-05 15:04:22.107 ThaliTest[6325:19702974] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-05 15:04:29.332 ThaliTest[6325:19702974] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-05 15:04:29.332 ThaliTest[6325:19702974] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-05 15:04:29.333 ThaliTest[6325,:19702974] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-05 15:04:29.335 ThaliTest[6325:19702974] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F462A663-135A-4ADE-B634-B94919ED5E45/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
