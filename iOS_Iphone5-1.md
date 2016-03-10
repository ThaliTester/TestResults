#### Test 60124347d1a8dac_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F2DDCDFF-7A83-4DC6-B77F-6E84E81A61BD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F2DDCDFF-7A83-4DC6-B77F-6E84E81A61BD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50817"
,(lldb)     command script import "/tmp/F2DDCDFF-7A83-4DC6-B77F-6E84E81A61BD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 15:19:36.729 ThaliTest[826:1761414] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6DDC0797-36E7-40F3-A7F3-9D22CB2A90A8/Library/Cookies/Cookies.binarycookies
,2016-03-10 15:19:36.840 ThaliTest[826:1761414] Apache Cordova native platform version 4.0.1 is starting.
2016-03-10 15:19:36.842 ThaliTest[826:1761414] Multi-tasking -> Device: YES, App: YES
,2016-03-10 15:19:36.859 ThaliTest[826:1761414] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 15:19:39.019 ThaliTest[826:1761414] Using UIWebView
,2016-03-10 15:19:39.024 ThaliTest[826:1761414] [CDVTimer][handleopenurl] 0.283003ms
,2016-03-10 15:19:39.030 ThaliTest[826:1761414] [CDVTimer][intentandnavigationfilter] 5.274951ms
2016-03-10 15:19:39.030 ThaliTest[826:1761414] [CDVTimer][gesturehandler] 0.278950ms
2016-03-10 15:19:39.031 ThaliTest[826:1761414] [CDVTimer][TotalPluginStartup] 6.875992ms
,2016-03-10 15:19:47.309 ThaliTest[826:1761414] Resetting plugins due to page load.
,2016-03-10 15:19:51.204 ThaliTest[826:1761414] Finished load of: file:///var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/index.html
,2016-03-10 15:19:51.409 ThaliTest[826:1761414] JXcore Cordova plugin initializing
,2016-03-10 15:19:51.411 ThaliTest[826:1761609] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 15:20:08.325 ThaliTest[826:1761609] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 15:20:08.326 ThaliTest[826:1761609] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-10 15:20:08.326 ThaliTest[826:1761609] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 15:20:08.332 ThaliTest[826:1761609] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/463B79AE-71BD-4106-88BF-E215C4998382/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
