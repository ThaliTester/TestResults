#### Test 60124347d1a8dac_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7130D0D3-A4BA-4E49-8777-5C8F35D79695/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7130D0D3-A4BA-4E49-8777-5C8F35D79695/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50842"
,(lldb)     command script import "/tmp/7130D0D3-A4BA-4E49-8777-5C8F35D79695/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 15:20:41.103 ThaliTest[1046:1615104] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/556E2F7D-0071-4C5C-A357-9F5F09E03709/Library/Cookies/Cookies.binarycookies
,2016-03-10 15:20:41.518 ThaliTest[1046:1615104] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 15:20:41.519 ThaliTest[1046:1615104] Multi-tasking -> Device: YES, App: YES
,2016-03-10 15:20:41.547 ThaliTest[1046:1615104] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 15:20:43.350 ThaliTest[1046:1615104] Using UIWebView
,2016-03-10 15:20:43.357 ThaliTest[1046:1615104] [CDVTimer][handleopenurl] 0.395000ms
,2016-03-10 15:20:43.365 ThaliTest[1046:1615104] [CDVTimer][intentandnavigationfilter] 7.398009ms
2016-03-10 15:20:43.366 ThaliTest[1046:1615104] [CDVTimer][gesturehandler] 0.343025ms
2016-03-10 15:20:43.366 ThaliTest[1046:1615104] [CDVTimer][TotalPluginStartup] 9.838045ms
,2016-03-10 15:20:50.172 ThaliTest[1046:1615104] Resetting plugins due to page load.
,2016-03-10 15:20:53.382 ThaliTest[1046:1615104] Finished load of: file:///var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/index.html
,2016-03-10 15:20:53.609 ThaliTest[1046:1615104] JXcore Cordova plugin initializing
2016-03-10 15:20:53.610 ThaliTest[1046:1615310] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 15:21:00.999 ThaliTest[1046:1615310] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 15:21:00.999 ThaliTest[1046:1615310] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 15:21:00.999 ThaliTest[1046:1615310] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 15:21:01.002 ThaliTest[1046:1615310] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8305639E-5505-462B-9F4F-ADF8E95B7913/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
