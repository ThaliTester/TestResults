#### Test 636801181df08af_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4BFAE5E3-DD8C-4BB1-9090-CD67AB115A78/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
Executing commands in '/tmp/4BFAE5E3-DD8C-4BB1-9090-CD67AB115A78/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54587"
,(lldb)     command script import "/tmp/4BFAE5E3-DD8C-4BB1-9090-CD67AB115A78/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 09:05:19.432 ThaliTest[2014:3382176] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/48E6D0E7-1602-48BE-AAAC-4C9A64838CA4/Library/Cookies/Cookies.binarycookies
,2016-03-22 09:05:19.813 ThaliTest[2014:3382176] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 09:05:19.814 ThaliTest[2014:3382176] Multi-tasking -> Device: YES, App: YES
,2016-03-22 09:05:19.834 ThaliTest[2014:3382176] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 09:05:21.832 ThaliTest[2014:3382176] Using UIWebView
,2016-03-22 09:05:21.839 ThaliTest[2014:3382176] [CDVTimer][handleopenurl] 0.384986ms
,2016-03-22 09:05:21.846 ThaliTest[2014:3382176] [CDVTimer][intentandnavigationfilter] 7.385015ms
,2016-03-22 09:05:21.847 ThaliTest[2014:3382176] [CDVTimer][gesturehandler] 0.331998ms
,2016-03-22 09:05:21.848 ThaliTest[2014:3382176] [CDVTimer][TotalPluginStartup] 9.683013ms
,2016-03-22 09:05:29.205 ThaliTest[2014:3382176] Resetting plugins due to page load.
,2016-03-22 09:05:32.609 ThaliTest[2014:3382176] Finished load of: file:///var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/index.html
,2016-03-22 09:05:32.838 ThaliTest[2014:3382176] JXcore Cordova plugin initializing
,2016-03-22 09:05:32.839 ThaliTest[2014:3382432] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 09:05:39.343 ThaliTest[2014:3382432] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:05:39.343 ThaliTest[2014:3382432] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:05:39.344 ThaliTest[2014:3382432] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:05:39.346 ThaliTest[2014:3382432] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1F2FDF1-C8EE-4E3D-9908-0442327F9A19/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 09:05:44.589 ThaliTest[2014:3382176] THREAD WARNING: ['JXcore'] took '4965.824951' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
