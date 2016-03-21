#### Test 635253937ae73fc_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5FDCF827-12F8-4AE0-860B-C3F2847BE6CC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5FDCF827-12F8-4AE0-860B-C3F2847BE6CC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53637"
,(lldb)     command script import "/tmp/5FDCF827-12F8-4AE0-860B-C3F2847BE6CC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 08:35:33.290 ThaliTest[1896:3239554] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF46F1A9-E7C9-45EA-ABA7-96BBAB3DA0A3/Library/Cookies/Cookies.binarycookies
,2016-03-21 08:35:33.735 ThaliTest[1896:3239554] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 08:35:33.737 ThaliTest[1896:3239554] Multi-tasking -> Device: YES, App: YES
,2016-03-21 08:35:33.761 ThaliTest[1896:3239554] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 08:35:35.704 ThaliTest[1896:3239554] Using UIWebView
,2016-03-21 08:35:35.714 ThaliTest[1896:3239554] [CDVTimer][handleopenurl] 0.562966ms
,2016-03-21 08:35:35.723 ThaliTest[1896:3239554] [CDVTimer][intentandnavigationfilter] 8.086026ms
2016-03-21 08:35:35.724 ThaliTest[1896:3239554] [CDVTimer][gesturehandler] 0.409007ms
2016-03-21 08:35:35.724 ThaliTest[1896:3239554] [CDVTimer][TotalPluginS,tartup] 10.945022ms
,2016-03-21 08:35:42.596 ThaliTest[1896:3239554] Resetting plugins due to page load.
,2016-03-21 08:35:46.135 ThaliTest[1896:3239554] Finished load of: file:///var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/index.html
,2016-03-21 08:35:46.382 ThaliTest[1896:3239554] JXcore Cordova plugin initializing
2016-03-21 08:35:46.385 ThaliTest[1896:3239803] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 08:35:51.542 ThaliTest[1896:3239803] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 08:35:51.543 ThaliTest[1896:3239803] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 08:35:51.543 ThaliTest[1896:3,239803] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 08:35:51.547 ThaliTest[1896:3239803] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AF9E5624-B472-4D80-83CC-DD0FFC93C5A7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 08:36:01.959 ThaliTest[1896:3239554] THREAD WARNING: ['JXcore'] took '7472.300049' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
