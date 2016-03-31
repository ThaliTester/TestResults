#### Test 645312549bcf247_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/44137557-0185-4298-8C54-901FF3D25F65/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/44137557-0185-4298-8C54-901FF3D25F65/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49491"
,(lldb)     command script import "/tmp/44137557-0185-4298-8C54-901FF3D25F65/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 01:48:06.579 ThaliTest[2526:4719612] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3BCA3612-199D-4968-A012-A9424E687EC4/Library/Cookies/Cookies.binarycookies
,2016-03-31 01:48:06.979 ThaliTest[2526:4719612] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 01:48:06.980 ThaliTest[2526:4719612] Multi-tasking -> Device: YES, App: YES
,2016-03-31 01:48:06.999 ThaliTest[2526:4719612] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 01:48:09.391 ThaliTest[2526:4719612] Using UIWebView
,2016-03-31 01:48:09.398 ThaliTest[2526:4719612] [CDVTimer][handleopenurl] 0.401020ms
,2016-03-31 01:48:09.406 ThaliTest[2526:4719612] [CDVTimer][intentandnavigationfilter] 6.798983ms
2016-03-31 01:48:09.406 ThaliTest[2526:4719612] [CDVTimer][gesturehandler] 0.320971ms
,2016-03-31 01:48:09.407 ThaliTest[2526:4719612] [CDVTimer][TotalPluginStartup] 9.209037ms
,2016-03-31 01:48:18.211 ThaliTest[2526:4719612] Resetting plugins due to page load.
,2016-03-31 01:48:22.353 ThaliTest[2526:4719612] Finished load of: file:///var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/index.html
,2016-03-31 01:48:22.578 ThaliTest[2526:4719612] JXcore Cordova plugin initializing
,2016-03-31 01:48:22.579 ThaliTest[2526:4719863] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 01:48:29.100 ThaliTest[2526:4719863] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 01:48:29.101 ThaliTest[2526:4719863] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 01:48:29.101 ThaliTest[2526:4719863] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 01:48:29.103 ThaliTest[2526:4719863] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6459E035-665D-43D7-8E56-7EBE0DDBBC0A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 01:48:34.327 ThaliTest[2526:4719612] THREAD WARNING: ['JXcore'] took '4949.829102' ms. Plugin should use a background thread.

```
