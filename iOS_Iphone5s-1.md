#### Test 64613803f00187f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B1F8DE0B-1C8E-44F2-B192-45F101ECD2F1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B1F8DE0B-1C8E-44F2-B192-45F101ECD2F1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803f00187f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49354"
,(lldb)     command script import "/tmp/B1F8DE0B-1C8E-44F2-B192-45F101ECD2F1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 14:11:20.550 ThaliTest[2490:4579617] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CDE63D4-CB0D-402A-ABF2-50A49A2D31B8/Library/Cookies/Cookies.binarycookies
,2016-03-30 14:11:20.805 ThaliTest[2490:4579617] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-30 14:11:20.806 ThaliTest[2490:4579617] Multi-tasking -> Device: YES, App: YES
,2016-03-30 14:11:20.825 ThaliTest[2490:4579617] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 14:11:21.624 ThaliTest[2490:4579617] Using UIWebView
2016-03-30 14:11:21.626 ThaliTest[2490:4579617] [CDVTimer][handleopenurl] 0.137031ms
,2016-03-30 14:11:21.630 ThaliTest[2490:4579617] [CDVTimer][intentandnavigationfilter] 3.816962ms
2016-03-30 14:11:21.631 ThaliTest[2490:4579617] [CDVTimer][gesturehandler] 0.162959ms
2016-03-30 14:11:21.631 ThaliTest[2490:4579617] [CDVTimer][TotalPluginS,tartup] 4.712999ms
,2016-03-30 14:11:24.849 ThaliTest[2490:4579617] Resetting plugins due to page load.
,2016-03-30 14:11:26.130 ThaliTest[2490:4579617] Finished load of: file:///var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/index.html
,2016-03-30 14:11:26.305 ThaliTest[2490:4579617] JXcore Cordova plugin initializing
,2016-03-30 14:11:26.307 ThaliTest[2490:4579766] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-30 14:11:34.536 ThaliTest[2490:4579766] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 14:11:34.536 ThaliTest[2490:4579766] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 14:11:34.537 ThaliTest[2490:4,579766] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 14:11:34.539 ThaliTest[2490:4579766] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/53944BF0-4EF6-414D-8B9F-C595319F2642/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup

```
