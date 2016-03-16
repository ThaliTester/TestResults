#### Test 62509094c147163_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F2D0C1E2-9653-48F3-85E7-DC1D1149E481/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F2D0C1E2-9653-48F3-85E7-DC1D1149E481/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50226"
,(lldb)     command script import "/tmp/F2D0C1E2-9653-48F3-85E7-DC1D1149E481/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 08:33:58.808 ThaliTest[1499:2414566] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF343BEE-769A-4AA1-8AEC-D159E4E68B7E/Library/Cookies/Cookies.binarycookies
,2016-03-16 08:33:59.200 ThaliTest[1499:2414566] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 08:33:59.202 ThaliTest[1499:2414566] Multi-tasking -> Device: YES, App: YES
,2016-03-16 08:33:59.231 ThaliTest[1499:2414566] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 08:34:01.082 ThaliTest[1499:2414566] Using UIWebView
,2016-03-16 08:34:01.089 ThaliTest[1499:2414566] [CDVTimer][handleopenurl] 0.398993ms
,2016-03-16 08:34:01.097 ThaliTest[1499:2414566] [CDVTimer][intentandnavigationfilter] 7.390976ms
2016-03-16 08:34:01.098 ThaliTest[1499:2414566] [CDVTimer][gesturehandler] 0.374973ms
2016-03-16 08:34:01.098 ThaliTest[1499:2414566] [CDVTimer][TotalPluginStartup] 9.877026ms
,2016-03-16 08:34:08.073 ThaliTest[1499:2414566] Resetting plugins due to page load.
,2016-03-16 08:34:11.663 ThaliTest[1499:2414566] Finished load of: file:///var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/index.html
,2016-03-16 08:34:11.872 ThaliTest[1499:2414566] JXcore Cordova plugin initializing
,2016-03-16 08:34:11.873 ThaliTest[1499:2414772] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 08:34:15.659 ThaliTest[1499:2414772] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 08:34:15.659 ThaliTest[1499:2414772] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 08:34:15.659 ThaliTest[1499:2,414772] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 08:34:15.662 ThaliTest[1499:2414772] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71E24C12-5B49-4E23-BACC-7A6E1394124F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 08:34:23.817 ThaliTest[1499:2414566] THREAD WARNING: ['JXcore'] took '6245.604980' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
