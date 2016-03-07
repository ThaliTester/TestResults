#### Test 6012434797f7ca7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D21A8A41-C801-4BB4-BC94-6FC2ECB55A3A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D21A8A41-C801-4BB4-BC94-6FC2ECB55A3A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51709"
,(lldb)     command script import "/tmp/D21A8A41-C801-4BB4-BC94-6FC2ECB55A3A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 20:26:39.507 ThaliTest[677:1332704] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41AD6014-A5CF-4DC7-B72C-30A81AA610D0/Library/Cookies/Cookies.binarycookies
,2016-03-07 20:26:39.622 ThaliTest[677:1332704] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 20:26:39.623 ThaliTest[677:1332704] Multi-tasking -> Device: YES, App: YES
,2016-03-07 20:26:39.643 ThaliTest[677:1332704] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 20:26:41.733 ThaliTest[677:1332704] Using UIWebView
,2016-03-07 20:26:41.738 ThaliTest[677:1332704] [CDVTimer][handleopenurl] 0.391006ms
,2016-03-07 20:26:41.743 ThaliTest[677:1332704] [CDVTimer][intentandnavigationfilter] 5.135953ms
2016-03-07 20:26:41.744 ThaliTest[677:1332704] [CDVTimer][gesturehandler] 0.306010ms
2016-03-07 20:26:41.744 ThaliTest[677:1332704] [CDVTimer][TotalPluginStartup] 6.860971ms
,2016-03-07 20:26:50.076 ThaliTest[677:1332704] Resetting plugins due to page load.
,2016-03-07 20:26:54.251 ThaliTest[677:1332704] Finished load of: file:///var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/index.html
,2016-03-07 20:26:54.455 ThaliTest[677:1332704] JXcore Cordova plugin initializing
,2016-03-07 20:26:54.457 ThaliTest[677:1332879] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 20:27:11.141 ThaliTest[677:1332879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 20:27:11.141 ThaliTest[677:1332879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 20:27:11.142 ThaliTest[677:1332,879] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-07 20:27:11.148 ThaliTest[677:1332879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B4A3A66D-352C-4B20-83DE-889AE9355D1D/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
