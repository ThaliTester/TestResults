#### Test 62548124b8ccb9f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1CC4EDE8-226B-47F3-8652-EB0CE35D2DF1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1CC4EDE8-226B-47F3-8652-EB0CE35D2DF1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52744"
,(lldb)     command script import "/tmp/1CC4EDE8-226B-47F3-8652-EB0CE35D2DF1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-18 17:15:02.148 ThaliTest[1764:2833872] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3CFE5B69-BF56-4173-B3CA-D0AC64523A1C/Library/Cookies/Cookies.binarycookies
,2016-03-18 17:15:02.513 ThaliTest[1764:2833872] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-18 17:15:02.514 ThaliTest[1764:2833872] Multi-tasking -> Device: YES, App: YES
,2016-03-18 17:15:02.533 ThaliTest[1764:2833872] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-18 17:15:04.456 ThaliTest[1764:2833872] Using UIWebView
,2016-03-18 17:15:04.462 ThaliTest[1764:2833872] [CDVTimer][handleopenurl] 0.401020ms
,2016-03-18 17:15:04.470 ThaliTest[1764:2833872] [CDVTimer][intentandnavigationfilter] 7.372022ms
,2016-03-18 17:15:04.471 ThaliTest[1764:2833872] [CDVTimer][gesturehandler] 0.344038ms
2016-03-18 17:15:04.471 ThaliTest[1764:2833872] [CDVTimer][TotalPluginStartup] 9.725034ms
,2016-03-18 17:15:12.125 ThaliTest[1764:2833872] Resetting plugins due to page load.
,2016-03-18 17:15:15.816 ThaliTest[1764:2833872] Finished load of: file:///var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/index.html
,2016-03-18 17:15:16.023 ThaliTest[1764:2833872] JXcore Cordova plugin initializing
,2016-03-18 17:15:16.024 ThaliTest[1764:2834094] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-18 17:15:22.481 ThaliTest[1764:2834094] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-18 17:15:22.481 ThaliTest[1764:2834094] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:15:22.482 ThaliTest[1764:2834094] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:15:22.483 ThaliTest[1764:2834094] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2354B425-875C-413D-8D36-464CABBF8650/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-18 17:15:27.696 ThaliTest[1764:2833872] THREAD WARNING: ['JXcore'] took '4934.601074' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
