#### Test 60124347d1a8dac_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/2B382B03-D7CB-45D3-85AB-34E6F5ED1923/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2B382B03-D7CB-45D3-85AB-34E6F5ED1923/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d1a8dac/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50841"
,(lldb)     command script import "/tmp/2B382B03-D7CB-45D3-85AB-34E6F5ED1923/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 15:20:41.477 ThaliTest[1082:1653607] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E06A459A-FB4F-4DE4-A19B-C46F22C2AD7C/Library/Cookies/Cookies.binarycookies
,2016-03-10 15:20:41.850 ThaliTest[1082:1653607] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 15:20:41.851 ThaliTest[1082:1653607] Multi-tasking -> Device: YES, App: YES
,2016-03-10 15:20:41.874 ThaliTest[1082:1653607] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 15:20:43.805 ThaliTest[1082:1653607] Using UIWebView
,2016-03-10 15:20:43.814 ThaliTest[1082:1653607] [CDVTimer][handleopenurl] 0.376999ms
,2016-03-10 15:20:43.821 ThaliTest[1082:1653607] [CDVTimer][intentandnavigationfilter] 6.506979ms
,2016-03-10 15:20:43.822 ThaliTest[1082:1653607] [CDVTimer][gesturehandler] 0.312984ms
,2016-03-10 15:20:43.822 ThaliTest[1082:1653607] [CDVTimer][TotalPluginStartup] 8.839011ms
,2016-03-10 15:20:50.680 ThaliTest[1082:1653607] Resetting plugins due to page load.
,2016-03-10 15:20:53.906 ThaliTest[1082:1653607] Finished load of: file:///var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/index.html
,2016-03-10 15:20:54.117 ThaliTest[1082:1653607] JXcore Cordova plugin initializing
,2016-03-10 15:20:54.118 ThaliTest[1082:1653856] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 15:21:00.717 ThaliTest[1082:1653856] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 15:21:00.717 ThaliTest[1082:1653856] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-10 15:21:00.717 ThaliTest[1082:1653856] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 15:21:00.720 ThaliTest[1082:1653856] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/201F496F-7248-4D3A-93F1-F5624D6B2AF4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
