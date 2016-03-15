#### Test 62509094058a2d4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4088BB4B-25FD-45D9-A4B1-878CB31FFC43/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4088BB4B-25FD-45D9-A4B1-878CB31FFC43/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49594"
,(lldb)     command script import "/tmp/4088BB4B-25FD-45D9-A4B1-878CB31FFC43/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 13:15:47.059 ThaliTest[1470:2359932] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F27209CE-C3A5-4849-B041-B684A32C4E5D/Library/Cookies/Cookies.binarycookies
,2016-03-15 13:15:47.518 ThaliTest[1470:2359932] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 13:15:47.520 ThaliTest[1470:2359932] Multi-tasking -> Device: YES, App: YES
,2016-03-15 13:15:47.545 ThaliTest[1470:2359932] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 13:15:49.413 ThaliTest[1470:2359932] Using UIWebView
,2016-03-15 13:15:49.423 ThaliTest[1470:2359932] [CDVTimer][handleopenurl] 0.571012ms
,2016-03-15 13:15:49.432 ThaliTest[1470:2359932] [CDVTimer][intentandnavigationfilter] 8.032978ms
2016-03-15 13:15:49.433 ThaliTest[1470:2359932] [CDVTimer][gesturehandler] 0.387967ms
2016-03-15 13:15:49.433 ThaliTest[1470:2359932] [CDVTimer][TotalPluginS,tartup] 10.895014ms
,2016-03-15 13:15:56.543 ThaliTest[1470:2359932] Resetting plugins due to page load.
,2016-03-15 13:16:00.596 ThaliTest[1470:2359932] Finished load of: file:///var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/index.html
,2016-03-15 13:16:00.781 ThaliTest[1470:2359932] JXcore Cordova plugin initializing
,2016-03-15 13:16:00.783 ThaliTest[1470:2360189] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-15 13:16:05.206 ThaliTest[1470:2360189] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 13:16:05.207 ThaliTest[1470:2360189] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 13:16:05.207 ThaliTest[1470:2360189] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 13:16:05.211 ThaliTest[1470:2360189] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/14975409-6855-472C-900F-C97AF915323C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-15 13:16:14.762 ThaliTest[1470:2359932] THREAD WARNING: ['JXcore'] took '7316.712158' ms. Plugin should use a background thread.
,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
