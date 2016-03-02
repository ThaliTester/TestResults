#### Test 613623660556c10_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3E13A955-7846-46D5-94DF-176ACA8065C7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3E13A955-7846-46D5-94DF-176ACA8065C7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50268"
,(lldb)     command script import "/tmp/3E13A955-7846-46D5-94DF-176ACA8065C7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 09:53:19.245 ThaliTest[459:489901] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14F729AA-1B56-4FE8-8429-22A700C73D14/Library/Cookies/Cookies.binarycookies
,2016-03-02 09:53:19.545 ThaliTest[459:489901] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 09:53:19.546 ThaliTest[459:489901] Multi-tasking -> Device: YES, App: YES
,2016-03-02 09:53:19.565 ThaliTest[459:489901] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 09:53:21.442 ThaliTest[459:489901] Using UIWebView
,2016-03-02 09:53:21.449 ThaliTest[459:489901] [CDVTimer][handleopenurl] 0.585020ms
,2016-03-02 09:53:21.456 ThaliTest[459:489901] [CDVTimer][intentandnavigationfilter] 7.187009ms
2016-03-02 09:53:21.457 ThaliTest[459:489901] [CDVTimer][gesturehandler] 0.328004ms
2016-03-02 09:53:21.458 ThaliTest[459:489901] [CDVTimer][TotalPluginStartup] 9.696007ms
,2016-03-02 09:53:28.595 ThaliTest[459:489901] Resetting plugins due to page load.
,2016-03-02 09:53:31.730 ThaliTest[459:489901] Finished load of: file:///var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/index.html
,2016-03-02 09:53:31.959 ThaliTest[459:489901] JXcore Cordova plugin initializing
2016-03-02 09:53:31.959 ThaliTest[459:490146] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 09:53:44.488 ThaliTest[459:490146] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 09:53:44.488 ThaliTest[459:490146] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-02 09:53:44.488 ThaliTest[459:490146,] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":true,"bluetoothLowEnergy":false,"bssidName":null,"cellular":true,"bluetooth":true}

2016-03-02 09:53:44.489 ThaliTest[459:490146] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CA12613-F06F-48C6-8FCA-4507C4E6F1F8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
