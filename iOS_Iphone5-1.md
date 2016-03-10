#### Test 62328822054c831_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8752DDF5-4E1D-47C9-AD55-0F0DBF6B42A3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8752DDF5-4E1D-47C9-AD55-0F0DBF6B42A3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51199"
,(lldb)     command script import "/tmp/8752DDF5-4E1D-47C9-AD55-0F0DBF6B42A3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 21:35:42.813 ThaliTest[855:1803811] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5BD786BF-6C42-4CDF-A0A8-43E7E2F37C20/Library/Cookies/Cookies.binarycookies
,2016-03-10 21:35:42.928 ThaliTest[855:1803811] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 21:35:42.930 ThaliTest[855:1803811] Multi-tasking -> Device: YES, App: YES
,2016-03-10 21:35:42.953 ThaliTest[855:1803811] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 21:35:45.070 ThaliTest[855:1803811] Using UIWebView
,2016-03-10 21:35:45.076 ThaliTest[855:1803811] [CDVTimer][handleopenurl] 0.267982ms
,2016-03-10 21:35:45.082 ThaliTest[855:1803811] [CDVTimer][intentandnavigationfilter] 5.172014ms
2016-03-10 21:35:45.082 ThaliTest[855:1803811] [CDVTimer][gesturehandler] 0.257015ms
2016-03-10 21:35:45.083 ThaliTest[855:1803811] [CDVTimer][TotalPluginStartup] 6.733000ms
,2016-03-10 21:35:53.915 ThaliTest[855:1803811] Resetting plugins due to page load.
,2016-03-10 21:35:58.100 ThaliTest[855:1803811] Finished load of: file:///var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/index.html
,2016-03-10 21:35:58.302 ThaliTest[855:1803811] JXcore Cordova plugin initializing
,2016-03-10 21:35:58.304 ThaliTest[855:1804002] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 21:36:15.264 ThaliTest[855:1804002] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 21:36:15.265 ThaliTest[855:1804002] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 21:36:15.266 ThaliTest[855:1804002] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 21:36:15.271 ThaliTest[855:1804002] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A626FB9D-55D1-4FE2-A181-DD039739EE55/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
