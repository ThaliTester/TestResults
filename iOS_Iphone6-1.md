#### Test 625481245382a4d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B23A5B04-D48D-4A56-B41F-9B82F401CB1E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B23A5B04-D48D-4A56-B41F-9B82F401CB1E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53225"
,(lldb)     command script import "/tmp/B23A5B04-D48D-4A56-B41F-9B82F401CB1E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 12:39:02.163 ThaliTest[1801:3033324] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/767A05E3-FE70-40DA-A33A-DB0052352A0B/Library/Cookies/Cookies.binarycookies
,2016-03-20 12:39:02.528 ThaliTest[1801:3033324] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 12:39:02.529 ThaliTest[1801:3033324] Multi-tasking -> Device: YES, App: YES
,2016-03-20 12:39:02.551 ThaliTest[1801:3033324] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 12:39:04.347 ThaliTest[1801:3033324] Using UIWebView
,2016-03-20 12:39:04.354 ThaliTest[1801:3033324] [CDVTimer][handleopenurl] 0.647962ms
,2016-03-20 12:39:04.363 ThaliTest[1801:3033324] [CDVTimer][intentandnavigationfilter] 7.873952ms
2016-03-20 12:39:04.364 ThaliTest[1801:3033324] [CDVTimer][gesturehandler] 0.407994ms
2016-03-20 12:39:04.364 ThaliTest[1801:3033324] [CDVTimer][TotalPluginStartup] 10.600030ms
,2016-03-20 12:39:11.519 ThaliTest[1801:3033324] Resetting plugins due to page load.
,2016-03-20 12:39:15.215 ThaliTest[1801:3033324] Finished load of: file:///var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/index.html
,2016-03-20 12:39:15.436 ThaliTest[1801:3033324] JXcore Cordova plugin initializing
,2016-03-20 12:39:15.438 ThaliTest[1801:3033707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 12:39:22.711 ThaliTest[1801:3033707] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:39:22.711 ThaliTest[1801:3033707] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:39:22.711 ThaliTest[1801:3,033707] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:39:22.714 ThaliTest[1801:3033707] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F1591144-64A3-4EB0-8F9D-E58628BC26D9/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 12:39:28.609 ThaliTest[1801:3033324] THREAD WARNING: ['JXcore'] took '5578.878906' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
