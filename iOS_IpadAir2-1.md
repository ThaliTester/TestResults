#### Test 6165819876c87fb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6165819876c87fb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A4F0050E-6364-45BF-B88A-93F55E9A4CBD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A4F0050E-6364-45BF-B88A-93F55E9A4CBD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6165819876c87fb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6165819876c87fb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50350"
,(lldb)     command script import "/tmp/A4F0050E-6364-45BF-B88A-93F55E9A4CBD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-05 02:36:56.709 ThaliTest[713:861640] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C150C7F-3F7A-4809-96A5-F3064E4D1E06/Library/Cookies/Cookies.binarycookies
,2016-03-05 02:36:57.090 ThaliTest[713:861640] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-05 02:36:57.092 ThaliTest[713:861640] Multi-tasking -> Device: YES, App: YES
,2016-03-05 02:36:57.110 ThaliTest[713:861640] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-05 02:36:59.116 ThaliTest[713:861640] Using UIWebView
,2016-03-05 02:36:59.123 ThaliTest[713:861640] [CDVTimer][handleopenurl] 0.511050ms
,2016-03-05 02:36:59.130 ThaliTest[713:861640] [CDVTimer][intentandnavigationfilter] 6.587029ms
,2016-03-05 02:36:59.131 ThaliTest[713:861640] [CDVTimer][gesturehandler] 0.310957ms
,2016-03-05 02:36:59.131 ThaliTest[713:861640] [CDVTimer][TotalPluginStartup] 9.036005ms
,2016-03-05 02:37:05.950 ThaliTest[713:861640] Resetting plugins due to page load.
,2016-03-05 02:37:09.500 ThaliTest[713:861640] Finished load of: file:///var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/index.html
,2016-03-05 02:37:09.700 ThaliTest[713:861640] JXcore Cordova plugin initializing
,2016-03-05 02:37:09.701 ThaliTest[713:861859] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-05 02:37:16.218 ThaliTest[713:861859] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-05 02:37:16.219 ThaliTest[713:861859] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-05 02:37:16.219 ThaliTest[713:861859] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-05 02:37:16.221 ThaliTest[713:861859] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7E0FDCC4-6731-44AB-AF25-7000E27FD705/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded


```
