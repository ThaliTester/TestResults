#### Test 62509094e6af764_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C7244A46-0E32-4AF8-8BC9-CB39C7A9B102/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C7244A46-0E32-4AF8-8BC9-CB39C7A9B102/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49667"
,(lldb)     command script import "/tmp/C7244A46-0E32-4AF8-8BC9-CB39C7A9B102/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 12:19:04.565 ThaliTest[1126:1710416] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/23AC6B07-D6C0-40A5-A993-91A85551ECA5/Library/Cookies/Cookies.binarycookies
,2016-03-11 12:19:04.910 ThaliTest[1126:1710416] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 12:19:04.911 ThaliTest[1126:1710416] Multi-tasking -> Device: YES, App: YES
,2016-03-11 12:19:04.934 ThaliTest[1126:1710416] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 12:19:06.673 ThaliTest[1126:1710416] Using UIWebView
,2016-03-11 12:19:06.680 ThaliTest[1126:1710416] [CDVTimer][handleopenurl] 0.388980ms
,2016-03-11 12:19:06.688 ThaliTest[1126:1710416] [CDVTimer][intentandnavigationfilter] 7.269025ms
2016-03-11 12:19:06.689 ThaliTest[1126:1710416] [CDVTimer][gesturehandler] 0.371993ms
2016-03-11 12:19:06.689 ThaliTest[1126:1710416] [CDVTimer][TotalPluginStartup] 9.748995ms
,2016-03-11 12:19:12.975 ThaliTest[1126:1710416] Resetting plugins due to page load.
,2016-03-11 12:19:16.020 ThaliTest[1126:1710416] Finished load of: file:///var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/index.html
,2016-03-11 12:19:16.252 ThaliTest[1126:1710416] JXcore Cordova plugin initializing
2016-03-11 12:19:16.253 ThaliTest[1126:1710624] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 12:19:28.766 ThaliTest[1126:1710624] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 12:19:28.767 ThaliTest[1126:1710624] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 12:19:28.767 ThaliTest[1126:1710624] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 12:19:28.768 ThaliTest[1126:1710624] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C5CEEE3-70EB-49A8-9560-B8CB52084E3B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
