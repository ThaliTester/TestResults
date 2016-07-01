#### Test 757892680c366d1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/238BF79D-D54D-4661-BE42-F4795742E42E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/238BF79D-D54D-4661-BE42-F4795742E42E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892680c366d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65524"
,(lldb)     command script import "/tmp/238BF79D-D54D-4661-BE42-F4795742E42E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 12:06:12.337 ThaliTest[3484:12995649] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C87BD538-F2D5-4DA6-BB75-3B9AFBDBE5FA/Library/Cookies/Cookies.binarycookies
,2016-07-01 12:06:12.568 ThaliTest[3484:12995649] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 12:06:12.569 ThaliTest[3484:12995649] Multi-tasking -> Device: YES, App: YES
,2016-07-01 12:06:12.581 ThaliTest[3484:12995649] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 12:06:13.373 ThaliTest[3484:12995649] Using UIWebView
,2016-07-01 12:06:13.375 ThaliTest[3484:12995649] [CDVTimer][handleopenurl] 0.151992ms
,2016-07-01 12:06:13.377 ThaliTest[3484:12995649] [CDVTimer][intentandnavigationfilter] 1.884043ms
2016-07-01 12:06:13.377 ThaliTest[3484:12995649] [CDVTimer][gesturehandler] 0.084996ms
2016-07-01 12:06:13.377 ThaliTest[3484:12995649] [CDVTimer][TotalPluginStartup] 2.555966ms
,2016-07-01 12:06:16.570 ThaliTest[3484:12995649] Resetting plugins due to page load.
,2016-07-01 12:06:17.976 ThaliTest[3484:12995649] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/index.html
,2016-07-01 12:06:18.111 ThaliTest[3484:12995649] JXcore Cordova plugin initializing
2016-07-01 12:06:18.112 ThaliTest[3484:12995821] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 12:06:24.527 ThaliTest[3484:12995821] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 12:06:24.528 ThaliTest[3484:12995821] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 12:06:24.528 ThaliTest[3484,:12995821] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 12:06:24.529 ThaliTest[3484:12995821] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C4E6C67-50FD-45F4-9742-34B2EE0554CE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-01 12:06:29.715 ThaliTest[3484:12995649] THREAD WARNING: ['JXcore'] took '4912.237793' ms. Plugin should use a background thread.
2016-07-01 12:06:29.715 ThaliTest[3484:12995649] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 12:06:29.715 ThaliTest[3484:12995649] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1445961477","JXcore","Test",[]]

```
