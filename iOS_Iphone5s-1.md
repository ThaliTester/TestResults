#### Test 63036995fb62ea7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7F5A5527-F4D3-471C-ACD2-745181BC0ED7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7F5A5527-F4D3-471C-ACD2-745181BC0ED7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51081"
,(lldb)     command script import "/tmp/7F5A5527-F4D3-471C-ACD2-745181BC0ED7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 07:10:10.633 ThaliTest[1624:2626234] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4424BFA6-5C7F-4BC3-803D-5E33F9F4B997/Library/Cookies/Cookies.binarycookies
,2016-03-17 07:10:11.018 ThaliTest[1624:2626234] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 07:10:11.019 ThaliTest[1624:2626234] Multi-tasking -> Device: YES, App: YES
,2016-03-17 07:10:11.043 ThaliTest[1624:2626234] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 07:10:12.935 ThaliTest[1624:2626234] Using UIWebView
,2016-03-17 07:10:12.943 ThaliTest[1624:2626234] [CDVTimer][handleopenurl] 0.419974ms
,2016-03-17 07:10:12.952 ThaliTest[1624:2626234] [CDVTimer][intentandnavigationfilter] 8.809030ms
2016-03-17 07:10:12.953 ThaliTest[1624:2626234] [CDVTimer][gesturehandler] 0.418007ms
2016-03-17 07:10:12.953 ThaliTest[1624:2626234] [CDVTimer][TotalPluginStartup] 11.433005ms
,2016-03-17 07:10:19.990 ThaliTest[1624:2626234] Resetting plugins due to page load.
,2016-03-17 07:10:23.981 ThaliTest[1624:2626234] Finished load of: file:///var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/index.html
,2016-03-17 07:10:24.226 ThaliTest[1624:2626234] JXcore Cordova plugin initializing
,2016-03-17 07:10:24.228 ThaliTest[1624:2626465] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-17 07:10:39.805 ThaliTest[1624:2626465] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 07:10:39.806 ThaliTest[1624:2626465] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 07:10:39.806 ThaliTest[1624:2626465] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 07:10:39.808 ThaliTest[1624:2626465] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/36BD1142-81B5-4C5B-AD61-43F655656DA7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
