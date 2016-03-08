#### Test 60124347d4f5b03_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6F136E68-B6B4-40EA-A310-A1766BBC8A12/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6F136E68-B6B4-40EA-A310-A1766BBC8A12/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51888"
,(lldb)     command script import "/tmp/6F136E68-B6B4-40EA-A310-A1766BBC8A12/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 02:11:20.310 ThaliTest[850:1240596] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8D3C99F-BA98-496F-B114-3BF6CE393B15/Library/Cookies/Cookies.binarycookies
,2016-03-08 02:11:20.690 ThaliTest[850:1240596] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-08 02:11:20.691 ThaliTest[850:1240596] Multi-tasking -> Device: YES, App: YES
,2016-03-08 02:11:20.714 ThaliTest[850:1240596] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 02:11:22.627 ThaliTest[850:1240596] Using UIWebView
,2016-03-08 02:11:22.633 ThaliTest[850:1240596] [CDVTimer][handleopenurl] 0.388980ms
,2016-03-08 02:11:22.641 ThaliTest[850:1240596] [CDVTimer][intentandnavigationfilter] 7.393003ms
2016-03-08 02:11:22.642 ThaliTest[850:1240596] [CDVTimer][gesturehandler] 0.332952ms
2016-03-08 02:11:22.642 ThaliTest[850:1240596] [CDVTimer][TotalPluginStartup] 9.663999ms
,2016-03-08 02:11:30.217 ThaliTest[850:1240596] Resetting plugins due to page load.
,2016-03-08 02:11:33.813 ThaliTest[850:1240596] Finished load of: file:///var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/index.html
,2016-03-08 02:11:34.048 ThaliTest[850:1240596] JXcore Cordova plugin initializing
,2016-03-08 02:11:34.050 ThaliTest[850:1240817] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-08 02:11:41.423 ThaliTest[850:1240817] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-08 02:11:41.423 ThaliTest[850:1240817] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-08 02:11:41.424 ThaliTest[850:1240817] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-08 02:11:41.426 ThaliTest[850:1240817] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C001705-01F6-4AB7-B899-331213CFCD8A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
