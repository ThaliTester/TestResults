#### Test 62509094a319d1d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/69E0886B-48C2-4D26-A726-3B8D8BB869DE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/69E0886B-48C2-4D26-A726-3B8D8BB869DE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49316"
,(lldb)     command script import "/tmp/69E0886B-48C2-4D26-A726-3B8D8BB869DE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 15:35:18.685 ThaliTest[1188:1768373] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B2F1C4C1-7DB5-4D22-B080-990184A2D378/Library/Cookies/Cookies.binarycookies
,2016-03-11 15:35:19.082 ThaliTest[1188:1768373] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 15:35:19.084 ThaliTest[1188:1768373] Multi-tasking -> Device: YES, App: YES
,2016-03-11 15:35:19.102 ThaliTest[1188:1768373] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 15:35:20.872 ThaliTest[1188:1768373] Using UIWebView
,2016-03-11 15:35:20.879 ThaliTest[1188:1768373] [CDVTimer][handleopenurl] 0.433981ms
,2016-03-11 15:35:20.886 ThaliTest[1188:1768373] [CDVTimer][intentandnavigationfilter] 6.642997ms
,2016-03-11 15:35:20.887 ThaliTest[1188:1768373] [CDVTimer][gesturehandler] 0.308990ms
,2016-03-11 15:35:20.887 ThaliTest[1188:1768373] [CDVTimer][TotalPluginStartup] 9.000003ms
,2016-03-11 15:35:27.546 ThaliTest[1188:1768373] Resetting plugins due to page load.
,2016-03-11 15:35:30.648 ThaliTest[1188:1768373] Finished load of: file:///var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/index.html
,2016-03-11 15:35:30.840 ThaliTest[1188:1768373] JXcore Cordova plugin initializing
,2016-03-11 15:35:30.841 ThaliTest[1188:1768596] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-11 15:35:40.675 ThaliTest[1188:1768596] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 15:35:40.676 ThaliTest[1188:1768596] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-11 15:35:40.676 ThaliTest[1188:1768596] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-11 15:35:40.677 ThaliTest[1188:1768596] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81DD205F-28D4-4736-8C3B-04314E848A82/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
