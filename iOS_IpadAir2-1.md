#### Test 62509094ffd3875_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/35D764C4-0D77-4FBD-8447-673BD784250E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/35D764C4-0D77-4FBD-8447-673BD784250E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49434"
,(lldb)     command script import "/tmp/35D764C4-0D77-4FBD-8447-673BD784250E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 11:04:26.258 ThaliTest[1162:1739854] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF213794-8C29-4501-BCF9-2A5BD4D3DBF4/Library/Cookies/Cookies.binarycookies
,2016-03-11 11:04:26.617 ThaliTest[1162:1739854] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 11:04:26.619 ThaliTest[1162:1739854] Multi-tasking -> Device: YES, App: YES
,2016-03-11 11:04:26.638 ThaliTest[1162:1739854] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 11:04:28.497 ThaliTest[1162:1739854] Using UIWebView
,2016-03-11 11:04:28.504 ThaliTest[1162:1739854] [CDVTimer][handleopenurl] 0.400007ms
,2016-03-11 11:04:28.512 ThaliTest[1162:1739854] [CDVTimer][intentandnavigationfilter] 7.436991ms
,2016-03-11 11:04:28.513 ThaliTest[1162:1739854] [CDVTimer][gesturehandler] 0.326991ms
,2016-03-11 11:04:28.513 ThaliTest[1162:1739854] [CDVTimer][TotalPluginStartup] 10.070026ms
,2016-03-11 11:04:35.047 ThaliTest[1162:1739854] Resetting plugins due to page load.
,2016-03-11 11:04:38.273 ThaliTest[1162:1739854] Finished load of: file:///var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/index.html
,2016-03-11 11:04:38.469 ThaliTest[1162:1739854] JXcore Cordova plugin initializing
,2016-03-11 11:04:38.470 ThaliTest[1162:1740060] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 11:04:50.137 ThaliTest[1162:1740060] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 11:04:50.138 ThaliTest[1162:1740060] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 11:04:50.138 ThaliTest[1162:1740060] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 11:04:50.139 ThaliTest[1162:1740060] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4B9CF05-9AB1-44B8-A5FA-7E987BBAFDB8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
