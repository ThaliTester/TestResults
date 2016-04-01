#### Test 648991491c812df_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/442591A5-AE26-4C18-BD43-654DE74C63A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/442591A5-AE26-4C18-BD43-654DE74C63A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50130"
,(lldb)     command script import "/tmp/442591A5-AE26-4C18-BD43-654DE74C63A6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 09:11:04.681 ThaliTest[272:83599] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/493E8462-A3CB-4FF2-BB68-25EB2E7A4CDB/Library/Cookies/Cookies.binarycookies
,2016-04-01 09:11:05.034 ThaliTest[272:83599] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 09:11:05.035 ThaliTest[272:83599] Multi-tasking -> Device: YES, App: YES
,2016-04-01 09:11:05.052 ThaliTest[272:83599] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 09:11:07.192 ThaliTest[272:83599] Using UIWebView
,2016-04-01 09:11:07.199 ThaliTest[272:83599] [CDVTimer][handleopenurl] 0.442982ms
,2016-04-01 09:11:07.206 ThaliTest[272:83599] [CDVTimer][intentandnavigationfilter] 6.657004ms
,2016-04-01 09:11:07.207 ThaliTest[272:83599] [CDVTimer][gesturehandler] 0.306010ms
,2016-04-01 09:11:07.207 ThaliTest[272:83599] [CDVTimer][TotalPluginStartup] 9.092987ms
,2016-04-01 09:11:15.754 ThaliTest[272:83599] Resetting plugins due to page load.
,2016-04-01 09:11:19.815 ThaliTest[272:83599] Finished load of: file:///var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/index.html
,2016-04-01 09:11:20.017 ThaliTest[272:83599] JXcore Cordova plugin initializing
,2016-04-01 09:11:20.017 ThaliTest[272:83831] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 09:11:26.610 ThaliTest[272:83831] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 09:11:26.610 ThaliTest[272:83831] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-01 09:11:26.611 ThaliTest[272:83831] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-01 09:11:26.612 ThaliTest[272:83831] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7C6AD4B1-D8BF-4B44-B46D-138B948E0999/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-01 09:11:31.900 ThaliTest[272:83599] THREAD WARNING: ['JXcore'] took '5009.566162' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# name
,ok 1 sane
,# teardown
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
