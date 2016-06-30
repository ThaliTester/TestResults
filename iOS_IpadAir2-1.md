#### Test 7578926851a8f91_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/BEEBEB6B-D094-4AD8-AEE9-E15D1901EF19/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BEEBEB6B-D094-4AD8-AEE9-E15D1901EF19/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7578926851a8f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64896"
,(lldb)     command script import "/tmp/BEEBEB6B-D094-4AD8-AEE9-E15D1901EF19/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 12:49:12.862 ThaliTest[3419:12840979] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EF0B8D13-83C2-4D5A-99C1-544DA71567E3/Library/Cookies/Cookies.binarycookies
,2016-06-30 12:49:13.090 ThaliTest[3419:12840979] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 12:49:13.090 ThaliTest[3419:12840979] Multi-tasking -> Device: YES, App: YES
,2016-06-30 12:49:13.103 ThaliTest[3419:12840979] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 12:49:13.894 ThaliTest[3419:12840979] Using UIWebView
,2016-06-30 12:49:13.896 ThaliTest[3419:12840979] [CDVTimer][handleopenurl] 0.135005ms
,2016-06-30 12:49:13.898 ThaliTest[3419:12840979] [CDVTimer][intentandnavigationfilter] 1.996040ms
2016-06-30 12:49:13.898 ThaliTest[3419:12840979] [CDVTimer][gesturehandler] 0.082016ms
2016-06-30 12:49:13.899 ThaliTest[3419:12840979] [CDVTimer][TotalPluginStartup] 2.627969ms
,2016-06-30 12:49:17.046 ThaliTest[3419:12840979] Resetting plugins due to page load.
,2016-06-30 12:49:18.445 ThaliTest[3419:12840979] Finished load of: file:///var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/index.html
,2016-06-30 12:49:18.585 ThaliTest[3419:12840979] JXcore Cordova plugin initializing
,2016-06-30 12:49:18.585 ThaliTest[3419:12841168] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 12:49:25.102 ThaliTest[3419:12841168] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 12:49:25.102 ThaliTest[3419:12841168] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 12:49:25.103 ThaliTest[3419:12841168] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 12:49:25.104 ThaliTest[3419:12841168] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CE17ED8-D06D-4EDA-89FE-A7F17D84E6CA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 12:49:30.358 ThaliTest[3419:12840979] THREAD WARNING: ['JXcore'] took '4980.506104' ms. Plugin should use a background thread.
2016-06-30 12:49:30.359 ThaliTest[3419:12840979] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
,2016-06-30 12:49:30.359 ThaliTest[3419:12840979] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1022654213","JXcore","Test",[]]

```
