#### Test 62947189e430ee9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D865FA9F-3EE5-48D4-9773-E0BE22CB8964/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D865FA9F-3EE5-48D4-9773-E0BE22CB8964/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49839"
,(lldb)     command script import "/tmp/D865FA9F-3EE5-48D4-9773-E0BE22CB8964/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 19:11:23.423 ThaliTest[1513:2391093] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F02EE886-0F96-47B6-9F05-EC3DA13687AB/Library/Cookies/Cookies.binarycookies
,2016-03-15 19:11:23.854 ThaliTest[1513:2391093] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 19:11:23.856 ThaliTest[1513:2391093] Multi-tasking -> Device: YES, App: YES
,2016-03-15 19:11:23.876 ThaliTest[1513:2391093] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 19:11:26.015 ThaliTest[1513:2391093] Using UIWebView
,2016-03-15 19:11:26.025 ThaliTest[1513:2391093] [CDVTimer][handleopenurl] 0.413001ms
,2016-03-15 19:11:26.032 ThaliTest[1513:2391093] [CDVTimer][intentandnavigationfilter] 6.707966ms
,2016-03-15 19:11:26.033 ThaliTest[1513:2391093] [CDVTimer][gesturehandler] 0.313044ms
,2016-03-15 19:11:26.033 ThaliTest[1513:2391093] [CDVTimer][TotalPluginStartup] 9.105980ms
,2016-03-15 19:11:32.965 ThaliTest[1513:2391093] Resetting plugins due to page load.
,2016-03-15 19:11:36.738 ThaliTest[1513:2391093] Finished load of: file:///var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/index.html
,2016-03-15 19:11:36.945 ThaliTest[1513:2391093] JXcore Cordova plugin initializing
,2016-03-15 19:11:36.946 ThaliTest[1513:2391338] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 19:11:48.640 ThaliTest[1513:2391338] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 19:11:48.640 ThaliTest[1513:2391338] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 19:11:48.640 ThaliTest[1513:2391338] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 19:11:48.641 ThaliTest[1513:2391338] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3EAE6C98-D376-4181-843A-E39A52D93FBA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
