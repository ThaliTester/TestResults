#### Test 61362366121daa0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/25A3DCEF-60B1-424D-851B-0C145E18FB32/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/25A3DCEF-60B1-424D-851B-0C145E18FB32/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50574"
,(lldb)     command script import "/tmp/25A3DCEF-60B1-424D-851B-0C145E18FB32/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 14:34:51.110 ThaliTest[505:527329] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B4A36A7-891C-4AC8-B1D4-A240AFCDBCE2/Library/Cookies/Cookies.binarycookies
,2016-03-02 14:34:51.491 ThaliTest[505:527329] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 14:34:51.493 ThaliTest[505:527329] Multi-tasking -> Device: YES, App: YES
,2016-03-02 14:34:51.516 ThaliTest[505:527329] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 14:34:53.549 ThaliTest[505:527329] Using UIWebView
,2016-03-02 14:34:53.561 ThaliTest[505:527329] [CDVTimer][handleopenurl] 0.464976ms
,2016-03-02 14:34:53.569 ThaliTest[505:527329] [CDVTimer][intentandnavigationfilter] 8.027017ms
2016-03-02 14:34:53.570 ThaliTest[505:527329] [CDVTimer][gesturehandler] 0.369012ms
2016-03-02 14:34:53.571 ThaliTest[505:527329] [CDVTimer][TotalPluginStartup] 10.749996ms
,2016-03-02 14:35:00.485 ThaliTest[505:527329] Resetting plugins due to page load.
,2016-03-02 14:35:03.831 ThaliTest[505:527329] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/index.html
,2016-03-02 14:35:04.102 ThaliTest[505:527329] JXcore Cordova plugin initializing
,2016-03-02 14:35:04.104 ThaliTest[505:527531] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 14:35:18.054 ThaliTest[505:527531] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 14:35:18.055 ThaliTest[505:527531] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-02 14:35:18.055 ThaliTest[505:527531] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-02 14:35:18.057 ThaliTest[505:527531] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4EFCE68-D954-4E61-B778-3586BF4319F4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
