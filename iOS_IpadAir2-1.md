#### Test 616581981d889bb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/542807E5-2A82-4468-AC1C-FEDF6C962274/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/542807E5-2A82-4468-AC1C-FEDF6C962274/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/616581981d889bb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50219"
,(lldb)     command script import "/tmp/542807E5-2A82-4468-AC1C-FEDF6C962274/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-05 01:39:45.887 ThaliTest[703:854813] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DAAD9151-A94A-49ED-ADD4-8627D96ED897/Library/Cookies/Cookies.binarycookies
,2016-03-05 01:39:46.208 ThaliTest[703:854813] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-05 01:39:46.209 ThaliTest[703:854813] Multi-tasking -> Device: YES, App: YES
,2016-03-05 01:39:46.226 ThaliTest[703:854813] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-05 01:39:48.004 ThaliTest[703:854813] Using UIWebView
,2016-03-05 01:39:48.011 ThaliTest[703:854813] [CDVTimer][handleopenurl] 0.441968ms
,2016-03-05 01:39:48.018 ThaliTest[703:854813] [CDVTimer][intentandnavigationfilter] 6.543994ms
,2016-03-05 01:39:48.019 ThaliTest[703:854813] [CDVTimer][gesturehandler] 0.320017ms
,2016-03-05 01:39:48.019 ThaliTest[703:854813] [CDVTimer][TotalPluginStartup] 9.069026ms
,2016-03-05 01:39:55.433 ThaliTest[703:854813] Resetting plugins due to page load.
,2016-03-05 01:39:58.844 ThaliTest[703:854813] Finished load of: file:///var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/index.html
,2016-03-05 01:39:59.054 ThaliTest[703:854813] JXcore Cordova plugin initializing
,2016-03-05 01:39:59.055 ThaliTest[703:855599] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-05 01:40:05.581 ThaliTest[703:855599] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-05 01:40:05.582 ThaliTest[703:855599] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-05 01:40:05.582 ThaliTest[703:855599] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-05 01:40:05.584 ThaliTest[703:855599] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C3DD12A-662A-4CE3-9950-4E672C044105/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded


```
