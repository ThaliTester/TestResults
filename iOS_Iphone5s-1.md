#### Test 625090943f585e4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090943f585e4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A0A3CF31-D34F-4738-937B-3D887958F085/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A0A3CF31-D34F-4738-937B-3D887958F085/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090943f585e4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090943f585e4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50793"
,(lldb)     command script import "/tmp/A0A3CF31-D34F-4738-937B-3D887958F085/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 17:16:43.896 ThaliTest[1387:2229352] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/358B51BD-D4A5-4726-A610-D9AC0D0EEFE4/Library/Cookies/Cookies.binarycookies
,2016-03-14 17:16:44.343 ThaliTest[1387:2229352] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 17:16:44.345 ThaliTest[1387:2229352] Multi-tasking -> Device: YES, App: YES
,2016-03-14 17:16:44.368 ThaliTest[1387:2229352] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 17:16:46.209 ThaliTest[1387:2229352] Using UIWebView
,2016-03-14 17:16:46.220 ThaliTest[1387:2229352] [CDVTimer][handleopenurl] 0.580013ms
,2016-03-14 17:16:46.229 ThaliTest[1387:2229352] [CDVTimer][intentandnavigationfilter] 8.017004ms
2016-03-14 17:16:46.230 ThaliTest[1387:2229352] [CDVTimer][gesturehandler] 0.433981ms
2016-03-14 17:16:46.230 ThaliTest[1387:2229352] [CDVTimer][TotalPluginS,tartup] 10.927975ms
,2016-03-14 17:16:53.167 ThaliTest[1387:2229352] Resetting plugins due to page load.
,2016-03-14 17:16:57.125 ThaliTest[1387:2229352] Finished load of: file:///var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/index.html
,2016-03-14 17:16:57.361 ThaliTest[1387:2229352] JXcore Cordova plugin initializing
,2016-03-14 17:16:57.363 ThaliTest[1387:2229584] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-14 17:17:01.782 ThaliTest[1387:2229584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 17:17:01.782 ThaliTest[1387:2229584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 17:17:01.782 ThaliTest[1387:2229584] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 17:17:01.786 ThaliTest[1387:2229584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F007EFAF-57F7-4D05-894F-A112CDBB40F7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-14 17:17:11.358 ThaliTest[1387:2229352] THREAD WARNING: ['JXcore'] took '7353.574951' ms. Plugin should use a background thread.
,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
