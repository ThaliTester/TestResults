#### Test 63008475d624ed8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63008475d624ed8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/34A71134-524A-48C0-9249-A98C380475D1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/34A71134-524A-48C0-9249-A98C380475D1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63008475d624ed8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63008475d624ed8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50565"
,(lldb)     command script import "/tmp/34A71134-524A-48C0-9249-A98C380475D1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 12:20:06.347 ThaliTest[1569:2509756] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA699258-C6D4-4E16-8AF9-CFF875FBA27A/Library/Cookies/Cookies.binarycookies
,2016-03-16 12:20:06.744 ThaliTest[1569:2509756] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 12:20:06.745 ThaliTest[1569:2509756] Multi-tasking -> Device: YES, App: YES
,2016-03-16 12:20:06.768 ThaliTest[1569:2509756] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 12:20:08.746 ThaliTest[1569:2509756] Using UIWebView
,2016-03-16 12:20:08.756 ThaliTest[1569:2509756] [CDVTimer][handleopenurl] 0.488043ms
,2016-03-16 12:20:08.765 ThaliTest[1569:2509756] [CDVTimer][intentandnavigationfilter] 8.081973ms
2016-03-16 12:20:08.766 ThaliTest[1569:2509756] [CDVTimer][gesturehandler] 0.386000ms
2016-03-16 12:20:08.766 ThaliTest[1569:2509756] [CDVTimer][TotalPluginStartup] 10.990977ms
,2016-03-16 12:20:16.185 ThaliTest[1569:2509756] Resetting plugins due to page load.
,2016-03-16 12:20:20.242 ThaliTest[1569:2509756] Finished load of: file:///var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/index.html
,2016-03-16 12:20:20.493 ThaliTest[1569:2509756] JXcore Cordova plugin initializing
,2016-03-16 12:20:20.494 ThaliTest[1569:2510000] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-16 12:20:35.882 ThaliTest[1569:2510000] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 12:20:35.883 ThaliTest[1569:2510000] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 12:20:35.883 ThaliTest[1569:2,510000] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-16 12:20:35.884 ThaliTest[1569:2510000] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E7D2BF47-D753-45BE-861B-F462126712A9/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
