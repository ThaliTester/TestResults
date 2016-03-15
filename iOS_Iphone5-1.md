#### Test 62509094058a2d4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/20694555-E8AD-417F-86B2-CF0B6A0833EE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/20694555-E8AD-417F-86B2-CF0B6A0833EE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49561"
,(lldb)     command script import "/tmp/20694555-E8AD-417F-86B2-CF0B6A0833EE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 13:14:31.736 ThaliTest[1119:2484196] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3789A172-05A5-4E3A-B6EB-66E42AB63B5C/Library/Cookies/Cookies.binarycookies
,2016-03-15 13:14:31.856 ThaliTest[1119:2484196] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 13:14:31.858 ThaliTest[1119:2484196] Multi-tasking -> Device: YES, App: YES
,2016-03-15 13:14:31.882 ThaliTest[1119:2484196] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 13:14:33.929 ThaliTest[1119:2484196] Using UIWebView
,2016-03-15 13:14:33.934 ThaliTest[1119:2484196] [CDVTimer][handleopenurl] 0.397980ms
,2016-03-15 13:14:33.940 ThaliTest[1119:2484196] [CDVTimer][intentandnavigationfilter] 5.584955ms
2016-03-15 13:14:33.941 ThaliTest[1119:2484196] [CDVTimer][gesturehandler] 0.268996ms
2016-03-15 13:14:33.941 ThaliTest[1119:2484196] [CDVTimer][TotalPluginStartup] 7.287025ms
,2016-03-15 13:14:42.246 ThaliTest[1119:2484196] Resetting plugins due to page load.
,2016-03-15 13:14:46.480 ThaliTest[1119:2484196] Finished load of: file:///var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/index.html
,2016-03-15 13:14:46.685 ThaliTest[1119:2484196] JXcore Cordova plugin initializing
,2016-03-15 13:14:46.687 ThaliTest[1119:2484370] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,2016-03-15 13:14:55.187 ThaliTest[1119:2484370] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 13:14:55.188 ThaliTest[1119:2484370] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 13:14:55.188 ThaliTest[1119:2,484370] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 13:14:55.194 ThaliTest[1119:2484370] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07B667EC-5259-41AA-97EE-9713E89B6B0A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-15 13:15:13.369 ThaliTest[1119:2484196] THREAD WARNING: ['JXcore'] took '13972.236084' ms. Plugin should use a background thread.
,2016-03-15 13:15:13.372 ThaliTest[1119:2484320] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
