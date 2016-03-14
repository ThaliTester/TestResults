#### Test 625090944a5472b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D7FD9012-1759-4CF6-B8DE-E83B186E5C29/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D7FD9012-1759-4CF6-B8DE-E83B186E5C29/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50152"
,(lldb)     command script import "/tmp/D7FD9012-1759-4CF6-B8DE-E83B186E5C29/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 08:49:44.730 ThaliTest[1335:2172712] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0DB49C44-F8BC-4BF6-9E60-8AEFD264E3D2/Library/Cookies/Cookies.binarycookies
,2016-03-14 08:49:45.114 ThaliTest[1335:2172712] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 08:49:45.115 ThaliTest[1335:2172712] Multi-tasking -> Device: YES, App: YES
,2016-03-14 08:49:45.137 ThaliTest[1335:2172712] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 08:49:46.825 ThaliTest[1335:2172712] Using UIWebView
,2016-03-14 08:49:46.835 ThaliTest[1335:2172712] [CDVTimer][handleopenurl] 0.449002ms
,2016-03-14 08:49:46.844 ThaliTest[1335:2172712] [CDVTimer][intentandnavigationfilter] 8.202016ms
2016-03-14 08:49:46.845 ThaliTest[1335:2172712] [CDVTimer][gesturehandler] 0.414014ms
2016-03-14 08:49:46.845 ThaliTest[1335:2172712] [CDVTimer][TotalPluginS,tartup] 10.926008ms
,2016-03-14 08:49:53.353 ThaliTest[1335:2172712] Resetting plugins due to page load.
,2016-03-14 08:49:56.854 ThaliTest[1335:2172712] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/index.html
,2016-03-14 08:49:57.105 ThaliTest[1335:2172712] JXcore Cordova plugin initializing
,2016-03-14 08:49:57.106 ThaliTest[1335:2172894] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 08:50:10.997 ThaliTest[1335:2172894] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 08:50:10.998 ThaliTest[1335:2172894] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 08:50:10.998 ThaliTest[1335:2,172894] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

2016-03-14 08:50:10.999 ThaliTest[1335:2172894] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5778348-5FE9-492F-BAA6-4C645E98722E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
