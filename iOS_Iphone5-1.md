#### Test 63012666d6bb2e8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B153A781-F77B-4979-84F4-7DBDE2B19B19/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B153A781-F77B-4979-84F4-7DBDE2B19B19/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50708"
,(lldb)     command script import "/tmp/B153A781-F77B-4979-84F4-7DBDE2B19B19/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 14:29:46.870 ThaliTest[1203:2652910] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/437DD462-E9C3-4E02-844E-98BBA7CCFA92/Library/Cookies/Cookies.binarycookies
,2016-03-16 14:29:46.987 ThaliTest[1203:2652910] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 14:29:46.989 ThaliTest[1203:2652910] Multi-tasking -> Device: YES, App: YES
,2016-03-16 14:29:47.009 ThaliTest[1203:2652910] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 14:29:49.147 ThaliTest[1203:2652910] Using UIWebView
,2016-03-16 14:29:49.152 ThaliTest[1203:2652910] [CDVTimer][handleopenurl] 0.407040ms
,2016-03-16 14:29:49.158 ThaliTest[1203:2652910] [CDVTimer][intentandnavigationfilter] 5.196035ms
2016-03-16 14:29:49.158 ThaliTest[1203:2652910] [CDVTimer][gesturehandler] 0.262022ms
2016-03-16 14:29:49.158 ThaliTest[1203:2652910] [CDVTimer][TotalPluginS,tartup] 6.972015ms
,2016-03-16 14:29:57.445 ThaliTest[1203:2652910] Resetting plugins due to page load.
,2016-03-16 14:30:01.390 ThaliTest[1203:2652910] Finished load of: file:///var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/index.html
,2016-03-16 14:30:01.601 ThaliTest[1203:2652910] JXcore Cordova plugin initializing
,2016-03-16 14:30:01.604 ThaliTest[1203:2653094] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-16 14:30:11.319 ThaliTest[1203:2653094] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-16 14:30:11.320 ThaliTest[1203:2653094] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 14:30:11.320 ThaliTest[1203:2653094] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-16 14:30:11.326 ThaliTest[1203:2653094] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E50C0CD-642F-4156-B444-65880ED6D47B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-16 14:30:31.177 ThaliTest[1203:2652910] THREAD WARNING: ['JXcore'] took '14317.277832' ms. Plugin should use a background thread.
,2016-03-16 14:30:31.178 ThaliTest[1203:2653052] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```
