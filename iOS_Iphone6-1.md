#### Test 62548124e8057a0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A01CE9E1-E283-47F2-AD2C-F9D70DC74D50/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A01CE9E1-E283-47F2-AD2C-F9D70DC74D50/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54264"
,(lldb)     command script import "/tmp/A01CE9E1-E283-47F2-AD2C-F9D70DC74D50/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 14:20:50.070 ThaliTest[1886:3195605] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B2A06133-1AB8-439D-B474-DB33A42E90A0/Library/Cookies/Cookies.binarycookies
,2016-03-21 14:20:50.462 ThaliTest[1886:3195605] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 14:20:50.463 ThaliTest[1886:3195605] Multi-tasking -> Device: YES, App: YES
,2016-03-21 14:20:50.491 ThaliTest[1886:3195605] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 14:20:52.439 ThaliTest[1886:3195605] Using UIWebView
,2016-03-21 14:20:52.449 ThaliTest[1886:3195605] [CDVTimer][handleopenurl] 0.522017ms
,2016-03-21 14:20:52.457 ThaliTest[1886:3195605] [CDVTimer][intentandnavigationfilter] 7.201016ms
2016-03-21 14:20:52.458 ThaliTest[1886:3195605] [CDVTimer][gesturehandler] 0.329971ms
2016-03-21 14:20:52.458 ThaliTest[1886:3195605] [CDVTimer][TotalPluginS,tartup] 9.688020ms
,2016-03-21 14:20:59.546 ThaliTest[1886:3195605] Resetting plugins due to page load.
,2016-03-21 14:21:03.145 ThaliTest[1886:3195605] Finished load of: file:///var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/index.html
,2016-03-21 14:21:03.305 ThaliTest[1886:3195605] JXcore Cordova plugin initializing
,2016-03-21 14:21:03.306 ThaliTest[1886:3195829] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 14:21:10.596 ThaliTest[1886:3195829] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 14:21:10.597 ThaliTest[1886:3195829] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 14:21:10.597 ThaliTest[1886:3195829] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 14:21:10.599 ThaliTest[1886:3195829] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8854F25-0023-40B6-AA22-F2CE837D7D1A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 14:21:16.476 ThaliTest[1886:3195605] THREAD WARNING: ['JXcore'] took '5562.167236' ms. Plugin should use a background thread.

```
