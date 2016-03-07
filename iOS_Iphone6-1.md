#### Test 61362366a48397d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DF63A75B-5DF5-4E5F-901E-5CBE62396A67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DF63A75B-5DF5-4E5F-901E-5CBE62396A67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50901"
,(lldb)     command script import "/tmp/DF63A75B-5DF5-4E5F-901E-5CBE62396A67/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 13:35:20.491 ThaliTest[791:1162007] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D023A14-644A-45B2-A5D7-A3A9F54B4F83/Library/Cookies/Cookies.binarycookies
,2016-03-07 13:35:20.844 ThaliTest[791:1162007] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 13:35:20.845 ThaliTest[791:1162007] Multi-tasking -> Device: YES, App: YES
,2016-03-07 13:35:20.869 ThaliTest[791:1162007] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 13:35:22.796 ThaliTest[791:1162007] Using UIWebView
,2016-03-07 13:35:22.802 ThaliTest[791:1162007] [CDVTimer][handleopenurl] 0.392973ms
,2016-03-07 13:35:22.811 ThaliTest[791:1162007] [CDVTimer][intentandnavigationfilter] 7.660985ms
2016-03-07 13:35:22.812 ThaliTest[791:1162007] [CDVTimer][gesturehandler] 0.329018ms
2016-03-07 13:35:22.812 ThaliTest[791:1162007] [CDVTimer][TotalPluginStartup] 10.267973ms
,2016-03-07 13:35:30.244 ThaliTest[791:1162007] Resetting plugins due to page load.
,2016-03-07 13:35:33.382 ThaliTest[791:1162007] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/index.html
,2016-03-07 13:35:33.605 ThaliTest[791:1162007] JXcore Cordova plugin initializing
,2016-03-07 13:35:33.608 ThaliTest[791:1162237] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 13:35:46.008 ThaliTest[791:1162237] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-07 13:35:46.009 ThaliTest[791:1162237] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 13:35:46.009 ThaliTest[791:1162237] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 13:35:46.010 ThaliTest[791:1162237] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0CA35382-D9CF-42B0-BBEA-58F195A0D59F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```
