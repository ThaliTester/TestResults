#### Test 6216742584ac8ae_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/055279C8-376C-4E50-A188-5D804D67CED5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/055279C8-376C-4E50-A188-5D804D67CED5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6216742584ac8ae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49777"
,(lldb)     command script import "/tmp/055279C8-376C-4E50-A188-5D804D67CED5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 03:03:51.626 ThaliTest[956:1428367] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/384A74E5-A1E9-4868-A3DD-DDDD6D5D1BE2/Library/Cookies/Cookies.binarycookies
,2016-03-09 03:03:51.989 ThaliTest[956:1428367] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-09 03:03:51.990 ThaliTest[956:1428367] Multi-tasking -> Device: YES, App: YES
,2016-03-09 03:03:52.013 ThaliTest[956:1428367] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 03:03:53.788 ThaliTest[956:1428367] Using UIWebView
,2016-03-09 03:03:53.795 ThaliTest[956:1428367] [CDVTimer][handleopenurl] 0.441015ms
,2016-03-09 03:03:53.804 ThaliTest[956:1428367] [CDVTimer][intentandnavigationfilter] 8.249998ms
2016-03-09 03:03:53.805 ThaliTest[956:1428367] [CDVTimer][gesturehandler] 0.427008ms
2016-03-09 03:03:53.805 ThaliTest[956:1428367] [CDVTimer][TotalPluginStar,tup] 11.057019ms
,2016-03-09 03:04:00.867 ThaliTest[956:1428367] Resetting plugins due to page load.
,2016-03-09 03:04:04.521 ThaliTest[956:1428367] Finished load of: file:///var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/index.html
,2016-03-09 03:04:04.756 ThaliTest[956:1428367] JXcore Cordova plugin initializing
2016-03-09 03:04:04.758 ThaliTest[956:1428591] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 03:04:13.482 ThaliTest[956:1428591] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-09 03:04:13.483 ThaliTest[956:1428591] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-09 03:04:13.483 ThaliTest[956:1428591] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 03:04:13.487 ThaliTest[956:1428591] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60DBA736-DDE5-430F-817D-136AD3B83460/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
