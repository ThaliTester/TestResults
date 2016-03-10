#### Test 61362366b225741_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/6F2E336C-5E54-4A2B-8F55-332A8626A78A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6F2E336C-5E54-4A2B-8F55-332A8626A78A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50611"
,(lldb)     command script import "/tmp/6F2E336C-5E54-4A2B-8F55-332A8626A78A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 11:12:26.144 ThaliTest[1055:1630011] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8961543-BE36-4019-ABCB-D8CADC31AA0C/Library/Cookies/Cookies.binarycookies
,2016-03-10 11:12:26.584 ThaliTest[1055:1630011] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 11:12:26.586 ThaliTest[1055:1630011] Multi-tasking -> Device: YES, App: YES
,2016-03-10 11:12:26.617 ThaliTest[1055:1630011] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 11:12:28.304 ThaliTest[1055:1630011] Using UIWebView
,2016-03-10 11:12:28.311 ThaliTest[1055:1630011] [CDVTimer][handleopenurl] 0.438035ms
,2016-03-10 11:12:28.320 ThaliTest[1055:1630011] [CDVTimer][intentandnavigationfilter] 8.144975ms
2016-03-10 11:12:28.321 ThaliTest[1055:1630011] [CDVTimer][gesturehandler] 0.458002ms
2016-03-10 11:12:28.322 ThaliTest[1055:1630011] [CDVTimer][TotalPluginStartup] 11.137962ms
,2016-03-10 11:12:34.924 ThaliTest[1055:1630011] Resetting plugins due to page load.
,2016-03-10 11:12:37.959 ThaliTest[1055:1630011] Finished load of: file:///var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/index.html
,2016-03-10 11:12:38.202 ThaliTest[1055:1630011] JXcore Cordova plugin initializing
,2016-03-10 11:12:38.204 ThaliTest[1055:1630230] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 11:12:52.053 ThaliTest[1055:1630230] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 11:12:52.054 ThaliTest[1055:1630230] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 11:12:52.054 ThaliTest[1055:1,630230] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 11:12:52.056 ThaliTest[1055:1630230] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5473005-33BB-4003-A4B0-AC103CFDADC3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****
,
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
