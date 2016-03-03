#### Test 6136236661fd38c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/41B4070D-B58C-4024-BAE5-7FC3139A7342/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/41B4070D-B58C-4024-BAE5-7FC3139A7342/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51308"
,(lldb)     command script import "/tmp/41B4070D-B58C-4024-BAE5-7FC3139A7342/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-03 14:57:17.216 ThaliTest[566:669528] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5F0C2DB2-7AE7-4095-882C-68E23D393545/Library/Cookies/Cookies.binarycookies
,2016-03-03 14:57:17.591 ThaliTest[566:669528] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-03 14:57:17.592 ThaliTest[566:669528] Multi-tasking -> Device: YES, App: YES
,2016-03-03 14:57:17.617 ThaliTest[566:669528] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-03 14:57:19.330 ThaliTest[566:669528] Using UIWebView
,2016-03-03 14:57:19.338 ThaliTest[566:669528] [CDVTimer][handleopenurl] 0.432014ms
,2016-03-03 14:57:19.347 ThaliTest[566:669528] [CDVTimer][intentandnavigationfilter] 8.111000ms
2016-03-03 14:57:19.348 ThaliTest[566:669528] [CDVTimer][gesturehandler] 0.425994ms
2016-03-03 14:57:19.348 ThaliTest[566:669528] [CDVTimer][TotalPluginStartup,] 10.802031ms
,2016-03-03 14:57:25.789 ThaliTest[566:669528] Resetting plugins due to page load.
,2016-03-03 14:57:28.641 ThaliTest[566:669528] Finished load of: file:///var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/index.html
,2016-03-03 14:57:28.882 ThaliTest[566:669528] JXcore Cordova plugin initializing
,2016-03-03 14:57:28.883 ThaliTest[566:669732] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-03 14:57:42.783 ThaliTest[566:669732] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-03 14:57:42.784 ThaliTest[566:669732] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-03 14:57:42.784 ThaliTest[566:669732] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-03 14:57:42.785 ThaliTest[566:669732] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D9710C4-F21E-4FD1-8B80-C2D6114EA1C1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
