#### Test 64613803adf70b9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8E19698A-67E3-4058-9742-DBC511CFB385/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8E19698A-67E3-4058-9742-DBC511CFB385/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49842"
,(lldb)     command script import "/tmp/8E19698A-67E3-4058-9742-DBC511CFB385/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 16:26:36.767 ThaliTest[2532:4705953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B905EBC6-4B54-4EE2-9962-B3734FF123CD/Library/Cookies/Cookies.binarycookies
,2016-03-31 16:26:36.993 ThaliTest[2532:4705953] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 16:26:36.994 ThaliTest[2532:4705953] Multi-tasking -> Device: YES, App: YES
,2016-03-31 16:26:37.010 ThaliTest[2532:4705953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 16:26:37.795 ThaliTest[2532:4705953] Using UIWebView
2016-03-31 16:26:37.797 ThaliTest[2532:4705953] [CDVTimer][handleopenurl] 0.122011ms
2016-03-31 16:26:37.799 ThaliTest[2532:4705953] [CDVTimer][intentandnavigationfilter] 2.170980ms
2016-03-31 16:26:37.800 ThaliTest[2532:4705953] [CDVTimer][gesturehandler] 0.095010ms
2016-03-31 16:26:37.800 ThaliTest[2532:4705953] [CDVTimer][TotalPluginStartup] 2.833009ms
,2016-03-31 16:26:40.911 ThaliTest[2532:4705953] Resetting plugins due to page load.
,2016-03-31 16:26:42.310 ThaliTest[2532:4705953] Finished load of: file:///var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/index.html
,2016-03-31 16:26:42.466 ThaliTest[2532:4705953] JXcore Cordova plugin initializing
2016-03-31 16:26:42.468 ThaliTest[2532:4706117] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 16:26:49.439 ThaliTest[2532:4706117] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 16:26:49.440 ThaliTest[2532:4706117] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 16:26:49.440 ThaliTest[2532:4706117] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 16:26:49.441 ThaliTest[2532:4706117] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7D8EBB9A-19AE-4FBF-B973-E0528C68926B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
