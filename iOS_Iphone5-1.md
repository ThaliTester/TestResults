#### Test 62548124ece3ba0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/83CDEA99-A82F-40F0-8F77-10DF5E1EEA7A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/83CDEA99-A82F-40F0-8F77-10DF5E1EEA7A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53349"
,(lldb)     command script import "/tmp/83CDEA99-A82F-40F0-8F77-10DF5E1EEA7A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 17:18:26.361 ThaliTest[1409:3290307] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FEFF08A1-A2A3-4E87-8033-13FFDDDBD39E/Library/Cookies/Cookies.binarycookies
,2016-03-20 17:18:26.472 ThaliTest[1409:3290307] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 17:18:26.475 ThaliTest[1409:3290307] Multi-tasking -> Device: YES, App: YES
,2016-03-20 17:18:26.493 ThaliTest[1409:3290307] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 17:18:28.784 ThaliTest[1409:3290307] Using UIWebView
,2016-03-20 17:18:28.790 ThaliTest[1409:3290307] [CDVTimer][handleopenurl] 0.439048ms
,2016-03-20 17:18:28.795 ThaliTest[1409:3290307] [CDVTimer][intentandnavigationfilter] 5.405009ms
2016-03-20 17:18:28.796 ThaliTest[1409:3290307] [CDVTimer][gesturehandler] 0.281036ms
2016-03-20 17:18:28.796 ThaliTest[1409:3290307] [CDVTimer][TotalPluginStartup] 7.399976ms
,2016-03-20 17:18:37.349 ThaliTest[1409:3290307] Resetting plugins due to page load.
,2016-03-20 17:18:41.564 ThaliTest[1409:3290307] Finished load of: file:///var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/index.html
,2016-03-20 17:18:41.767 ThaliTest[1409:3290307] JXcore Cordova plugin initializing
,2016-03-20 17:18:41.769 ThaliTest[1409:3290496] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 17:18:58.393 ThaliTest[1409:3290496] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 17:18:58.394 ThaliTest[1409:3290496] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 17:18:58.394 ThaliTest[1409:3290496] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 17:18:58.397 ThaliTest[1409:3290496] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8105D2A-3AE2-4166-90D0-693A8BAF10BE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 17:19:11.904 ThaliTest[1409:3290307] THREAD WARNING: ['JXcore'] took '12814.295898' ms. Plugin should use a background thread.
,2016-03-20 17:19:11.906 ThaliTest[1409:3290430] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
