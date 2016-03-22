#### Test 636801181df08af_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/140F4A3D-F076-4336-BB09-320DEF6AB634/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/140F4A3D-F076-4336-BB09-320DEF6AB634/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54585"
,(lldb)     command script import "/tmp/140F4A3D-F076-4336-BB09-320DEF6AB634/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 09:04:51.001 ThaliTest[1502:3551636] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AEECD6D9-A0A3-49AF-832C-3C58B00945D6/Library/Cookies/Cookies.binarycookies
,2016-03-22 09:04:51.121 ThaliTest[1502:3551636] Apache Cordova native platform version 4.0.1 is starting.
2016-03-22 09:04:51.123 ThaliTest[1502:3551636] Multi-tasking -> Device: YES, App: YES
,2016-03-22 09:04:51.140 ThaliTest[1502:3551636] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 09:04:53.422 ThaliTest[1502:3551636] Using UIWebView
,2016-03-22 09:04:53.427 ThaliTest[1502:3551636] [CDVTimer][handleopenurl] 0.315964ms
,2016-03-22 09:04:53.433 ThaliTest[1502:3551636] [CDVTimer][intentandnavigationfilter] 5.153954ms
2016-03-22 09:04:53.433 ThaliTest[1502:3551636] [CDVTimer][gesturehandler] 0.280023ms
2016-03-22 09:04:53.434 ThaliTest[1502:3551636] [CDVTimer][TotalPluginStartup] 6.812990ms
,2016-03-22 09:05:02.799 ThaliTest[1502:3551636] Resetting plugins due to page load.
,2016-03-22 09:05:06.331 ThaliTest[1502:3551636] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/index.html
,2016-03-22 09:05:06.537 ThaliTest[1502:3551636] JXcore Cordova plugin initializing
,2016-03-22 09:05:06.539 ThaliTest[1502:3551822] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 09:05:23.692 ThaliTest[1502:3551822] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:05:23.692 ThaliTest[1502:3551822] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:05:23.693 ThaliTest[1502:3551822] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:05:23.696 ThaliTest[1502:3551822] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D9C8709-109D-4693-AF94-B56E655C2658/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 09:05:37.777 ThaliTest[1502:3551636] THREAD WARNING: ['JXcore'] took '13333.507812' ms. Plugin should use a background thread.
,2016-03-22 09:05:37.778 ThaliTest[1502:3551767] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
