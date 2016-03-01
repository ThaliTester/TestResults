#### Test 6122644500803c8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6122644500803c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/59948A4A-C050-4C46-8C89-01C660038C8B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/59948A4A-C050-4C46-8C89-01C660038C8B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6122644500803c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6122644500803c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49759"
,(lldb)     command script import "/tmp/59948A4A-C050-4C46-8C89-01C660038C8B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-01 16:13:00.078 ThaliTest[376:407812] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/90DE6625-EC69-4F7E-9018-64201CFEA3B3/Library/Cookies/Cookies.binarycookies
,2016-03-01 16:13:00.604 ThaliTest[376:407812] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-01 16:13:00.606 ThaliTest[376:407812] Multi-tasking -> Device: YES, App: YES
,2016-03-01 16:13:00.626 ThaliTest[376:407812] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-01 16:13:02.702 ThaliTest[376:407812] Using UIWebView
,2016-03-01 16:13:02.709 ThaliTest[376:407812] [CDVTimer][handleopenurl] 0.427961ms
,2016-03-01 16:13:02.715 ThaliTest[376:407812] [CDVTimer][intentandnavigationfilter] 5.654037ms
2016-03-01 16:13:02.715 ThaliTest[376:407812] [CDVTimer][gesturehandler] 0.265956ms
2016-03-01 16:13:02.716 ThaliTest[376:407812] [CDVTimer][TotalPluginStartup] 7.476985ms
,2016-03-01 16:13:11.055 ThaliTest[376:407812] Resetting plugins due to page load.
,2016-03-01 16:13:14.592 ThaliTest[376:407812] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/index.html
,2016-03-01 16:13:14.918 ThaliTest[376:407812] JXcore Cordova plugin initializing
,2016-03-01 16:13:14.921 ThaliTest[376:408057] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-01 16:13:31.568 ThaliTest[376:408057] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-01 16:13:31.570 ThaliTest[376:408057] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-01 16:13:31.570 ThaliTest[376:408057] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-01 16:13:31.575 ThaliTest[376:408057] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE0D2900-D694-4A70-A4BD-73A63A765CB1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
