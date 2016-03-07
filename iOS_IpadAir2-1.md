#### Test 6012434797f7ca7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DB984FDA-0218-4658-A442-1BCFABBD7925/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DB984FDA-0218-4658-A442-1BCFABBD7925/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51745"
,(lldb)     command script import "/tmp/DB984FDA-0218-4658-A442-1BCFABBD7925/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 20:27:47.050 ThaliTest[860:1249726] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7363D05A-2414-4259-AAB8-F194A4E03BF1/Library/Cookies/Cookies.binarycookies
,2016-03-07 20:27:47.473 ThaliTest[860:1249726] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 20:27:47.474 ThaliTest[860:1249726] Multi-tasking -> Device: YES, App: YES
,2016-03-07 20:27:47.492 ThaliTest[860:1249726] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 20:27:49.449 ThaliTest[860:1249726] Using UIWebView
,2016-03-07 20:27:49.456 ThaliTest[860:1249726] [CDVTimer][handleopenurl] 0.398993ms
,2016-03-07 20:27:49.463 ThaliTest[860:1249726] [CDVTimer][intentandnavigationfilter] 6.702006ms
,2016-03-07 20:27:49.464 ThaliTest[860:1249726] [CDVTimer][gesturehandler] 0.362992ms
,2016-03-07 20:27:49.464 ThaliTest[860:1249726] [CDVTimer][TotalPluginStartup] 9.190023ms
,2016-03-07 20:27:56.479 ThaliTest[860:1249726] Resetting plugins due to page load.
,2016-03-07 20:28:00.146 ThaliTest[860:1249726] Finished load of: file:///var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/index.html
,2016-03-07 20:28:00.289 ThaliTest[860:1249726] JXcore Cordova plugin initializing
,2016-03-07 20:28:00.290 ThaliTest[860:1249975] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 20:28:06.790 ThaliTest[860:1249975] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 20:28:06.790 ThaliTest[860:1249975] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-07 20:28:06.790 ThaliTest[860:1249975] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-07 20:28:06.793 ThaliTest[860:1249975] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/48104B87-4509-44FD-8982-C981D9000F0E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
