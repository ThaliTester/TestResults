#### Test 623288225dc9f88_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1C2108E1-E8D4-4E57-B12E-2B4779FC565F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1C2108E1-E8D4-4E57-B12E-2B4779FC565F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50206"
,(lldb)     command script import "/tmp/1C2108E1-E8D4-4E57-B12E-2B4779FC565F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 03:32:37.389 ThaliTest[988:1536283] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/639450E2-9CCF-4174-B36D-13AB178EB2EB/Library/Cookies/Cookies.binarycookies
,2016-03-10 03:32:37.780 ThaliTest[988:1536283] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 03:32:37.782 ThaliTest[988:1536283] Multi-tasking -> Device: YES, App: YES
,2016-03-10 03:32:37.810 ThaliTest[988:1536283] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 03:32:39.701 ThaliTest[988:1536283] Using UIWebView
,2016-03-10 03:32:39.707 ThaliTest[988:1536283] [CDVTimer][handleopenurl] 0.382960ms
,2016-03-10 03:32:39.715 ThaliTest[988:1536283] [CDVTimer][intentandnavigationfilter] 7.291019ms
2016-03-10 03:32:39.716 ThaliTest[988:1536283] [CDVTimer][gesturehandler] 0.352979ms
2016-03-10 03:32:39.716 ThaliTest[988:1536283] [CDVTimer][TotalPluginStartup] 9.631991ms
,2016-03-10 03:32:46.820 ThaliTest[988:1536283] Resetting plugins due to page load.
,2016-03-10 03:32:50.173 ThaliTest[988:1536283] Finished load of: file:///var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/index.html
,2016-03-10 03:32:50.397 ThaliTest[988:1536283] JXcore Cordova plugin initializing
,2016-03-10 03:32:50.398 ThaliTest[988:1536514] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 03:32:57.928 ThaliTest[988:1536514] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 03:32:57.928 ThaliTest[988:1536514] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 03:32:57.929 ThaliTest[988:1536514] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 03:32:57.931 ThaliTest[988:1536514] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/917BB6AB-D6FC-40AB-B72A-594D656F75B7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
