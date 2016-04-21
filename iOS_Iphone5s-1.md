#### Test 672996567f6295f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5E6118E0-2C0E-41C4-949F-660F7745EBA0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5E6118E0-2C0E-41C4-949F-660F7745EBA0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/672996567f6295f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54207"
,(lldb)     command script import "/tmp/5E6118E0-2C0E-41C4-949F-660F7745EBA0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-04-21 08:02:21.337 ThaliTest[3519:7727377] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D1A5035B-A99E-49A9-8391-099C59C00197/Library/Cookies/Cookies.binarycookies
,2016-04-21 08:02:21.785 ThaliTest[3519:7727377] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-21 08:02:21.787 ThaliTest[3519:7727377] Multi-tasking -> Device: YES, App: YES
,2016-04-21 08:02:21.811 ThaliTest[3519:7727377] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-21 08:02:23.791 ThaliTest[3519:7727377] Using UIWebView
,2016-04-21 08:02:23.799 ThaliTest[3519:7727377] [CDVTimer][handleopenurl] 0.482976ms
,2016-04-21 08:02:23.808 ThaliTest[3519:7727377] [CDVTimer][intentandnavigationfilter] 8.166015ms
2016-04-21 08:02:23.809 ThaliTest[3519:7727377] [CDVTimer][gesturehandler] 0.366986ms
2016-04-21 08:02:23.809 ThaliTest[3519:7727377] [CDVTimer][TotalPluginStartup] 11.097968ms
,2016-04-21 08:02:31.339 ThaliTest[3519:7727377] Resetting plugins due to page load.
,2016-04-21 08:02:35.446 ThaliTest[3519:7727377] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/index.html
,2016-04-21 08:02:35.673 ThaliTest[3519:7727377] JXcore Cordova plugin initializing
,2016-04-21 08:02:35.818 ThaliTest[3519:7727595] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-21 08:02:44.559 ThaliTest[3519:7727595] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-21 08:02:44.560 ThaliTest[3519:7727595] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-21 08:02:44.560 ThaliTest[3519:7727595] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-21 08:02:44.562 ThaliTest[3519:7727595] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A5CAC90-8B0D-46E7-B9D6-6642D0C9E2BC/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-21 08:02:52.446 ThaliTest[3519:7727377] THREAD WARNING: ['JXcore'] took '7517.668945' ms. Plugin should use a background thread.

```
