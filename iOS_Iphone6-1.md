#### Test 62560673a3c76e9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8C12DF09-37EA-469E-8124-6F645F945E8A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8C12DF09-37EA-469E-8124-6F645F945E8A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50396"
,(lldb)     command script import "/tmp/8C12DF09-37EA-469E-8124-6F645F945E8A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 12:14:52.202 ThaliTest[1310:2138156] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EDB8948D-058E-4F50-930A-B844C2B273DD/Library/Cookies/Cookies.binarycookies
,2016-03-14 12:14:52.576 ThaliTest[1310:2138156] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 12:14:52.578 ThaliTest[1310:2138156] Multi-tasking -> Device: YES, App: YES
,2016-03-14 12:14:52.601 ThaliTest[1310:2138156] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 12:14:54.468 ThaliTest[1310:2138156] Using UIWebView
,2016-03-14 12:14:54.475 ThaliTest[1310:2138156] [CDVTimer][handleopenurl] 0.531018ms
,2016-03-14 12:14:54.483 ThaliTest[1310:2138156] [CDVTimer][intentandnavigationfilter] 7.168949ms
2016-03-14 12:14:54.484 ThaliTest[1310:2138156] [CDVTimer][gesturehandler] 0.401974ms
2016-03-14 12:14:54.484 ThaliTest[1310:2138156] [CDVTimer][TotalPluginStartup] 9.810030ms
,2016-03-14 12:15:01.520 ThaliTest[1310:2138156] Resetting plugins due to page load.
,2016-03-14 12:15:04.973 ThaliTest[1310:2138156] Finished load of: file:///var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/index.html
,2016-03-14 12:15:05.202 ThaliTest[1310:2138156] JXcore Cordova plugin initializing
,2016-03-14 12:15:05.204 ThaliTest[1310:2138354] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 12:15:17.676 ThaliTest[1310:2138354] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 12:15:17.676 ThaliTest[1310:2138354] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 12:15:17.676 ThaliTest[1310:2,138354] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 12:15:17.677 ThaliTest[1310:2138354] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E4E2630-9B62-4148-B0A0-59C8BE57826D/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
