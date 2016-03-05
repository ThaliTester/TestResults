#### Test 616581981d889bb_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B5663D04-14B8-45EA-AF40-C4579F812DA9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B5663D04-14B8-45EA-AF40-C4579F812DA9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50223"
,(lldb)     command script import "/tmp/B5663D04-14B8-45EA-AF40-C4579F812DA9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-05 01:39:47.384 ThaliTest[712:829549] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D33ED1C-8B82-4AD9-90B1-6DDB7A818742/Library/Cookies/Cookies.binarycookies
,2016-03-05 01:39:47.754 ThaliTest[712:829549] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-05 01:39:47.755 ThaliTest[712:829549] Multi-tasking -> Device: YES, App: YES
,2016-03-05 01:39:47.774 ThaliTest[712:829549] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-05 01:39:49.586 ThaliTest[712:829549] Using UIWebView
,2016-03-05 01:39:49.593 ThaliTest[712:829549] [CDVTimer][handleopenurl] 0.423968ms
,2016-03-05 01:39:49.602 ThaliTest[712:829549] [CDVTimer][intentandnavigationfilter] 8.106947ms
2016-03-05 01:39:49.603 ThaliTest[712:829549] [CDVTimer][gesturehandler] 0.386000ms
2016-03-05 01:39:49.603 ThaliTest[712:829549] [CDVTimer][TotalPluginStartup,] 10.803998ms
,2016-03-05 01:39:56.613 ThaliTest[712:829549] Resetting plugins due to page load.
,2016-03-05 01:40:00.692 ThaliTest[712:829549] Finished load of: file:///var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/index.html
,2016-03-05 01:40:00.877 ThaliTest[712:829549] JXcore Cordova plugin initializing
,2016-03-05 01:40:00.878 ThaliTest[712:829805] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-05 01:40:09.534 ThaliTest[712:829805] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-05 01:40:09.534 ThaliTest[712:829805] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-05 01:40:09.534 ThaliTest[712:829805] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-05 01:40:09.538 ThaliTest[712:829805] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9AB20D9-225B-4680-A0BE-53E26C0A1A04/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded


```
