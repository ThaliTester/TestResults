#### Test 62509094764c200_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9E89B6B8-0C39-44AF-B5C1-5BF830771DFA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9E89B6B8-0C39-44AF-B5C1-5BF830771DFA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50933"
,(lldb)     command script import "/tmp/9E89B6B8-0C39-44AF-B5C1-5BF830771DFA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 06:43:01.331 ThaliTest[1226:2755370] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D91CEB9C-8266-48FB-A8D9-00FD680E339B/Library/Cookies/Cookies.binarycookies
,2016-03-17 06:43:01.848 ThaliTest[1226:2755370] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 06:43:01.850 ThaliTest[1226:2755370] Multi-tasking -> Device: YES, App: YES
,2016-03-17 06:43:01.870 ThaliTest[1226:2755370] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 06:43:03.963 ThaliTest[1226:2755370] Using UIWebView
,2016-03-17 06:43:03.968 ThaliTest[1226:2755370] [CDVTimer][handleopenurl] 0.299990ms
,2016-03-17 06:43:03.973 ThaliTest[1226:2755370] [CDVTimer][intentandnavigationfilter] 5.436003ms
2016-03-17 06:43:03.974 ThaliTest[1226:2755370] [CDVTimer][gesturehandler] 0.263989ms
2016-03-17 06:43:03.974 ThaliTest[1226:2755370] [CDVTimer][TotalPluginStartup] 7.070005ms
,2016-03-17 06:43:12.514 ThaliTest[1226:2755370] Resetting plugins due to page load.
,2016-03-17 06:43:16.447 ThaliTest[1226:2755370] Finished load of: file:///var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/index.html
,2016-03-17 06:43:16.651 ThaliTest[1226:2755370] JXcore Cordova plugin initializing
2016-03-17 06:43:16.652 ThaliTest[1226:2755561] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,2016-03-17 06:43:26.330 ThaliTest[1226:2755561] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 06:43:26.330 ThaliTest[1226:2755561] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 06:43:26.331 ThaliTest[1226:2,755561] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-17 06:43:26.337 ThaliTest[1226:2755561] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20D4552F-A99E-4F28-AF53-294755BBAECB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-17 06:43:46.169 ThaliTest[1226:2755370] THREAD WARNING: ['JXcore'] took '14324.629150' ms. Plugin should use a background thread.
,2016-03-17 06:43:46.170 ThaliTest[1226:2755508] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e

```
