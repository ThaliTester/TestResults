#### Test 63998117de3e24f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63998117de3e24f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4B6053C1-1674-49ED-A736-6C22EC5F909A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4B6053C1-1674-49ED-A736-6C22EC5F909A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63998117de3e24f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63998117de3e24f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56474"
,(lldb)     command script import "/tmp/4B6053C1-1674-49ED-A736-6C22EC5F909A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 16:20:38.183 ThaliTest[2450:4512128] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED5A253D-55B7-4554-9ED8-35338D43101B/Library/Cookies/Cookies.binarycookies
,2016-03-29 16:20:38.655 ThaliTest[2450:4512128] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 16:20:38.656 ThaliTest[2450:4512128] Multi-tasking -> Device: YES, App: YES
,2016-03-29 16:20:38.675 ThaliTest[2450:4512128] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 16:20:40.943 ThaliTest[2450:4512128] Using UIWebView
,2016-03-29 16:20:40.951 ThaliTest[2450:4512128] [CDVTimer][handleopenurl] 0.432014ms
,2016-03-29 16:20:40.959 ThaliTest[2450:4512128] [CDVTimer][intentandnavigationfilter] 7.188022ms
,2016-03-29 16:20:40.960 ThaliTest[2450:4512128] [CDVTimer][gesturehandler] 0.340998ms
2016-03-29 16:20:40.960 ThaliTest[2450:4512128] [CDVTimer][TotalPluginStartup] 10.021985ms
,2016-03-29 16:20:49.093 ThaliTest[2450:4512128] Resetting plugins due to page load.
,2016-03-29 16:20:53.141 ThaliTest[2450:4512128] Finished load of: file:///var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/index.html
,2016-03-29 16:20:53.363 ThaliTest[2450:4512128] JXcore Cordova plugin initializing
,2016-03-29 16:20:53.364 ThaliTest[2450:4512364] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 16:20:59.816 ThaliTest[2450:4512364] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 16:20:59.816 ThaliTest[2450:4512364] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 16:20:59.817 ThaliTest[2450:4512364] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 16:20:59.818 ThaliTest[2450:4512364] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/623B7461-92C8-4AC2-A692-1C0F5B09B4A2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-29 16:21:05.041 ThaliTest[2450:4512128] THREAD WARNING: ['JXcore'] took '4949.964111' ms. Plugin should use a background thread.

```
