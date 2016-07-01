#### Test 757892686fd65a6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/091394C9-CF11-4445-8F21-D44DDD0058A8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/091394C9-CF11-4445-8F21-D44DDD0058A8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65194"
,(lldb)     command script import "/tmp/091394C9-CF11-4445-8F21-D44DDD0058A8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 08:55:26.754 ThaliTest[3464:12971713] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A21CC3FE-7A4A-442F-8C42-B3F02EC9CB29/Library/Cookies/Cookies.binarycookies
,2016-07-01 08:55:26.978 ThaliTest[3464:12971713] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 08:55:26.978 ThaliTest[3464:12971713] Multi-tasking -> Device: YES, App: YES
,2016-07-01 08:55:26.992 ThaliTest[3464:12971713] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 08:55:27.773 ThaliTest[3464:12971713] Using UIWebView
,2016-07-01 08:55:27.775 ThaliTest[3464:12971713] [CDVTimer][handleopenurl] 0.153005ms
,2016-07-01 08:55:27.777 ThaliTest[3464:12971713] [CDVTimer][intentandnavigationfilter] 1.899004ms
2016-07-01 08:55:27.777 ThaliTest[3464:12971713] [CDVTimer][gesturehandler] 0.088036ms
2016-07-01 08:55:27.777 ThaliTest[3464:12971713] [CDVTimer][TotalPluginStartup] 2.568007ms
,2016-07-01 08:55:31.018 ThaliTest[3464:12971713] Resetting plugins due to page load.
,2016-07-01 08:55:32.416 ThaliTest[3464:12971713] Finished load of: file:///var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/index.html
,2016-07-01 08:55:32.553 ThaliTest[3464:12971713] JXcore Cordova plugin initializing
2016-07-01 08:55:32.554 ThaliTest[3464:12971881] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 08:55:38.921 ThaliTest[3464:12971881] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-01 08:55:38.921 ThaliTest[3464:12971881] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-01 08:55:38.922 ThaliTest[3464:12971881] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 08:55:38.923 ThaliTest[3464:12971881] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/52F4F599-F0E0-4B6B-9017-191BC4406E78/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-01 08:55:44.076 ThaliTest[3464:12971713] THREAD WARNING: ['JXcore'] took '4884.179199' ms. Plugin should use a background thread.
2016-07-01 08:55:44.076 ThaliTest[3464:12971713] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 08:55:44.076 ThaliTest[3464:12971713] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1784156983","JXcore","Test",[]]

```
