#### Test 757892682551a10_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B459FB64-B68A-4D3D-9D40-EB5ECA316CBF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B459FB64-B68A-4D3D-9D40-EB5ECA316CBF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65023"
,(lldb)     command script import "/tmp/B459FB64-B68A-4D3D-9D40-EB5ECA316CBF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 13:50:06.048 ThaliTest[6058:18844260] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F765571D-9A02-4332-90CB-D63E6C183285/Library/Cookies/Cookies.binarycookies
,2016-06-30 13:50:06.459 ThaliTest[6058:18844260] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 13:50:06.461 ThaliTest[6058:18844260] Multi-tasking -> Device: YES, App: YES
,2016-06-30 13:50:06.482 ThaliTest[6058:18844260] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 13:50:08.444 ThaliTest[6058:18844260] Using UIWebView
,2016-06-30 13:50:08.451 ThaliTest[6058:18844260] [CDVTimer][handleopenurl] 0.449002ms
,2016-06-30 13:50:08.459 ThaliTest[6058:18844260] [CDVTimer][intentandnavigationfilter] 7.463992ms
2016-06-30 13:50:08.460 ThaliTest[6058:18844260] [CDVTimer][gesturehandler] 0.330985ms
2016-06-30 13:50:08.460 ThaliTest[6058:18844260] [CDVTimer][TotalPluginStartup] 9.964049ms
,2016-06-30 13:50:15.844 ThaliTest[6058:18844260] Resetting plugins due to page load.
,2016-06-30 13:50:19.627 ThaliTest[6058:18844260] Finished load of: file:///var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/index.html
,2016-06-30 13:50:19.849 ThaliTest[6058:18844260] JXcore Cordova plugin initializing
,2016-06-30 13:50:19.962 ThaliTest[6058:18844485] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 13:50:27.345 ThaliTest[6058:18844485] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 13:50:27.345 ThaliTest[6058:18844485] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 13:50:27.345 ThaliTest[6058:18844485] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 13:50:27.347 ThaliTest[6058:18844485] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2C9DD5F9-FEFA-4B9B-968A-B7E90E5E5909/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 13:50:33.396 ThaliTest[6058:18844260] THREAD WARNING: ['JXcore'] took '5739.601074' ms. Plugin should use a background thread.
2016-06-30 13:50:33.396 ThaliTest[6058:18844260] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-06-30 13:50:33.396 ThaliTest[6058:18844260] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1093740124","JXcore","Test",[]]

```
