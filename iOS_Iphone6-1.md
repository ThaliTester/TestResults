#### Test 62509094cfda267_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6728C740-B040-4571-A508-BBA0C5E02D35/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6728C740-B040-4571-A508-BBA0C5E02D35/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50293"
,(lldb)     command script import "/tmp/6728C740-B040-4571-A508-BBA0C5E02D35/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 09:51:05.652 ThaliTest[1301:2123485] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/811494BC-D296-455D-8F1D-BACE4F62A222/Library/Cookies/Cookies.binarycookies
,2016-03-14 09:51:06.076 ThaliTest[1301:2123485] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 09:51:06.078 ThaliTest[1301:2123485] Multi-tasking -> Device: YES, App: YES
,2016-03-14 09:51:06.101 ThaliTest[1301:2123485] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 09:51:07.914 ThaliTest[1301:2123485] Using UIWebView
,2016-03-14 09:51:07.922 ThaliTest[1301:2123485] [CDVTimer][handleopenurl] 0.416994ms
,2016-03-14 09:51:07.934 ThaliTest[1301:2123485] [CDVTimer][intentandnavigationfilter] 11.511028ms
2016-03-14 09:51:07.935 ThaliTest[1301:2123485] [CDVTimer][gesturehandler] 0.524044ms
2016-03-14 09:51:07.936 ThaliTest[1301:2123485] [CDVTimer][TotalPlugin,Startup] 14.775991ms
,2016-03-14 09:51:14.774 ThaliTest[1301:2123485] Resetting plugins due to page load.
,2016-03-14 09:51:18.095 ThaliTest[1301:2123485] Finished load of: file:///var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/index.html
,2016-03-14 09:51:18.384 ThaliTest[1301:2123485] JXcore Cordova plugin initializing
2016-03-14 09:51:18.385 ThaliTest[1301:2123717] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 09:51:30.845 ThaliTest[1301:2123717] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 09:51:30.846 ThaliTest[1301:2123717] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 09:51:30.846 ThaliTest[1301:2,123717] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

2016-03-14 09:51:30.847 ThaliTest[1301:2123717] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F615D597-2C0B-4192-8CE8-D31904EAE02E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
