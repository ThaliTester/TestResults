#### Test 635253937ae73fc_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D57682BE-A9CE-45DD-B487-C477EFE6BE15/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D57682BE-A9CE-45DD-B487-C477EFE6BE15/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53621"
,(lldb)     command script import "/tmp/D57682BE-A9CE-45DD-B487-C477EFE6BE15/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 08:34:51.171 ThaliTest[1434:3388636] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35B01468-3119-47ED-B197-3EB4B1100B8E/Library/Cookies/Cookies.binarycookies
,2016-03-21 08:34:51.295 ThaliTest[1434:3388636] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 08:34:51.297 ThaliTest[1434:3388636] Multi-tasking -> Device: YES, App: YES
,2016-03-21 08:34:51.319 ThaliTest[1434:3388636] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 08:34:53.439 ThaliTest[1434:3388636] Using UIWebView
,2016-03-21 08:34:53.443 ThaliTest[1434:3388636] [CDVTimer][handleopenurl] 0.374019ms
,2016-03-21 08:34:53.449 ThaliTest[1434:3388636] [CDVTimer][intentandnavigationfilter] 5.191982ms
2016-03-21 08:34:53.450 ThaliTest[1434:3388636] [CDVTimer][gesturehandler] 0.257015ms
2016-03-21 08:34:53.450 ThaliTest[1434:3388636] [CDVTimer][TotalPluginStartup] 6.955028ms
,2016-03-21 08:35:01.808 ThaliTest[1434:3388636] Resetting plugins due to page load.
,2016-03-21 08:35:05.934 ThaliTest[1434:3388636] Finished load of: file:///var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/index.html
,2016-03-21 08:35:06.138 ThaliTest[1434:3388636] JXcore Cordova plugin initializing
2016-03-21 08:35:06.140 ThaliTest[1434:3388805] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 08:35:16.193 ThaliTest[1434:3388805] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 08:35:16.194 ThaliTest[1434:3388805] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 08:35:16.195 ThaliTest[1434:3388805] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 08:35:16.200 ThaliTest[1434:3388805] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A38F67AE-A0F2-4653-91C2-08DB3706F32B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 08:35:36.310 ThaliTest[1434:3388636] THREAD WARNING: ['JXcore'] took '14518.386963' ms. Plugin should use a background thread.
,2016-03-21 08:35:36.311 ThaliTest[1434:3388756] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
