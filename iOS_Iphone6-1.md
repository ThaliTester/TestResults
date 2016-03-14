#### Test 6250909442642cd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2A07D0B3-EF30-47D1-A67F-C2D30B37AF85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2A07D0B3-EF30-47D1-A67F-C2D30B37AF85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50003"
,(lldb)     command script import "/tmp/2A07D0B3-EF30-47D1-A67F-C2D30B37AF85/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 07:36:52.326 ThaliTest[1281:2107418] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28488E84-5250-42EF-BB9B-C2CD5D1FDB80/Library/Cookies/Cookies.binarycookies
,2016-03-14 07:36:52.686 ThaliTest[1281:2107418] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 07:36:52.687 ThaliTest[1281:2107418] Multi-tasking -> Device: YES, App: YES
,2016-03-14 07:36:52.711 ThaliTest[1281:2107418] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 07:36:54.536 ThaliTest[1281:2107418] Using UIWebView
,2016-03-14 07:36:54.543 ThaliTest[1281:2107418] [CDVTimer][handleopenurl] 0.391960ms
,2016-03-14 07:36:54.551 ThaliTest[1281:2107418] [CDVTimer][intentandnavigationfilter] 8.009017ms
2016-03-14 07:36:54.552 ThaliTest[1281:2107418] [CDVTimer][gesturehandler] 0.379980ms
2016-03-14 07:36:54.552 ThaliTest[1281:2107418] [CDVTimer][TotalPluginS,tartup] 10.433018ms
,2016-03-14 07:37:01.475 ThaliTest[1281:2107418] Resetting plugins due to page load.
,2016-03-14 07:37:04.751 ThaliTest[1281:2107418] Finished load of: file:///var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/index.html
,2016-03-14 07:37:04.974 ThaliTest[1281:2107418] JXcore Cordova plugin initializing
,2016-03-14 07:37:04.976 ThaliTest[1281:2107622] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 07:37:17.515 ThaliTest[1281:2107622] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 07:37:17.515 ThaliTest[1281:2107622] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 07:37:17.516 ThaliTest[1281:2107622] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 07:37:17.516 ThaliTest[1281:2107622] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97BABF27-8669-4550-B184-9168BA49C636/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
