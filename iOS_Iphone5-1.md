#### Test 625090942f85e77_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3DC73FCB-6A9D-4DC6-99BA-52335A1DF1C5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3DC73FCB-6A9D-4DC6-99BA-52335A1DF1C5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090942f85e77/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49543"
,(lldb)     command script import "/tmp/3DC73FCB-6A9D-4DC6-99BA-52335A1DF1C5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-11 16:56:59.544 ThaliTest[918:1891754] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB683413-4F23-4C1B-840A-4EE5251A6D07/Library/Cookies/Cookies.binarycookies
,2016-03-11 16:56:59.648 ThaliTest[918:1891754] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 16:56:59.652 ThaliTest[918:1891754] Multi-tasking -> Device: YES, App: YES
,2016-03-11 16:56:59.672 ThaliTest[918:1891754] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 16:57:01.744 ThaliTest[918:1891754] Using UIWebView
,2016-03-11 16:57:01.749 ThaliTest[918:1891754] [CDVTimer][handleopenurl] 0.290036ms
,2016-03-11 16:57:01.755 ThaliTest[918:1891754] [CDVTimer][intentandnavigationfilter] 5.384982ms
2016-03-11 16:57:01.755 ThaliTest[918:1891754] [CDVTimer][gesturehandler] 0.280023ms
2016-03-11 16:57:01.755 ThaliTest[918:1891754] [CDVTimer][TotalPluginStartup] 7.079005ms
,2016-03-11 16:57:10.856 ThaliTest[918:1891754] Resetting plugins due to page load.
,2016-03-11 16:57:14.435 ThaliTest[918:1891754] Finished load of: file:///var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/index.html
,2016-03-11 16:57:14.642 ThaliTest[918:1891754] JXcore Cordova plugin initializing
,2016-03-11 16:57:14.644 ThaliTest[918:1891939] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 16:57:36.485 ThaliTest[918:1891939] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 16:57:36.487 ThaliTest[918:1891939] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 16:57:36.487 ThaliTest[918:1891939] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 16:57:36.489 ThaliTest[918:1891939] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52C9B373-53DD-4638-B825-E63070796434/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
