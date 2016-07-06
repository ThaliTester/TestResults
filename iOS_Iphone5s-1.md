#### Test 7214543121d4f5c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/072FE83F-3C02-4F11-A356-5B454BB5BB62/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/072FE83F-3C02-4F11-A356-5B454BB5BB62/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app"
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543121d4f5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50878"
,(lldb)     command script import "/tmp/072FE83F-3C02-4F11-A356-5B454BB5BB62/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 13:52:11.909 ThaliTest[6477:19509967] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77C67CDB-28B9-408D-A8C0-ABB5420001E6/Library/Cookies/Cookies.binarycookies
,2016-07-06 13:52:12.165 ThaliTest[6477:19509967] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 13:52:12.166 ThaliTest[6477:19509967] Multi-tasking -> Device: YES, App: YES
,2016-07-06 13:52:12.185 ThaliTest[6477:19509967] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 13:52:13.000 ThaliTest[6477:19509967] Using UIWebView
,2016-07-06 13:52:13.003 ThaliTest[6477:19509967] [CDVTimer][handleopenurl] 0.182033ms
,2016-07-06 13:52:13.006 ThaliTest[6477:19509967] [CDVTimer][intentandnavigationfilter] 2.894998ms
2016-07-06 13:52:13.007 ThaliTest[6477:19509967] [CDVTimer][gesturehandler] 0.133038ms
2016-07-06 13:52:13.007 ThaliTest[6477:19509967] [CDVTimer][TotalPlug,inStartup] 3.920019ms
,2016-07-06 13:52:16.257 ThaliTest[6477:19509967] Resetting plugins due to page load.
,2016-07-06 13:52:17.741 ThaliTest[6477:19509967] Finished load of: file:///var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/index.html
,2016-07-06 13:52:17.918 ThaliTest[6477:19509967] JXcore Cordova plugin initializing
,2016-07-06 13:52:18.013 ThaliTest[6477:19510126] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 13:52:26.508 ThaliTest[6477:19510126] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-06 13:52:26.509 ThaliTest[6477:19510126] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-06 13:52:26.509 ThaliTest[6477:19510126] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-06 13:52:26.512 ThaliTest[6477:19510126] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4952CF-3E51-484B-A086-7C44FFD8E49A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
