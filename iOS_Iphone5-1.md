#### Test 721454317367600_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/721454317367600/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/442317B0-CC7E-41A1-9CF4-FEAC50335DA1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/442317B0-CC7E-41A1-9CF4-FEAC50335DA1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/721454317367600/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/721454317367600/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62128"
,(lldb)     command script import "/tmp/442317B0-CC7E-41A1-9CF4-FEAC50335DA1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-22 07:41:09.841 ThaliTest[4244:18290710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3B92F99F-FA2F-4B4C-ADFE-A73DDE84B9F2/Library/Cookies/Cookies.binarycookies
,2016-06-22 07:41:10.374 ThaliTest[4244:18290710] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-22 07:41:10.376 ThaliTest[4244:18290710] Multi-tasking -> Device: YES, App: YES
,2016-06-22 07:41:10.397 ThaliTest[4244:18290710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-22 07:41:12.601 ThaliTest[4244:18290710] Using UIWebView
,2016-06-22 07:41:12.606 ThaliTest[4244:18290710] [CDVTimer][handleopenurl] 0.337005ms
,2016-06-22 07:41:12.612 ThaliTest[4244:18290710] [CDVTimer][intentandnavigationfilter] 5.075991ms
2016-06-22 07:41:12.613 ThaliTest[4244:18290710] [CDVTimer][gesturehandler] 0.256002ms
2016-06-22 07:41:12.613 ThaliTest[4244:18290710] [CDVTimer][TotalPluginStartup] 6.958008ms
,2016-06-22 07:41:21.025 ThaliTest[4244:18290710] Resetting plugins due to page load.
,2016-06-22 07:41:24.608 ThaliTest[4244:18290710] Finished load of: file:///var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/index.html
,2016-06-22 07:41:24.811 ThaliTest[4244:18290710] JXcore Cordova plugin initializing
,2016-06-22 07:41:24.813 ThaliTest[4244:18290885] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-22 07:41:41.905 ThaliTest[4244:18290885] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-06-22 07:41:41.906 ThaliTest[4244:18290885] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-22 07:41:41.907 ThaliTest[4244:18290885] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-22 07:41:41.910 ThaliTest[4244:18290885] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48F8E69E-65E0-4703-9699-C7589D6F82BA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-22 07:41:56.002 ThaliTest[4244:18290710] THREAD WARNING: ['JXcore'] took '13393.078125' ms. Plugin should use a background thread.
,2016-06-22 07:41:56.004 ThaliTest[4244:18290833] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
