#### Test 62560673e7cbba2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62560673e7cbba2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BDE48879-75C9-4A3F-B198-CEA87B4D3F84/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BDE48879-75C9-4A3F-B198-CEA87B4D3F84/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/62560673e7cbba2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62560673e7cbba2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49699"
,(lldb)     command script import "/tmp/BDE48879-75C9-4A3F-B198-CEA87B4D3F84/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-11 17:26:54.008 ThaliTest[1204:1788350] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/92DC2F09-0C65-432F-8FB9-0A6D2FF16A56/Library/Cookies/Cookies.binarycookies
,2016-03-11 17:26:54.421 ThaliTest[1204:1788350] Apache Cordova native platform version 4.0.1 is starting.
2016-03-11 17:26:54.422 ThaliTest[1204:1788350] Multi-tasking -> Device: YES, App: YES
,2016-03-11 17:26:54.445 ThaliTest[1204:1788350] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 17:26:56.237 ThaliTest[1204:1788350] Using UIWebView
,2016-03-11 17:26:56.248 ThaliTest[1204:1788350] [CDVTimer][handleopenurl] 0.506997ms
,2016-03-11 17:26:56.257 ThaliTest[1204:1788350] [CDVTimer][intentandnavigationfilter] 8.076012ms
2016-03-11 17:26:56.258 ThaliTest[1204:1788350] [CDVTimer][gesturehandler] 0.385046ms
2016-03-11 17:26:56.258 ThaliTest[1204:1788350] [CDVTimer][TotalPluginS,tartup] 11.022985ms
,2016-03-11 17:27:03.299 ThaliTest[1204:1788350] Resetting plugins due to page load.
,2016-03-11 17:27:07.315 ThaliTest[1204:1788350] Finished load of: file:///var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/index.html
,2016-03-11 17:27:07.568 ThaliTest[1204:1788350] JXcore Cordova plugin initializing
,2016-03-11 17:27:07.569 ThaliTest[1204:1788575] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 17:27:21.574 ThaliTest[1204:1788575] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 17:27:21.575 ThaliTest[1204:1788575] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 17:27:21.575 ThaliTest[1204:1,788575] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

2016-03-11 17:27:21.576 ThaliTest[1204:1788575] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/936677A6-681C-49E4-AFBF-CDB44107B2B8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
