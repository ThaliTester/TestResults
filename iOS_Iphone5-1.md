#### Test 613623667b1a8f4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5DE77554-461E-4FF2-840F-3A98BDF0E8CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5DE77554-461E-4FF2-840F-3A98BDF0E8CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50957"
,(lldb)     command script import "/tmp/5DE77554-461E-4FF2-840F-3A98BDF0E8CC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 16:21:36.953 ThaliTest[833:1769219] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/381D245A-CCC1-4C89-9FE0-B53F275F1D5D/Library/Cookies/Cookies.binarycookies
,2016-03-10 16:21:37.065 ThaliTest[833:1769219] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 16:21:37.068 ThaliTest[833:1769219] Multi-tasking -> Device: YES, App: YES
,2016-03-10 16:21:37.089 ThaliTest[833:1769219] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 16:21:39.163 ThaliTest[833:1769219] Using UIWebView
,2016-03-10 16:21:39.168 ThaliTest[833:1769219] [CDVTimer][handleopenurl] 0.362039ms
,2016-03-10 16:21:39.173 ThaliTest[833:1769219] [CDVTimer][intentandnavigationfilter] 5.144000ms
2016-03-10 16:21:39.174 ThaliTest[833:1769219] [CDVTimer][gesturehandler] 0.252962ms
2016-03-10 16:21:39.174 ThaliTest[833:1769219] [CDVTimer][TotalPluginStartup] 6.801009ms
,2016-03-10 16:21:47.627 ThaliTest[833:1769219] Resetting plugins due to page load.
,2016-03-10 16:21:51.670 ThaliTest[833:1769219] Finished load of: file:///var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/index.html
,2016-03-10 16:21:51.875 ThaliTest[833:1769219] JXcore Cordova plugin initializing
,2016-03-10 16:21:51.877 ThaliTest[833:1769399] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 16:22:13.449 ThaliTest[833:1769399] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 16:22:13.451 ThaliTest[833:1769399] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 16:22:13.451 ThaliTest[833:1769399] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 16:22:13.453 ThaliTest[833:1769399] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/489E8849-2A1A-40A9-9B7D-3C995A44114C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
