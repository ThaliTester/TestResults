#### Test 62548124e8057a0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/586D46C1-CC70-4F18-94C3-B0ACFF38C172/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/586D46C1-CC70-4F18-94C3-B0ACFF38C172/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54242"
,(lldb)     command script import "/tmp/586D46C1-CC70-4F18-94C3-B0ACFF38C172/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 14:20:16.308 ThaliTest[1454:3427074] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF0E0596-2177-44A5-BD9F-4B6FBC2076B8/Library/Cookies/Cookies.binarycookies
,2016-03-21 14:20:16.875 ThaliTest[1454:3427074] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 14:20:16.876 ThaliTest[1454:3427074] Multi-tasking -> Device: YES, App: YES
,2016-03-21 14:20:16.899 ThaliTest[1454:3427074] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 14:20:19.140 ThaliTest[1454:3427074] Using UIWebView
,2016-03-21 14:20:19.145 ThaliTest[1454:3427074] [CDVTimer][handleopenurl] 0.344992ms
,2016-03-21 14:20:19.151 ThaliTest[1454:3427074] [CDVTimer][intentandnavigationfilter] 5.006969ms
2016-03-21 14:20:19.152 ThaliTest[1454:3427074] [CDVTimer][gesturehandler] 0.252008ms
2016-03-21 14:20:19.152 ThaliTest[1454:3427074] [CDVTimer][TotalPluginS,tartup] 7.452011ms
,2016-03-21 14:20:28.007 ThaliTest[1454:3427074] Resetting plugins due to page load.
,2016-03-21 14:20:31.733 ThaliTest[1454:3427074] Finished load of: file:///var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/index.html
,2016-03-21 14:20:32.024 ThaliTest[1454:3427074] JXcore Cordova plugin initializing
,2016-03-21 14:20:32.026 ThaliTest[1454:3427261] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 14:20:48.603 ThaliTest[1454:3427261] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 14:20:48.604 ThaliTest[1454:3427261] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 14:20:48.604 ThaliTest[1454:3,427261] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 14:20:48.608 ThaliTest[1454:3427261] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/603CF3C1-8E7A-405E-8C51-6D3B447C1884/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 14:21:02.151 ThaliTest[1454:3427074] THREAD WARNING: ['JXcore'] took '12849.156982' ms. Plugin should use a background thread.
,2016-03-21 14:21:02.153 ThaliTest[1454:3427213] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
