#### Test 757892680c366d1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AC5EFB6F-2187-4E77-9C2F-31153B97DAA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AC5EFB6F-2187-4E77-9C2F-31153B97DAA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65526"
,(lldb)     command script import "/tmp/AC5EFB6F-2187-4E77-9C2F-31153B97DAA5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 12:06:28.217 ThaliTest[6114:19004487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E6742BC7-3491-484E-8DFD-72E0461145E2/Library/Cookies/Cookies.binarycookies
,2016-07-01 12:06:28.636 ThaliTest[6114:19004487] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 12:06:28.638 ThaliTest[6114:19004487] Multi-tasking -> Device: YES, App: YES
,2016-07-01 12:06:28.662 ThaliTest[6114:19004487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 12:06:30.581 ThaliTest[6114:19004487] Using UIWebView
,2016-07-01 12:06:30.588 ThaliTest[6114:19004487] [CDVTimer][handleopenurl] 0.457048ms
,2016-07-01 12:06:30.596 ThaliTest[6114:19004487] [CDVTimer][intentandnavigationfilter] 7.135987ms
2016-07-01 12:06:30.597 ThaliTest[6114:19004487] [CDVTimer][gesturehandler] 0.325978ms
2016-07-01 12:06:30.597 ThaliTest[6114:19004487] [CDVTimer][TotalPlug,inStartup] 9.545028ms
,2016-07-01 12:06:38.158 ThaliTest[6114:19004487] Resetting plugins due to page load.
,2016-07-01 12:06:41.309 ThaliTest[6114:19004487] Finished load of: file:///var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/index.html
,2016-07-01 12:06:41.540 ThaliTest[6114:19004487] JXcore Cordova plugin initializing
2016-07-01 12:06:41.541 ThaliTest[6114:19004713] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 12:06:49.055 ThaliTest[6114:19004713] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 12:06:49.056 ThaliTest[6114:19004713] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 12:06:49.056 ThaliTest[6114:19004713] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 12:06:49.058 ThaliTest[6114:19004713] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6650569D-60BF-4784-AC19-0E4968365499/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-01 12:06:55.153 ThaliTest[6114:19004487] THREAD WARNING: ['JXcore'] took '5783.694092' ms. Plugin should use a background thread.
2016-07-01 12:06:55.153 ThaliTest[6114:19004487] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 12:,06:55.153 ThaliTest[6114:19004487] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore105710591","JXcore","Test",[]]

```
