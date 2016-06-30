#### Test 72145431fdae11f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/EA6333F6-01DF-42DA-890A-858020019A06/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EA6333F6-01DF-42DA-890A-858020019A06/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64714"
,(lldb)     command script import "/tmp/EA6333F6-01DF-42DA-890A-858020019A06/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 10:32:52.557 ThaliTest[4464:19673899] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC27EE47-068D-4EE7-BB13-868803FBA829/Library/Cookies/Cookies.binarycookies
,2016-06-30 10:32:52.666 ThaliTest[4464:19673899] Apache Cordova native platform version 4.1.1 is starting.
2016-06-30 10:32:52.667 ThaliTest[4464:19673899] Multi-tasking -> Device: YES, App: YES
,2016-06-30 10:32:52.684 ThaliTest[4464:19673899] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 10:32:54.834 ThaliTest[4464:19673899] Using UIWebView
,2016-06-30 10:32:54.840 ThaliTest[4464:19673899] [CDVTimer][handleopenurl] 0.378966ms
,2016-06-30 10:32:54.845 ThaliTest[4464:19673899] [CDVTimer][intentandnavigationfilter] 5.362034ms
2016-06-30 10:32:54.846 ThaliTest[4464:19673899] [CDVTimer][gesturehandler] 0.266969ms
2016-06-30 10:32:54.846 ThaliTest[4464:19673899] [CDVTimer][TotalPluginStartup] 7.443964ms
,2016-06-30 10:33:03.897 ThaliTest[4464:19673899] Resetting plugins due to page load.
,2016-06-30 10:33:07.430 ThaliTest[4464:19673899] Finished load of: file:///var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/index.html
,2016-06-30 10:33:07.638 ThaliTest[4464:19673899] JXcore Cordova plugin initializing
,2016-06-30 10:33:07.642 ThaliTest[4464:19674093] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 10:33:24.493 ThaliTest[4464:19674093] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 10:33:24.494 ThaliTest[4464:19674093] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 10:33:24.494 ThaliTest[4464:19674093] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 10:33:24.498 ThaliTest[4464:19674093] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C6AA84A7-D639-41DB-9392-24C357C87C2D/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 10:33:38.441 ThaliTest[4464:19673899] THREAD WARNING: ['JXcore'] took '13265.435059' ms. Plugin should use a background thread.
,2016-06-30 10:33:38.443 ThaliTest[4464:19674029] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMo,de

```
