#### Test 757892686fd65a6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F514CACA-4291-4A64-984D-91AD8177794B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F514CACA-4291-4A64-984D-91AD8177794B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65199"
,(lldb)     command script import "/tmp/F514CACA-4291-4A64-984D-91AD8177794B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 08:55:43.261 ThaliTest[6094:18978930] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/93CFADA2-64D2-407D-A26F-8BB57708F01B/Library/Cookies/Cookies.binarycookies
,2016-07-01 08:55:43.550 ThaliTest[6094:18978930] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 08:55:43.551 ThaliTest[6094:18978930] Multi-tasking -> Device: YES, App: YES
,2016-07-01 08:55:43.574 ThaliTest[6094:18978930] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 08:55:44.503 ThaliTest[6094:18978930] Using UIWebView
2016-07-01 08:55:44.507 ThaliTest[6094:18978930] [CDVTimer][handleopenurl] 0.229001ms
2016-07-01 08:55:44.510 ThaliTest[6094:18978930] [CDVTimer][intentandnavigationfilter] 3.098011ms
2016,-07-01 08:55:44.510 ThaliTest[6094:18978930] [CDVTimer][gesturehandler] 0.142038ms
2016-07-01 08:55:44.510 ThaliTest[6094:18978930] [CDVTimer][TotalPluginStartup] 4.115999ms
,2016-07-01 08:55:48.200 ThaliTest[6094:18978930] Resetting plugins due to page load.
,2016-07-01 08:55:49.857 ThaliTest[6094:18978930] Finished load of: file:///var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/index.html
,2016-07-01 08:55:50.081 ThaliTest[6094:18978930] JXcore Cordova plugin initializing
,2016-07-01 08:55:50.082 ThaliTest[6094:18979078] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 08:56:06.624 ThaliTest[6094:18979078] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-01 08:56:06.626 ThaliTest[6094:18979078] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-01 08:56:06.627 ThaliTest[6094:18979078] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 08:56:06.632 ThaliTest[6094:18979078] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-07-01 08:56:07.513 ThaliTest[6094:18978930] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 08:56:07.513 ThaliTest[6094:18978930] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore925279481","JXcore","Test",[]],
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/583D646D-3261-4730-AF87-C34B6B93A34A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
