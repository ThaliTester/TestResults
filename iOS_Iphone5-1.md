#### Test 757892680c366d1_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C2C7911B-D566-4670-84BF-2DDD5C610A1A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C2C7911B-D566-4670-84BF-2DDD5C610A1A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65505"
,(lldb)     command script import "/tmp/C2C7911B-D566-4670-84BF-2DDD5C610A1A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 12:05:41.171 ThaliTest[4518:19855265] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/163EC9AB-95FE-4A2F-9AC5-2DF0682E04E9/Library/Cookies/Cookies.binarycookies
,2016-07-01 12:05:41.282 ThaliTest[4518:19855265] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 12:05:41.284 ThaliTest[4518:19855265] Multi-tasking -> Device: YES, App: YES
,2016-07-01 12:05:41.301 ThaliTest[4518:19855265] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 12:05:42.451 ThaliTest[4518:19855265] Using UIWebView
,2016-07-01 12:05:42.455 ThaliTest[4518:19855265] [CDVTimer][handleopenurl] 0.285983ms
,2016-07-01 12:05:42.461 ThaliTest[4518:19855265] [CDVTimer][intentandnavigationfilter] 4.900038ms
2016-07-01 12:05:42.461 ThaliTest[4518:19855265] [CDVTimer][gesturehandler] 0.218034ms
2016-07-01 12:05:42.461 ThaliTest[4518:19855265] [CDVTimer][TotalPluginStartup] 6.305039ms
,2016-07-01 12:05:47.423 ThaliTest[4518:19855265] Resetting plugins due to page load.
,2016-07-01 12:05:49.652 ThaliTest[4518:19855265] Finished load of: file:///var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/index.html
,2016-07-01 12:05:49.853 ThaliTest[4518:19855265] JXcore Cordova plugin initializing
,2016-07-01 12:05:49.855 ThaliTest[4518:19855407] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 12:06:04.966 ThaliTest[4518:19855407] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 12:06:04.968 ThaliTest[4518:19855407] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 12:06:04.969 ThaliTest[4518,:19855407] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-01 12:06:04.971 ThaliTest[4518:19855407] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-07-01 12:06:05.623 ThaliTest[4518:19855265] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 12:06:05.623 ThaliTest[4518:19855265] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore488514865","JXcore","Test",[]]
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/74E6CD9A-4655-4827-8D6F-DBA7A0E90CFE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
