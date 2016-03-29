#### Test 64531254841497d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8FCB4518-D7F2-4AC9-B579-AE8FA296C3A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8FCB4518-D7F2-4AC9-B579-AE8FA296C3A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56569"
,(lldb)     command script import "/tmp/8FCB4518-D7F2-4AC9-B579-AE8FA296C3A4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 23:40:47.886 ThaliTest[2467:4557251] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/12DCF0B8-7830-4884-8C4D-7A40B72F1D54/Library/Cookies/Cookies.binarycookies
,2016-03-29 23:40:48.315 ThaliTest[2467:4557251] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 23:40:48.317 ThaliTest[2467:4557251] Multi-tasking -> Device: YES, App: YES
,2016-03-29 23:40:48.336 ThaliTest[2467:4557251] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 23:40:50.729 ThaliTest[2467:4557251] Using UIWebView
,2016-03-29 23:40:50.735 ThaliTest[2467:4557251] [CDVTimer][handleopenurl] 0.459969ms
,2016-03-29 23:40:50.742 ThaliTest[2467:4557251] [CDVTimer][intentandnavigationfilter] 6.532013ms
,2016-03-29 23:40:50.743 ThaliTest[2467:4557251] [CDVTimer][gesturehandler] 0.329971ms
,2016-03-29 23:40:50.744 ThaliTest[2467:4557251] [CDVTimer][TotalPluginStartup] 8.975983ms
,2016-03-29 23:40:58.648 ThaliTest[2467:4557251] Resetting plugins due to page load.
,2016-03-29 23:41:02.741 ThaliTest[2467:4557251] Finished load of: file:///var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/index.html
,2016-03-29 23:41:02.753 ThaliTest[2467:4557251] JXcore Cordova plugin initializing
,2016-03-29 23:41:02.754 ThaliTest[2467:4557473] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 23:41:09.438 ThaliTest[2467:4557473] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 23:41:09.438 ThaliTest[2467:4557473] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 23:41:09.439 ThaliTest[2467:4557473] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 23:41:09.440 ThaliTest[2467:4557473] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A9880581-5D19-44B1-B3A7-C94FC796DE69/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-29 23:41:14.634 ThaliTest[2467:4557251] THREAD WARNING: ['JXcore'] took '4922.763916' ms. Plugin should use a background thread.

```
