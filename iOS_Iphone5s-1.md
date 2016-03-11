#### Test 625090942f85e77_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FE0C87E4-CAD6-4C2D-8DEC-33D8A74D75A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FE0C87E4-CAD6-4C2D-8DEC-33D8A74D75A0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49585"
,(lldb)     command script import "/tmp/FE0C87E4-CAD6-4C2D-8DEC-33D8A74D75A0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-11 16:58:09.087 ThaliTest[1196:1784599] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA30F907-D483-4B57-88A8-052393C0F722/Library/Cookies/Cookies.binarycookies
,2016-03-11 16:58:09.455 ThaliTest[1196:1784599] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 16:58:09.457 ThaliTest[1196:1784599] Multi-tasking -> Device: YES, App: YES
,2016-03-11 16:58:09.479 ThaliTest[1196:1784599] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 16:58:11.178 ThaliTest[1196:1784599] Using UIWebView
,2016-03-11 16:58:11.186 ThaliTest[1196:1784599] [CDVTimer][handleopenurl] 0.442028ms
,2016-03-11 16:58:11.195 ThaliTest[1196:1784599] [CDVTimer][intentandnavigationfilter] 8.763015ms
2016-03-11 16:58:11.196 ThaliTest[1196:1784599] [CDVTimer][gesturehandler] 0.436008ms
2016-03-11 16:58:11.197 ThaliTest[1196:1784599] [CDVTimer][TotalPluginStartup] 11.727989ms
,2016-03-11 16:58:17.395 ThaliTest[1196:1784599] Resetting plugins due to page load.
,2016-03-11 16:58:20.651 ThaliTest[1196:1784599] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/index.html
,2016-03-11 16:58:20.893 ThaliTest[1196:1784599] JXcore Cordova plugin initializing
,2016-03-11 16:58:20.894 ThaliTest[1196:1784786] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 16:58:34.782 ThaliTest[1196:1784786] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 16:58:34.783 ThaliTest[1196:1784786] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 16:58:34.783 ThaliTest[1196:1784786] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 16:58:34.784 ThaliTest[1196:1784786] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CCB4FD3-BAEC-49BA-8453-B156ABBCA588/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
