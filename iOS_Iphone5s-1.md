#### Test 721454319a152ff_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/73345BA3-F108-493E-AE73-8FBFD1970EE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/73345BA3-F108-493E-AE73-8FBFD1970EE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/721454319a152ff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50370"
,(lldb)     command script import "/tmp/73345BA3-F108-493E-AE73-8FBFD1970EE1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 15:04:17.990 ThaliTest[6408:19361045] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CAB0255D-F825-4C48-85BB-2287C118833D/Library/Cookies/Cookies.binarycookies
,2016-07-05 15:04:18.243 ThaliTest[6408:19361045] Apache Cordova native platform version 4.1.1 is starting.
2016-07-05 15:04:18.244 ThaliTest[6408:19361045] Multi-tasking -> Device: YES, App: YES
,2016-07-05 15:04:18.262 ThaliTest[6408:19361045] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 15:04:19.083 ThaliTest[6408:19361045] Using UIWebView
,2016-07-05 15:04:19.087 ThaliTest[6408:19361045] [CDVTimer][handleopenurl] 0.167012ms
,2016-07-05 15:04:19.091 ThaliTest[6408:19361045] [CDVTimer][intentandnavigationfilter] 3.864050ms
2016-07-05 15:04:19.091 ThaliTest[6408:19361045] [CDVTimer][gesturehandler] 0.158012ms
2016-07-05 15:04:19.092 ThaliTest[6408:19361045] [CDVTimer][TotalPlug,inStartup] 4.836977ms
,2016-07-05 15:04:22.364 ThaliTest[6408:19361045] Resetting plugins due to page load.
,2016-07-05 15:04:23.915 ThaliTest[6408:19361045] Finished load of: file:///var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/index.html
,2016-07-05 15:04:24.104 ThaliTest[6408:19361045] JXcore Cordova plugin initializing
2016-07-05 15:04:24.105 ThaliTest[6408:19361229] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-05 15:04:32.708 ThaliTest[6408:19361229] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-05 15:04:32.709 ThaliTest[6408:19361229] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-05 15:04:32.710 ThaliTest[6408:19361229] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-05 15:04:32.713 ThaliTest[6408:19361229] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E0E8751-3235-474F-8728-BA7A95C23730/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
