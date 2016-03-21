#### Test 62548124bd1cdb6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4EF3F584-80C5-4599-A73A-160FD2FCF9DC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4EF3F584-80C5-4599-A73A-160FD2FCF9DC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53514"
,(lldb)     command script import "/tmp/4EF3F584-80C5-4599-A73A-160FD2FCF9DC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-21 07:31:06.207 ThaliTest[1427:3380766] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/424B7F7D-2E3A-4579-A7AD-80D81D6FDDE6/Library/Cookies/Cookies.binarycookies
,2016-03-21 07:31:06.714 ThaliTest[1427:3380766] Apache Cordova native platform version 4.0.1 is starting.
2016-03-21 07:31:06.715 ThaliTest[1427:3380766] Multi-tasking -> Device: YES, App: YES
,2016-03-21 07:31:06.736 ThaliTest[1427:3380766] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 07:31:08.780 ThaliTest[1427:3380766] Using UIWebView
,2016-03-21 07:31:08.785 ThaliTest[1427:3380766] [CDVTimer][handleopenurl] 0.297010ms
,2016-03-21 07:31:08.791 ThaliTest[1427:3380766] [CDVTimer][intentandnavigationfilter] 5.446017ms
2016-03-21 07:31:08.791 ThaliTest[1427:3380766] [CDVTimer][gesturehandler] 0.256956ms
2016-03-21 07:31:08.791 ThaliTest[1427:3380766] [CDVTimer][TotalPluginStartup] 7.041991ms
,2016-03-21 07:31:16.284 ThaliTest[1427:3380766] Resetting plugins due to page load.
,2016-03-21 07:31:19.544 ThaliTest[1427:3380766] Finished load of: file:///var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/index.html
,2016-03-21 07:31:19.750 ThaliTest[1427:3380766] JXcore Cordova plugin initializing
,2016-03-21 07:31:19.753 ThaliTest[1427:3381135] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 07:31:36.293 ThaliTest[1427:3381135] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 07:31:36.294 ThaliTest[1427:3381135] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:31:36.294 ThaliTest[1427:3,381135] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:31:36.297 ThaliTest[1427:3381135] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DC259EA4-9F1D-421D-A71E-1229E30432CA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 07:31:49.837 ThaliTest[1427:3380766] THREAD WARNING: ['JXcore'] took '12851.626221' ms. Plugin should use a background thread.
,2016-03-21 07:31:49.838 ThaliTest[1427:3380895] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
