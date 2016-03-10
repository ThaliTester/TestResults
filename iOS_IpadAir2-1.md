#### Test 61362366b6c9a6f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0BE594E6-75AA-449F-ABA8-4330FA1A7AA3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0BE594E6-75AA-449F-ABA8-4330FA1A7AA3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50534"
,(lldb)     command script import "/tmp/0BE594E6-75AA-449F-ABA8-4330FA1A7AA3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 09:36:42.096 ThaliTest[1051:1616295] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6242D6A8-A6A5-42EF-A958-7C2FFA3B5D07/Library/Cookies/Cookies.binarycookies
,2016-03-10 09:36:42.520 ThaliTest[1051:1616295] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 09:36:42.521 ThaliTest[1051:1616295] Multi-tasking -> Device: YES, App: YES
,2016-03-10 09:36:42.539 ThaliTest[1051:1616295] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 09:36:44.482 ThaliTest[1051:1616295] Using UIWebView
,2016-03-10 09:36:44.488 ThaliTest[1051:1616295] [CDVTimer][handleopenurl] 0.392973ms
,2016-03-10 09:36:44.496 ThaliTest[1051:1616295] [CDVTimer][intentandnavigationfilter] 7.301033ms
2016-03-10 09:36:44.497 ThaliTest[1051:1616295] [CDVTimer][gesturehandler] 0.340998ms
,2016-03-10 09:36:44.497 ThaliTest[1051:1616295] [CDVTimer][TotalPluginStartup] 9.687960ms
,2016-03-10 09:36:51.728 ThaliTest[1051:1616295] Resetting plugins due to page load.
,2016-03-10 09:36:55.375 ThaliTest[1051:1616295] Finished load of: file:///var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/index.html
,2016-03-10 09:36:55.600 ThaliTest[1051:1616295] JXcore Cordova plugin initializing
,2016-03-10 09:36:55.601 ThaliTest[1051:1616532] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 09:37:07.245 ThaliTest[1051:1616532] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 09:37:07.245 ThaliTest[1051:1616532] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 09:37:07.245 ThaliTest[1051:1616532] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 09:37:07.246 ThaliTest[1051:1616532] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3BE31F-8EF6-4FFB-8D51-C3B14EC8959F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
