#### Test 68102130aff19f4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/64C4EFC7-377D-4301-A56C-286E9616525D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/64C4EFC7-377D-4301-A56C-286E9616525D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130aff19f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55018"
,(lldb)     command script import "/tmp/64C4EFC7-377D-4301-A56C-286E9616525D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 17:13:41.329 ThaliTest[2803:9307100] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C12D616F-9E7C-4ACF-851C-CE1A2B785274/Library/Cookies/Cookies.binarycookies
,2016-04-28 17:13:41.902 ThaliTest[2803:9307100] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 17:13:41.903 ThaliTest[2803:9307100] Multi-tasking -> Device: YES, App: YES
,2016-04-28 17:13:41.924 ThaliTest[2803:9307100] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 17:13:44.246 ThaliTest[2803:9307100] Using UIWebView
,2016-04-28 17:13:44.253 ThaliTest[2803:9307100] [CDVTimer][handleopenurl] 0.388980ms
,2016-04-28 17:13:44.258 ThaliTest[2803:9307100] [CDVTimer][intentandnavigationfilter] 5.124986ms
2016-04-28 17:13:44.259 ThaliTest[2803:9307100] [CDVTimer][gesturehandler] 0.252008ms
2016-04-28 17:13:44.259 ThaliTest[2803:9307100] [CDVTimer][TotalPluginS,tartup] 6.812036ms
,2016-04-28 17:13:53.347 ThaliTest[2803:9307100] Resetting plugins due to page load.
,2016-04-28 17:13:57.129 ThaliTest[2803:9307100] Finished load of: file:///var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/index.html
,2016-04-28 17:13:57.342 ThaliTest[2803:9307100] JXcore Cordova plugin initializing
,2016-04-28 17:13:57.344 ThaliTest[2803:9307289] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 17:14:14.491 ThaliTest[2803:9307289] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-28 17:14:14.493 ThaliTest[2803:9307289] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 17:14:14.493 ThaliTest[2803:9307289] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 17:14:14.496 ThaliTest[2803:9307289] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FA505C80-5419-4E0E-98BA-ADBE8999DF93/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 17:14:28.403 ThaliTest[2803:9307100] THREAD WARNING: ['JXcore'] took '13195.186279' ms. Plugin should use a background thread.
,2016-04-28 17:14:28.405 ThaliTest[2803:9307233] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e

```
