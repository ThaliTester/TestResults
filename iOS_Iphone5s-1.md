#### Test 62509094e6af764_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/59187D8F-525E-406C-BA1F-43B97A027001/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/59187D8F-525E-406C-BA1F-43B97A027001/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094e6af764/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49669"
,(lldb)     command script import "/tmp/59187D8F-525E-406C-BA1F-43B97A027001/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 12:19:06.766 ThaliTest[1161:1752351] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/66EBE338-0E1F-44E6-B1FE-FE6F057A03BB/Library/Cookies/Cookies.binarycookies
,2016-03-11 12:19:07.136 ThaliTest[1161:1752351] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 12:19:07.137 ThaliTest[1161:1752351] Multi-tasking -> Device: YES, App: YES
,2016-03-11 12:19:07.161 ThaliTest[1161:1752351] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 12:19:08.916 ThaliTest[1161:1752351] Using UIWebView
,2016-03-11 12:19:08.927 ThaliTest[1161:1752351] [CDVTimer][handleopenurl] 0.479043ms
,2016-03-11 12:19:08.936 ThaliTest[1161:1752351] [CDVTimer][intentandnavigationfilter] 8.145988ms
2016-03-11 12:19:08.937 ThaliTest[1161:1752351] [CDVTimer][gesturehandler] 0.393987ms
2016-03-11 12:19:08.937 ThaliTest[1161:1752351] [CDVTimer][TotalPluginS,tartup] 11.062980ms
,2016-03-11 12:19:15.092 ThaliTest[1161:1752351] Resetting plugins due to page load.
,2016-03-11 12:19:18.228 ThaliTest[1161:1752351] Finished load of: file:///var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/index.html
,2016-03-11 12:19:18.557 ThaliTest[1161:1752351] JXcore Cordova plugin initializing
,2016-03-11 12:19:18.559 ThaliTest[1161:1752551] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 12:19:32.573 ThaliTest[1161:1752551] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 12:19:32.574 ThaliTest[1161:1752551] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 12:19:32.574 ThaliTest[1161:1,752551] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 12:19:32.575 ThaliTest[1161:1752551] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1539B2D4-F815-4CFB-BAB8-D95C9D41532F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
