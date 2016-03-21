#### Test 625481246894564_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2EA995DE-6FEB-4AFE-B775-7E59D69D9C8B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2EA995DE-6FEB-4AFE-B775-7E59D69D9C8B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54169"
,(lldb)     command script import "/tmp/2EA995DE-6FEB-4AFE-B775-7E59D69D9C8B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 13:02:15.826 ThaliTest[1909:3268486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/473E6ED2-DB6D-4AED-8F71-20730B59999C/Library/Cookies/Cookies.binarycookies
,2016-03-21 13:02:16.234 ThaliTest[1909:3268486] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 13:02:16.236 ThaliTest[1909:3268486] Multi-tasking -> Device: YES, App: YES
,2016-03-21 13:02:16.258 ThaliTest[1909:3268486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 13:02:17.772 ThaliTest[1909:3268486] Using UIWebView
,2016-03-21 13:02:17.777 ThaliTest[1909:3268486] [CDVTimer][handleopenurl] 0.277996ms
,2016-03-21 13:02:17.784 ThaliTest[1909:3268486] [CDVTimer][intentandnavigationfilter] 6.208003ms
2016-03-21 13:02:17.785 ThaliTest[1909:3268486] [CDVTimer][gesturehandler] 0.260055ms
2016-03-21 13:02:17.785 ThaliTest[1909:3268486] [CDVTimer][TotalPluginStartup] 7.982016ms
,2016-03-21 13:02:24.544 ThaliTest[1909:3268486] Resetting plugins due to page load.
,2016-03-21 13:02:28.396 ThaliTest[1909:3268486] Finished load of: file:///var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/index.html
,2016-03-21 13:02:28.648 ThaliTest[1909:3268486] JXcore Cordova plugin initializing
,2016-03-21 13:02:28.649 ThaliTest[1909:3268692] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 13:02:37.238 ThaliTest[1909:3268692] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:02:37.239 ThaliTest[1909:3268692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:02:37.239 ThaliTest[1909:3268692] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:02:37.241 ThaliTest[1909:3268692] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BE6D035-3445-4FE9-825C-4D225E6CC4B8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 13:02:44.234 ThaliTest[1909:3268486] THREAD WARNING: ['JXcore'] took '6622.427979' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
