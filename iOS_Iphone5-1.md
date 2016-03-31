#### Test 646138036c5f71d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/562E8C92-346E-4E3F-833B-C410A0130CC5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/562E8C92-346E-4E3F-833B-C410A0130CC5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138036c5f71d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49761"
,(lldb)     command script import "/tmp/562E8C92-346E-4E3F-833B-C410A0130CC5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 15:12:41.156 ThaliTest[1935:4946953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F75B4EE-1B39-4CB1-A35F-F32C99B9BBDF/Library/Cookies/Cookies.binarycookies
,2016-03-31 15:12:41.264 ThaliTest[1935:4946953] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 15:12:41.265 ThaliTest[1935:4946953] Multi-tasking -> Device: YES, App: YES
,2016-03-31 15:12:41.282 ThaliTest[1935:4946953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 15:12:42.467 ThaliTest[1935:4946953] Using UIWebView
2016-03-31 15:12:42.470 ThaliTest[1935:4946953] [CDVTimer][handleopenurl] 0.279009ms
,2016-03-31 15:12:42.477 ThaliTest[1935:4946953] [CDVTimer][intentandnavigationfilter] 6.454945ms
2016-03-31 15:12:42.478 ThaliTest[1935:4946953] [CDVTimer][gesturehandler] 0.234008ms
2016-03-31 15:12:42.478 ThaliTest[1935:4946953] [CDVTimer][TotalPluginStartup] 7.786989ms
,2016-03-31 15:12:47.388 ThaliTest[1935:4946953] Resetting plugins due to page load.
,2016-03-31 15:12:49.806 ThaliTest[1935:4946953] Finished load of: file:///var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/index.html
,2016-03-31 15:12:50.005 ThaliTest[1935:4946953] JXcore Cordova plugin initializing
,2016-03-31 15:12:50.128 ThaliTest[1935:4947107] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 15:13:04.282 ThaliTest[1935:4947107] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 15:13:04.283 ThaliTest[1935:4947107] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 15:13:04.284 ThaliTest[1935:4947107] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 15:13:04.286 ThaliTest[1935:4947107] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/97962079-A81B-4C78-A01A-7D335DF6ED99/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
