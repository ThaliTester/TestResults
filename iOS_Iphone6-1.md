#### Test 62509094c3227b2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c3227b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5020258C-B64B-4E87-8EAA-F0E6834CDE45/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5020258C-B64B-4E87-8EAA-F0E6834CDE45/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c3227b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c3227b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49861"
,(lldb)     command script import "/tmp/5020258C-B64B-4E87-8EAA-F0E6834CDE45/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 06:43:00.748 ThaliTest[1272:2101776] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CC13D2FE-D5D0-49D7-A8B8-117966814AD1/Library/Cookies/Cookies.binarycookies
,2016-03-14 06:43:01.110 ThaliTest[1272:2101776] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 06:43:01.112 ThaliTest[1272:2101776] Multi-tasking -> Device: YES, App: YES
,2016-03-14 06:43:01.134 ThaliTest[1272:2101776] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 06:43:03.082 ThaliTest[1272:2101776] Using UIWebView
,2016-03-14 06:43:03.090 ThaliTest[1272:2101776] [CDVTimer][handleopenurl] 0.379026ms
,2016-03-14 06:43:03.099 ThaliTest[1272:2101776] [CDVTimer][intentandnavigationfilter] 8.744001ms
2016-03-14 06:43:03.100 ThaliTest[1272:2101776] [CDVTimer][gesturehandler] 0.383973ms
2016-03-14 06:43:03.100 ThaliTest[1272:2101776] [CDVTimer][TotalPluginStartup] 11.198997ms
,2016-03-14 06:43:10.018 ThaliTest[1272:2101776] Resetting plugins due to page load.
,2016-03-14 06:43:13.154 ThaliTest[1272:2101776] Finished load of: file:///var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/index.html
,2016-03-14 06:43:13.377 ThaliTest[1272:2101776] JXcore Cordova plugin initializing
,2016-03-14 06:43:13.379 ThaliTest[1272:2101990] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 06:43:25.855 ThaliTest[1272:2101990] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 06:43:25.856 ThaliTest[1272:2101990] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 06:43:25.856 ThaliTest[1272:2,101990] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 06:43:25.857 ThaliTest[1272:2101990] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B92B76F-69B4-46C2-BE34-431B3BF73713/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
