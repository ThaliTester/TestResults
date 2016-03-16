#### Test 63012666c2ddc84_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A2904E00-EFB6-42C9-9110-2CB724FD6D45/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A2904E00-EFB6-42C9-9110-2CB724FD6D45/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50099"
,(lldb)     command script import "/tmp/A2904E00-EFB6-42C9-9110-2CB724FD6D45/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 06:28:53.610 ThaliTest[1533:2469211] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DDD8769A-5C39-4819-BA0B-2B3A5AFC0494/Library/Cookies/Cookies.binarycookies
,2016-03-16 06:28:54.070 ThaliTest[1533:2469211] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 06:28:54.072 ThaliTest[1533:2469211] Multi-tasking -> Device: YES, App: YES
,2016-03-16 06:28:54.098 ThaliTest[1533:2469211] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 06:28:55.899 ThaliTest[1533:2469211] Using UIWebView
,2016-03-16 06:28:55.907 ThaliTest[1533:2469211] [CDVTimer][handleopenurl] 0.427008ms
,2016-03-16 06:28:55.916 ThaliTest[1533:2469211] [CDVTimer][intentandnavigationfilter] 8.000016ms
2016-03-16 06:28:55.917 ThaliTest[1533:2469211] [CDVTimer][gesturehandler] 0.384986ms
2016-03-16 06:28:55.917 ThaliTest[1533:2469211] [CDVTimer][TotalPluginS,tartup] 10.701954ms
,2016-03-16 06:29:03.428 ThaliTest[1533:2469211] Resetting plugins due to page load.
,2016-03-16 06:29:07.365 ThaliTest[1533:2469211] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/index.html
,2016-03-16 06:29:07.603 ThaliTest[1533:2469211] JXcore Cordova plugin initializing
,2016-03-16 06:29:07.604 ThaliTest[1533:2469412] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-16 06:29:12.017 ThaliTest[1533:2469412] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 06:29:12.018 ThaliTest[1533:2469412] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 06:29:12.018 ThaliTest[1533:2469412] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-16 06:29:12.022 ThaliTest[1533:2469412] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE7AF608-1731-48B9-82E5-1A697D8E16F1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-16 06:29:21.484 ThaliTest[1533:2469211] THREAD WARNING: ['JXcore'] took '7234.481201' ms. Plugin should use a background thread.
,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
