#### Test 62509094b685d58_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D982F40B-753C-4CF3-96E5-6DFFDB79D94C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D982F40B-753C-4CF3-96E5-6DFFDB79D94C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51996"
,(lldb)     command script import "/tmp/D982F40B-753C-4CF3-96E5-6DFFDB79D94C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 12:27:51.521 ThaliTest[1621:2591475] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4096D5B6-65B8-44C4-886A-3EBAF11D8C9F/Library/Cookies/Cookies.binarycookies
,2016-03-17 12:27:51.922 ThaliTest[1621:2591475] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 12:27:51.923 ThaliTest[1621:2591475] Multi-tasking -> Device: YES, App: YES
,2016-03-17 12:27:51.946 ThaliTest[1621:2591475] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 12:27:53.763 ThaliTest[1621:2591475] Using UIWebView
,2016-03-17 12:27:53.770 ThaliTest[1621:2591475] [CDVTimer][handleopenurl] 0.497997ms
,2016-03-17 12:27:53.777 ThaliTest[1621:2591475] [CDVTimer][intentandnavigationfilter] 7.189989ms
2016-03-17 12:27:53.779 ThaliTest[1621:2591475] [CDVTimer][gesturehandler] 0.669003ms
2016-03-17 12:27:53.779 ThaliTest[1621:2591475] [CDVTimer][TotalPluginStartup] 10.253966ms
,2016-03-17 12:28:00.089 ThaliTest[1621:2591475] Resetting plugins due to page load.
,2016-03-17 12:28:03.047 ThaliTest[1621:2591475] Finished load of: file:///var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/index.html
,2016-03-17 12:28:03.275 ThaliTest[1621:2591475] JXcore Cordova plugin initializing
,2016-03-17 12:28:03.277 ThaliTest[1621:2591683] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 12:28:07.560 ThaliTest[1621:2591683] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 12:28:07.561 ThaliTest[1621:2591683] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 12:28:07.561 ThaliTest[1621:2591683] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 12:28:07.564 ThaliTest[1621:2591683] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BAA50068-8B09-4061-A36D-93B2F4693885/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 12:28:16.357 ThaliTest[1621:2591475] THREAD WARNING: ['JXcore'] took '6314.037109' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
