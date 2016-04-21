#### Test 672996567f6295f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C4559A80-555F-4B73-96F9-55AA05C4A9A6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C4559A80-555F-4B73-96F9-55AA05C4A9A6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54203"
,(lldb)     command script import "/tmp/C4559A80-555F-4B73-96F9-55AA05C4A9A6/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-21 08:01:37.519 ThaliTest[2605:8105598] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C2522C78-B838-434D-895B-E73FCCB0565F/Library/Cookies/Cookies.binarycookies
,2016-04-21 08:01:37.631 ThaliTest[2605:8105598] Apache Cordova native platform version 4.1.1 is starting.
2016-04-21 08:01:37.633 ThaliTest[2605:8105598] Multi-tasking -> Device: YES, App: YES
,2016-04-21 08:01:37.650 ThaliTest[2605:8105598] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-21 08:01:39.999 ThaliTest[2605:8105598] Using UIWebView
,2016-04-21 08:01:40.004 ThaliTest[2605:8105598] [CDVTimer][handleopenurl] 0.335991ms
,2016-04-21 08:01:40.010 ThaliTest[2605:8105598] [CDVTimer][intentandnavigationfilter] 5.243957ms
2016-04-21 08:01:40.010 ThaliTest[2605:8105598] [CDVTimer][gesturehandler] 0.296950ms
2016-04-21 08:01:40.011 ThaliTest[2605:8105598] [CDVTimer][TotalPluginStartup] 6.933033ms
,2016-04-21 08:01:48.746 ThaliTest[2605:8105598] Resetting plugins due to page load.
,2016-04-21 08:01:53.284 ThaliTest[2605:8105598] Finished load of: file:///var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/index.html
,2016-04-21 08:01:53.496 ThaliTest[2605:8105598] JXcore Cordova plugin initializing
,2016-04-21 08:01:53.498 ThaliTest[2605:8105784] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-21 08:02:10.550 ThaliTest[2605:8105784] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-21 08:02:10.551 ThaliTest[2605:8105784] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-21 08:02:10.552 ThaliTest[2605:8105784] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-21 08:02:10.555 ThaliTest[2605:8105784] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/39EDB29B-154C-4D08-B8AF-C0ADD41BE02A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-21 08:02:25.783 ThaliTest[2605:8105598] THREAD WARNING: ['JXcore'] took '14522.691895' ms. Plugin should use a background thread.
,2016-04-21 08:02:25.785 ThaliTest[2605:8105734] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
