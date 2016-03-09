#### Test 6012434764ab483_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/935A5A89-1DA2-4111-A91B-C1E9C30ECA82/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/935A5A89-1DA2-4111-A91B-C1E9C30ECA82/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49617"
,(lldb)     command script import "/tmp/935A5A89-1DA2-4111-A91B-C1E9C30ECA82/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 02:35:41.022 ThaliTest[735:1522375] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/39C4D382-5046-47E7-8F62-9ECCFB5FF1A9/Library/Cookies/Cookies.binarycookies
,2016-03-09 02:35:41.136 ThaliTest[735:1522375] Apache Cordova native platform version 4.0.1 is starting.
2016-03-09 02:35:41.138 ThaliTest[735:1522375] Multi-tasking -> Device: YES, App: YES
,2016-03-09 02:35:41.157 ThaliTest[735:1522375] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 02:35:43.295 ThaliTest[735:1522375] Using UIWebView
,2016-03-09 02:35:43.300 ThaliTest[735:1522375] [CDVTimer][handleopenurl] 0.288010ms
,2016-03-09 02:35:43.305 ThaliTest[735:1522375] [CDVTimer][intentandnavigationfilter] 5.250990ms
2016-03-09 02:35:43.306 ThaliTest[735:1522375] [CDVTimer][gesturehandler] 0.293970ms
2016-03-09 02:35:43.306 ThaliTest[735:1522375] [CDVTimer][TotalPluginStartup] 6.927967ms
,2016-03-09 02:35:51.740 ThaliTest[735:1522375] Resetting plugins due to page load.
,2016-03-09 02:35:55.874 ThaliTest[735:1522375] Finished load of: file:///var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/index.html
,2016-03-09 02:35:56.081 ThaliTest[735:1522375] JXcore Cordova plugin initializing
,2016-03-09 02:35:56.083 ThaliTest[735:1522574] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!
,
,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 02:36:13.039 ThaliTest[735:1522574] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-09 02:36:13.040 ThaliTest[735:1522574] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-09 02:36:13.041 ThaliTest[735:1522574] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 02:36:13.046 ThaliTest[735:1522574] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E29CE9A7-3AC4-4BC3-B38A-D65BE2683447/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
