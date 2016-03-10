#### Test 6012434713fea37_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/91744504-9A0D-42A7-B0DE-D7B93FE81E6A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/91744504-9A0D-42A7-B0DE-D7B93FE81E6A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50058"
,(lldb)     command script import "/tmp/91744504-9A0D-42A7-B0DE-D7B93FE81E6A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 02:43:07.477 ThaliTest[979:1530601] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7183976-11BE-4AB0-B0F9-FBC0E8E499C5/Library/Cookies/Cookies.binarycookies
,2016-03-10 02:43:07.838 ThaliTest[979:1530601] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 02:43:07.839 ThaliTest[979:1530601] Multi-tasking -> Device: YES, App: YES
,2016-03-10 02:43:07.860 ThaliTest[979:1530601] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 02:43:09.705 ThaliTest[979:1530601] Using UIWebView
,2016-03-10 02:43:09.712 ThaliTest[979:1530601] [CDVTimer][handleopenurl] 0.411034ms
,2016-03-10 02:43:09.720 ThaliTest[979:1530601] [CDVTimer][intentandnavigationfilter] 7.086992ms
2016-03-10 02:43:09.721 ThaliTest[979:1530601] [CDVTimer][gesturehandler] 0.404000ms
2016-03-10 02:43:09.721 ThaliTest[979:1530601] [CDVTimer][TotalPluginStartup] 9.777009ms
,2016-03-10 02:43:17.285 ThaliTest[979:1530601] Resetting plugins due to page load.
,2016-03-10 02:43:20.427 ThaliTest[979:1530601] Finished load of: file:///var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/index.html
,2016-03-10 02:43:20.719 ThaliTest[979:1530601] JXcore Cordova plugin initializing
,2016-03-10 02:43:20.720 ThaliTest[979:1530847] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 02:43:28.119 ThaliTest[979:1530847] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 02:43:28.120 ThaliTest[979:1530847] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 02:43:28.120 ThaliTest[979:1530847] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 02:43:28.123 ThaliTest[979:1530847] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEDECA50-2166-427C-8421-4117CC650FBB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
