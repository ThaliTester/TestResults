#### Test 64613803f00187f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3187FD58-0CC4-4BE2-8DB6-93789BF46E67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3187FD58-0CC4-4BE2-8DB6-93789BF46E67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49352"
,(lldb)     command script import "/tmp/3187FD58-0CC4-4BE2-8DB6-93789BF46E67/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 14:11:18.629 ThaliTest[2432:4534515] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0FE4DF2B-D279-4C0D-8373-CC2024F386DF/Library/Cookies/Cookies.binarycookies
,2016-03-30 14:11:18.863 ThaliTest[2432:4534515] Apache Cordova native platform version 4.1.0 is starting.
2016-03-30 14:11:18.864 ThaliTest[2432:4534515] Multi-tasking -> Device: YES, App: YES
,2016-03-30 14:11:18.879 ThaliTest[2432:4534515] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 14:11:19.658 ThaliTest[2432:4534515] Using UIWebView
2016-03-30 14:11:19.660 ThaliTest[2432:4534515] [CDVTimer][handleopenurl] 0.109017ms
2016-03-30 14:11:19.662 ThaliTest[2432:4534515] [CDVTimer][intentandnavigationfilter] 2.125025ms
2016-03-30 14:11:19.663 ThaliTest[2432:4534515] [CDVTimer][gesturehandler] 0.105977ms
2016-03-30 14:11:19.663 ThaliTest[2432:4534515] [CDVTimer][TotalPluginStartup] 2.770960ms
,2016-03-30 14:11:22.798 ThaliTest[2432:4534515] Resetting plugins due to page load.
,2016-03-30 14:11:24.041 ThaliTest[2432:4534515] Finished load of: file:///var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/index.html
,2016-03-30 14:11:24.199 ThaliTest[2432:4534515] JXcore Cordova plugin initializing
,2016-03-30 14:11:24.200 ThaliTest[2432:4534671] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-30 14:11:31.285 ThaliTest[2432:4534671] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 14:11:31.286 ThaliTest[2432:4534671] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 14:11:31.286 ThaliTest[2432:4534671] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 14:11:31.288 ThaliTest[2432:4534671] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5033D114-3FF8-44AC-95E6-41601E3A99C7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup

```
