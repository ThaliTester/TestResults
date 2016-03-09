#### Test 6012434764ab483_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A9F321EB-7004-42A6-BBE0-9D7C203C4BF8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A9F321EB-7004-42A6-BBE0-9D7C203C4BF8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49655"
,(lldb)     command script import "/tmp/A9F321EB-7004-42A6-BBE0-9D7C203C4BF8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 02:36:44.785 ThaliTest[918:1386147] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2FF2ABCD-0530-4D95-9CD4-4BD40FDC4850/Library/Cookies/Cookies.binarycookies
,2016-03-09 02:36:45.118 ThaliTest[918:1386147] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-09 02:36:45.119 ThaliTest[918:1386147] Multi-tasking -> Device: YES, App: YES
,2016-03-09 02:36:45.143 ThaliTest[918:1386147] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 02:36:46.989 ThaliTest[918:1386147] Using UIWebView
,2016-03-09 02:36:46.995 ThaliTest[918:1386147] [CDVTimer][handleopenurl] 0.398993ms
,2016-03-09 02:36:47.003 ThaliTest[918:1386147] [CDVTimer][intentandnavigationfilter] 7.197976ms
2016-03-09 02:36:47.004 ThaliTest[918:1386147] [CDVTimer][gesturehandler] 0.332057ms
2016-03-09 02:36:47.004 ThaliTest[918:1386147] [CDVTimer][TotalPluginStartup] 9.656012ms
,2016-03-09 02:36:53.427 ThaliTest[918:1386147] Resetting plugins due to page load.
,2016-03-09 02:36:56.963 ThaliTest[918:1386147] Finished load of: file:///var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/index.html
,2016-03-09 02:36:57.186 ThaliTest[918:1386147] JXcore Cordova plugin initializing
,2016-03-09 02:36:57.187 ThaliTest[918:1386396] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 02:37:04.542 ThaliTest[918:1386396] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-09 02:37:04.543 ThaliTest[918:1386396] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-09 02:37:04.543 ThaliTest[918:1386396] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 02:37:04.546 ThaliTest[918:1386396] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF37A501-E674-4173-86D2-7E3F648A3985/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
