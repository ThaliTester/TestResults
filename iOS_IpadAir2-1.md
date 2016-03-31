#### Test 646138036c5f71d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/615A7AB0-BBE0-457C-A898-B21D4F882825/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/615A7AB0-BBE0-457C-A898-B21D4F882825/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49773"
,(lldb)     command script import "/tmp/615A7AB0-BBE0-457C-A898-B21D4F882825/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 15:13:35.532 ThaliTest[2570:4804514] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E773580B-EEBF-4A8A-81AB-9E92DFE0F30F/Library/Cookies/Cookies.binarycookies
,2016-03-31 15:13:35.949 ThaliTest[2570:4804514] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 15:13:35.950 ThaliTest[2570:4804514] Multi-tasking -> Device: YES, App: YES
,2016-03-31 15:13:35.969 ThaliTest[2570:4804514] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 15:13:38.275 ThaliTest[2570:4804514] Using UIWebView
,2016-03-31 15:13:38.281 ThaliTest[2570:4804514] [CDVTimer][handleopenurl] 0.518024ms
,2016-03-31 15:13:38.289 ThaliTest[2570:4804514] [CDVTimer][intentandnavigationfilter] 7.351995ms
,2016-03-31 15:13:38.290 ThaliTest[2570:4804514] [CDVTimer][gesturehandler] 0.335991ms
,2016-03-31 15:13:38.290 ThaliTest[2570:4804514] [CDVTimer][TotalPluginStartup] 9.846032ms
,2016-03-31 15:13:47.095 ThaliTest[2570:4804514] Resetting plugins due to page load.
,2016-03-31 15:13:51.259 ThaliTest[2570:4804514] Finished load of: file:///var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/index.html
,2016-03-31 15:13:51.485 ThaliTest[2570:4804514] JXcore Cordova plugin initializing
,2016-03-31 15:13:51.485 ThaliTest[2570:4804730] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-31 15:13:57.948 ThaliTest[2570:4804730] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 15:13:57.949 ThaliTest[2570:4804730] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 15:13:57.949 ThaliTest[2570:4804730] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 15:13:57.951 ThaliTest[2570:4804730] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/269975ED-5DE4-481E-A7AE-A1E0A26B3B89/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 15:14:03.185 ThaliTest[2570:4804514] THREAD WARNING: ['JXcore'] took '4958.448975' ms. Plugin should use a background thread.

```
