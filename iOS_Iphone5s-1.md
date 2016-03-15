#### Test 62509094c453ee6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c453ee6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8C3DA649-571B-4807-8C98-BD39E23E009C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8C3DA649-571B-4807-8C98-BD39E23E009C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c453ee6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c453ee6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49262"
,(lldb)     command script import "/tmp/8C3DA649-571B-4807-8C98-BD39E23E009C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 10:58:30.148 ThaliTest[1444:2341755] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ACB2A554-27DD-4134-BDF2-6C3219AACB03/Library/Cookies/Cookies.binarycookies
,2016-03-15 10:58:30.604 ThaliTest[1444:2341755] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 10:58:30.607 ThaliTest[1444:2341755] Multi-tasking -> Device: YES, App: YES
,2016-03-15 10:58:30.635 ThaliTest[1444:2341755] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 10:58:32.628 ThaliTest[1444:2341755] Using UIWebView
,2016-03-15 10:58:32.636 ThaliTest[1444:2341755] [CDVTimer][handleopenurl] 0.494957ms
,2016-03-15 10:58:32.645 ThaliTest[1444:2341755] [CDVTimer][intentandnavigationfilter] 8.940995ms
2016-03-15 10:58:32.646 ThaliTest[1444:2341755] [CDVTimer][gesturehandler] 0.423968ms
2016-03-15 10:58:32.647 ThaliTest[1444:2341755] [CDVTimer][TotalPluginS,tartup] 11.682034ms
,2016-03-15 10:58:39.530 ThaliTest[1444:2341755] Resetting plugins due to page load.
,2016-03-15 10:58:43.427 ThaliTest[1444:2341755] Finished load of: file:///var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/index.html
,2016-03-15 10:58:43.690 ThaliTest[1444:2341755] JXcore Cordova plugin initializing
,2016-03-15 10:58:43.692 ThaliTest[1444:2341950] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-15 10:58:48.117 ThaliTest[1444:2341950] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 10:58:48.118 ThaliTest[1444:2341950] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 10:58:48.118 ThaliTest[1444:2341950] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 10:58:48.122 ThaliTest[1444:2341950] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24142A20-5DD9-4153-9CDB-8DD58AA429DF/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-15 10:58:57.691 ThaliTest[1444:2341755] THREAD WARNING: ['JXcore'] took '7326.218994' ms. Plugin should use a background thread.
,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
