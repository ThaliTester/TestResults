#### Test 6136236661fd38c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5A661D01-7EA0-449D-B34C-133FFCF66730/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5A661D01-7EA0-449D-B34C-133FFCF66730/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51267"
,(lldb)     command script import "/tmp/5A661D01-7EA0-449D-B34C-133FFCF66730/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-03 14:56:13.189 ThaliTest[464:691029] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/57CD164A-8736-48FE-B040-7933FDCF96A7/Library/Cookies/Cookies.binarycookies
,2016-03-03 14:56:13.683 ThaliTest[464:691029] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-03 14:56:13.685 ThaliTest[464:691029] Multi-tasking -> Device: YES, App: YES
,2016-03-03 14:56:13.705 ThaliTest[464:691029] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-03 14:56:15.765 ThaliTest[464:691029] Using UIWebView
,2016-03-03 14:56:15.769 ThaliTest[464:691029] [CDVTimer][handleopenurl] 0.376999ms
,2016-03-03 14:56:15.775 ThaliTest[464:691029] [CDVTimer][intentandnavigationfilter] 5.177975ms
2016-03-03 14:56:15.776 ThaliTest[464:691029] [CDVTimer][gesturehandler] 0.276983ms
2016-03-03 14:56:15.776 ThaliTest[464:691029] [CDVTimer][TotalPluginStartup] 7.132053ms
,2016-03-03 14:56:24.106 ThaliTest[464:691029] Resetting plugins due to page load.
,2016-03-03 14:56:27.827 ThaliTest[464:691029] Finished load of: file:///var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/index.html
,2016-03-03 14:56:28.034 ThaliTest[464:691029] JXcore Cordova plugin initializing
,2016-03-03 14:56:28.036 ThaliTest[464:691209] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-03 14:56:49.641 ThaliTest[464:691209] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-03 14:56:49.642 ThaliTest[464:691209] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-03 14:56:49.643 ThaliTest[464:691209] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-03 14:56:49.645 ThaliTest[464:691209] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/519558A7-06B0-418E-AFD3-953D726C3E72/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
