#### Test 61432979dd0fe92_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61432979dd0fe92/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/85CC49C6-B02F-4B4D-B50C-DE10E561C4AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/85CC49C6-B02F-4B4D-B50C-DE10E561C4AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61432979dd0fe92/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61432979dd0fe92/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50659"
,(lldb)     command script import "/tmp/85CC49C6-B02F-4B4D-B50C-DE10E561C4AD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 11:41:51.442 ThaliTest[1033:1592164] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8A7B6F6C-641B-41D5-93B4-2AEC9E4A2252/Library/Cookies/Cookies.binarycookies
,2016-03-10 11:41:51.771 ThaliTest[1033:1592164] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 11:41:51.772 ThaliTest[1033:1592164] Multi-tasking -> Device: YES, App: YES
,2016-03-10 11:41:51.790 ThaliTest[1033:1592164] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 11:41:53.614 ThaliTest[1033:1592164] Using UIWebView
,2016-03-10 11:41:53.621 ThaliTest[1033:1592164] [CDVTimer][handleopenurl] 0.389993ms
,2016-03-10 11:41:53.629 ThaliTest[1033:1592164] [CDVTimer][intentandnavigationfilter] 7.379949ms
2016-03-10 11:41:53.630 ThaliTest[1033:1592164] [CDVTimer][gesturehandler] 0.340998ms
2016-03-10 11:41:53.630 ThaliTest[1033:1592164] [CDVTimer][TotalPluginS,tartup] 9.722054ms
,2016-03-10 11:42:00.597 ThaliTest[1033:1592164] Resetting plugins due to page load.
,2016-03-10 11:42:03.532 ThaliTest[1033:1592164] Finished load of: file:///var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/index.html
,2016-03-10 11:42:03.754 ThaliTest[1033:1592164] JXcore Cordova plugin initializing
,2016-03-10 11:42:03.755 ThaliTest[1033:1592396] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 11:42:11.065 ThaliTest[1033:1592396] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 11:42:11.066 ThaliTest[1033:1592396] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 11:42:11.066 ThaliTest[1033:1,592396] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 11:42:11.069 ThaliTest[1033:1592396] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E1D7CB1-F956-4930-A71B-84B7E3BE7649/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
