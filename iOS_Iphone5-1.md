#### Test 757892682551a10_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/1EAD9F20-C467-4EAB-8EA2-17F6F204395F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1EAD9F20-C467-4EAB-8EA2-17F6F204395F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65009"
,(lldb)     command script import "/tmp/1EAD9F20-C467-4EAB-8EA2-17F6F204395F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 13:49:21.426 ThaliTest[4476:19698862] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C14AF7B0-2E6C-4219-89B8-BFD05CD1DB92/Library/Cookies/Cookies.binarycookies
,2016-06-30 13:49:21.898 ThaliTest[4476:19698862] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 13:49:21.900 ThaliTest[4476:19698862] Multi-tasking -> Device: YES, App: YES
,2016-06-30 13:49:21.920 ThaliTest[4476:19698862] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 13:49:24.055 ThaliTest[4476:19698862] Using UIWebView
,2016-06-30 13:49:24.060 ThaliTest[4476:19698862] [CDVTimer][handleopenurl] 0.434995ms
,2016-06-30 13:49:24.065 ThaliTest[4476:19698862] [CDVTimer][intentandnavigationfilter] 5.371988ms
2016-06-30 13:49:24.066 ThaliTest[4476:19698862] [CDVTimer][gesturehandler] 0.295997ms
2016-06-30 13:49:24.066 ThaliTest[4476:19698862] [CDVTimer][TotalPluginStartup] 7.135034ms
,2016-06-30 13:49:32.286 ThaliTest[4476:19698862] Resetting plugins due to page load.
,2016-06-30 13:49:35.797 ThaliTest[4476:19698862] Finished load of: file:///var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/index.html
,2016-06-30 13:49:36.008 ThaliTest[4476:19698862] JXcore Cordova plugin initializing
,2016-06-30 13:49:36.011 ThaliTest[4476:19699043] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 13:49:52.942 ThaliTest[4476:19699043] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 13:49:52.943 ThaliTest[4476:19699043] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 13:49:52.943 ThaliTest[4476,:19699043] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 13:49:52.947 ThaliTest[4476:19699043] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E208A3D-D401-4767-8994-B18ECF1DA06D/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 13:50:06.935 ThaliTest[4476:19698862] THREAD WARNING: ['JXcore'] took '13299.680908' ms. Plugin should use a background thread.
2016-06-30 13:50:06.935 ThaliTest[4476:19698862] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-06-30 13,:50:06.936 ThaliTest[4476:19698862] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1992100497","JXcore","Test",[]]
,2016-06-30 13:50:06.939 ThaliTest[4476:19698991] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
