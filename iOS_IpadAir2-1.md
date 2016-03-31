#### Test 648099369ce4518_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/379F00E3-E996-4A0A-B5FE-D27B6B4650C6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/379F00E3-E996-4A0A-B5FE-D27B6B4650C6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49974"
,(lldb)     command script import "/tmp/379F00E3-E996-4A0A-B5FE-D27B6B4650C6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 18:03:54.584 ThaliTest[232:8921] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC5B11DC-B642-40D7-9E8B-4AB16B736B61/Library/Cookies/Cookies.binarycookies
,2016-03-31 18:03:55.024 ThaliTest[232:8921] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 18:03:55.025 ThaliTest[232:8921] Multi-tasking -> Device: YES, App: YES
,2016-03-31 18:03:55.043 ThaliTest[232:8921] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 18:03:57.407 ThaliTest[232:8921] Using UIWebView
,2016-03-31 18:03:57.414 ThaliTest[232:8921] [CDVTimer][handleopenurl] 0.425041ms
,2016-03-31 18:03:57.422 ThaliTest[232:8921] [CDVTimer][intentandnavigationfilter] 7.956028ms
,2016-03-31 18:03:57.423 ThaliTest[232:8921] [CDVTimer][gesturehandler] 0.382006ms
,2016-03-31 18:03:57.424 ThaliTest[232:8921] [CDVTimer][TotalPluginStartup] 10.664046ms
,2016-03-31 18:04:05.277 ThaliTest[232:8921] Resetting plugins due to page load.
,2016-03-31 18:04:09.481 ThaliTest[232:8921] Finished load of: file:///var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/index.html
,2016-03-31 18:04:09.698 ThaliTest[232:8921] JXcore Cordova plugin initializing
,2016-03-31 18:04:09.699 ThaliTest[232:9159] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 18:04:16.227 ThaliTest[232:9159] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 18:04:16.228 ThaliTest[232:9159] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 18:04:16.228 ThaliTest[232:9159] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 18:04:16.230 ThaliTest[232:9159] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C070C849-73D1-42E5-9829-DC6BB830F9AF/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 18:04:21.516 ThaliTest[232:8921] THREAD WARNING: ['JXcore'] took '5010.940186' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
