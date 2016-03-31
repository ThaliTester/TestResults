#### Test 646138038d447f5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D30D6010-7108-48FC-83E9-5386F95BF46A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D30D6010-7108-48FC-83E9-5386F95BF46A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49577"
,(lldb)     command script import "/tmp/D30D6010-7108-48FC-83E9-5386F95BF46A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 09:41:46.074 ThaliTest[2543:4767328] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3389F621-3B07-4B5F-8C45-0DE260570C7B/Library/Cookies/Cookies.binarycookies
,2016-03-31 09:41:46.467 ThaliTest[2543:4767328] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 09:41:46.469 ThaliTest[2543:4767328] Multi-tasking -> Device: YES, App: YES
,2016-03-31 09:41:46.487 ThaliTest[2543:4767328] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 09:41:48.348 ThaliTest[2543:4767328] Using UIWebView
,2016-03-31 09:41:48.357 ThaliTest[2543:4767328] [CDVTimer][handleopenurl] 0.392020ms
,2016-03-31 09:41:48.364 ThaliTest[2543:4767328] [CDVTimer][intentandnavigationfilter] 6.510019ms
,2016-03-31 09:41:48.365 ThaliTest[2543:4767328] [CDVTimer][gesturehandler] 0.295997ms
,2016-03-31 09:41:48.365 ThaliTest[2543:4767328] [CDVTimer][TotalPluginStartup] 8.776963ms
,2016-03-31 09:41:55.834 ThaliTest[2543:4767328] Resetting plugins due to page load.
,2016-03-31 09:41:59.713 ThaliTest[2543:4767328] Finished load of: file:///var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/index.html
,2016-03-31 09:41:59.945 ThaliTest[2543:4767328] JXcore Cordova plugin initializing
,2016-03-31 09:41:59.946 ThaliTest[2543:4767539] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 09:42:06.384 ThaliTest[2543:4767539] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 09:42:06.384 ThaliTest[2543:4767539] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 09:42:06.385 ThaliTest[2543:4767539] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 09:42:06.386 ThaliTest[2543:4767539] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/467425B3-D895-4BDF-AEAB-0E8A4CB9ED3B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 09:42:11.588 ThaliTest[2543:4767328] THREAD WARNING: ['JXcore'] took '4924.342041' ms. Plugin should use a background thread.

```
