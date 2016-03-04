#### Test 617161634bd7322_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/039412FE-C163-47CE-910D-FE03233AD2BA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/039412FE-C163-47CE-910D-FE03233AD2BA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49884"
,(lldb)     command script import "/tmp/039412FE-C163-47CE-910D-FE03233AD2BA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 15:42:41.383 ThaliTest[667:797099] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68847E32-D59D-43C4-93B7-49E4F6B3421F/Library/Cookies/Cookies.binarycookies
,2016-03-04 15:42:41.702 ThaliTest[667:797099] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 15:42:41.703 ThaliTest[667:797099] Multi-tasking -> Device: YES, App: YES
,2016-03-04 15:42:41.718 ThaliTest[667:797099] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 15:42:43.530 ThaliTest[667:797099] Using UIWebView
,2016-03-04 15:42:43.536 ThaliTest[667:797099] [CDVTimer][handleopenurl] 0.432014ms
,2016-03-04 15:42:43.543 ThaliTest[667:797099] [CDVTimer][intentandnavigationfilter] 6.547987ms
,2016-03-04 15:42:43.544 ThaliTest[667:797099] [CDVTimer][gesturehandler] 0.301003ms
2016-03-04 15:42:43.544 ThaliTest[667:797099] [CDVTimer][TotalPluginStartup] 9.234011ms
,2016-03-04 15:42:51.079 ThaliTest[667:797099] Resetting plugins due to page load.
,2016-03-04 15:42:54.869 ThaliTest[667:797099] Finished load of: file:///var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/index.html
,2016-03-04 15:42:55.070 ThaliTest[667:797099] JXcore Cordova plugin initializing
,2016-03-04 15:42:55.070 ThaliTest[667:797326] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 15:43:01.605 ThaliTest[667:797326] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 15:43:01.606 ThaliTest[667:797326] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 15:43:01.606 ThaliTest[667:797326] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 15:43:01.608 ThaliTest[667:797326] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBE94ECB-54E1-4375-A9D7-DBD3113DB33C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded


```
