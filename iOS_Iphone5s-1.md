#### Test 60124347e678b8e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8D1547D6-793B-49C1-8BCE-7D603B4ED938/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8D1547D6-793B-49C1-8BCE-7D603B4ED938/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51120"
,(lldb)     command script import "/tmp/8D1547D6-793B-49C1-8BCE-7D603B4ED938/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 19:27:02.191 ThaliTest[1100:1684761] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3ED5328A-E431-4B5E-A8BC-4A7DC0A5C86D/Library/Cookies/Cookies.binarycookies
,2016-03-10 19:27:02.595 ThaliTest[1100:1684761] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 19:27:02.596 ThaliTest[1100:1684761] Multi-tasking -> Device: YES, App: YES
,2016-03-10 19:27:02.621 ThaliTest[1100:1684761] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 19:27:04.603 ThaliTest[1100:1684761] Using UIWebView
,2016-03-10 19:27:04.610 ThaliTest[1100:1684761] [CDVTimer][handleopenurl] 0.442028ms
,2016-03-10 19:27:04.619 ThaliTest[1100:1684761] [CDVTimer][intentandnavigationfilter] 8.144975ms
2016-03-10 19:27:04.620 ThaliTest[1100:1684761] [CDVTimer][gesturehandler] 0.386000ms
2016-03-10 19:27:04.620 ThaliTest[1100:1684761] [CDVTimer][TotalPluginS,tartup] 10.918021ms
,2016-03-10 19:27:11.328 ThaliTest[1100:1684761] Resetting plugins due to page load.
,2016-03-10 19:27:14.897 ThaliTest[1100:1684761] Finished load of: file:///var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/index.html
,2016-03-10 19:27:15.149 ThaliTest[1100:1684761] JXcore Cordova plugin initializing
2016-03-10 19:27:15.150 ThaliTest[1100:1684993] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 19:27:23.908 ThaliTest[1100:1684993] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 19:27:23.909 ThaliTest[1100:1684993] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 19:27:23.909 ThaliTest[1100:1,684993] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 19:27:23.913 ThaliTest[1100:1684993] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5419A9BE-E9D3-4368-945B-9D79562E25E8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
