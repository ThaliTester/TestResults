#### Test 61362366a48397d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/83139757-9629-426F-8BE7-63FA4356E415/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/83139757-9629-426F-8BE7-63FA4356E415/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366a48397d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50904"
,(lldb)     command script import "/tmp/83139757-9629-426F-8BE7-63FA4356E415/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 13:35:25.242 ThaliTest[825:1192982] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C37D59CA-AEC4-49A4-8DC3-9598E62D97EB/Library/Cookies/Cookies.binarycookies
,2016-03-07 13:35:25.578 ThaliTest[825:1192982] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 13:35:25.579 ThaliTest[825:1192982] Multi-tasking -> Device: YES, App: YES
,2016-03-07 13:35:25.601 ThaliTest[825:1192982] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 13:35:27.425 ThaliTest[825:1192982] Using UIWebView
,2016-03-07 13:35:27.436 ThaliTest[825:1192982] [CDVTimer][handleopenurl] 0.476956ms
,2016-03-07 13:35:27.445 ThaliTest[825:1192982] [CDVTimer][intentandnavigationfilter] 8.293033ms
2016-03-07 13:35:27.446 ThaliTest[825:1192982] [CDVTimer][gesturehandler] 0.410020ms
2016-03-07 13:35:27.446 ThaliTest[825:1192982] [CDVTimer][TotalPluginStar,tup] 11.192024ms
,2016-03-07 13:35:34.485 ThaliTest[825:1192982] Resetting plugins due to page load.
,2016-03-07 13:35:38.474 ThaliTest[825:1192982] Finished load of: file:///var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/index.html
,2016-03-07 13:35:38.717 ThaliTest[825:1192982] JXcore Cordova plugin initializing
2016-03-07 13:35:38.719 ThaliTest[825:1193233] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 13:35:52.479 ThaliTest[825:1193233] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 13:35:52.480 ThaliTest[825:1193233] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 13:35:52.480 ThaliTest[825:1193,233] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 13:35:52.482 ThaliTest[825:1193233] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D20CD6D9-08A3-4B49-9811-1981606FBB0C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```
