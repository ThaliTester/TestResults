#### Test 62548124b8ccb9f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7B882D28-0A3A-4838-A679-343DFAD76A0B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7B882D28-0A3A-4838-A679-343DFAD76A0B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52736"
,(lldb)     command script import "/tmp/7B882D28-0A3A-4838-A679-343DFAD76A0B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-18 17:14:19.654 ThaliTest[1323:2982628] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EC9C72DE-A056-4158-8DD7-7B59474C405F/Library/Cookies/Cookies.binarycookies
,2016-03-18 17:14:20.156 ThaliTest[1323:2982628] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-18 17:14:20.157 ThaliTest[1323:2982628] Multi-tasking -> Device: YES, App: YES
,2016-03-18 17:14:20.177 ThaliTest[1323:2982628] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-18 17:14:22.264 ThaliTest[1323:2982628] Using UIWebView
,2016-03-18 17:14:22.269 ThaliTest[1323:2982628] [CDVTimer][handleopenurl] 0.423014ms
,2016-03-18 17:14:22.274 ThaliTest[1323:2982628] [CDVTimer][intentandnavigationfilter] 5.180001ms
2016-03-18 17:14:22.275 ThaliTest[1323:2982628] [CDVTimer][gesturehandler] 0.257015ms
2016-03-18 17:14:22.275 ThaliTest[1323:2982628] [CDVTimer][TotalPluginS,tartup] 6.940961ms
,2016-03-18 17:14:30.904 ThaliTest[1323:2982628] Resetting plugins due to page load.
,2016-03-18 17:14:34.786 ThaliTest[1323:2982628] Finished load of: file:///var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/index.html
,2016-03-18 17:14:34.990 ThaliTest[1323:2982628] JXcore Cordova plugin initializing
,2016-03-18 17:14:34.992 ThaliTest[1323:2982831] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-18 17:14:52.187 ThaliTest[1323:2982831] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:14:52.188 ThaliTest[1323:2982831] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:14:52.188 ThaliTest[1323:2,982831] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:14:52.192 ThaliTest[1323:2982831] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B486DDBD-9AEF-4C62-B1FE-A4BAFB1AE36A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-18 17:15:06.222 ThaliTest[1323:2982628] THREAD WARNING: ['JXcore'] took '13304.947998' ms. Plugin should use a background thread.
,2016-03-18 17:15:06.224 ThaliTest[1323:2982768] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
