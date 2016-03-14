#### Test 625090944a5472b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3C9C532A-00C6-45FD-A0EF-98AE189AA0F3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3C9C532A-00C6-45FD-A0EF-98AE189AA0F3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090944a5472b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50148"
,(lldb)     command script import "/tmp/3C9C532A-00C6-45FD-A0EF-98AE189AA0F3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 08:49:43.876 ThaliTest[1341:2165274] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/63E64DFB-758C-4855-9858-6E7E66AB9405/Library/Cookies/Cookies.binarycookies
,2016-03-14 08:49:44.247 ThaliTest[1341:2165274] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 08:49:44.249 ThaliTest[1341:2165274] Multi-tasking -> Device: YES, App: YES
,2016-03-14 08:49:44.267 ThaliTest[1341:2165274] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 08:49:46.085 ThaliTest[1341:2165274] Using UIWebView
,2016-03-14 08:49:46.095 ThaliTest[1341:2165274] [CDVTimer][handleopenurl] 0.571012ms
,2016-03-14 08:49:46.102 ThaliTest[1341:2165274] [CDVTimer][intentandnavigationfilter] 6.621957ms
,2016-03-14 08:49:46.103 ThaliTest[1341:2165274] [CDVTimer][gesturehandler] 0.326037ms
,2016-03-14 08:49:46.103 ThaliTest[1341:2165274] [CDVTimer][TotalPluginStartup] 9.095967ms
,2016-03-14 08:49:52.596 ThaliTest[1341:2165274] Resetting plugins due to page load.
,2016-03-14 08:49:55.644 ThaliTest[1341:2165274] Finished load of: file:///var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/index.html
,2016-03-14 08:49:55.854 ThaliTest[1341:2165274] JXcore Cordova plugin initializing
,2016-03-14 08:49:55.855 ThaliTest[1341:2165518] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 08:50:07.525 ThaliTest[1341:2165518] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 08:50:07.525 ThaliTest[1341:2165518] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-14 08:50:07.525 ThaliTest[1341:2165518] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 08:50:07.526 ThaliTest[1341:2165518] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/09DE6D20-AAC0-4D5D-BEE5-D76CB2F104EA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
