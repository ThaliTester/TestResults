#### Test 625481246b04bc0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/71D347AF-C0AB-45A8-A06B-6CF6555BBA79/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/71D347AF-C0AB-45A8-A06B-6CF6555BBA79/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49458"
,(lldb)     command script import "/tmp/71D347AF-C0AB-45A8-A06B-6CF6555BBA79/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 12:43:52.161 ThaliTest[1113:2479641] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA4E4070-0EB1-4DBE-8F66-12C38B2E69D4/Library/Cookies/Cookies.binarycookies
,2016-03-15 12:43:52.286 ThaliTest[1113:2479641] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 12:43:52.288 ThaliTest[1113:2479641] Multi-tasking -> Device: YES, App: YES
,2016-03-15 12:43:52.312 ThaliTest[1113:2479641] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 12:43:54.369 ThaliTest[1113:2479641] Using UIWebView
,2016-03-15 12:43:54.374 ThaliTest[1113:2479641] [CDVTimer][handleopenurl] 0.415981ms
,2016-03-15 12:43:54.380 ThaliTest[1113:2479641] [CDVTimer][intentandnavigationfilter] 5.169988ms
2016-03-15 12:43:54.380 ThaliTest[1113:2479641] [CDVTimer][gesturehandler] 0.277042ms
2016-03-15 12:43:54.380 ThaliTest[1113:2479641] [CDVTimer][TotalPluginStartup] 6.896019ms
,2016-03-15 12:44:03.065 ThaliTest[1113:2479641] Resetting plugins due to page load.
,2016-03-15 12:44:06.858 ThaliTest[1113:2479641] Finished load of: file:///var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/index.html
,2016-03-15 12:44:07.073 ThaliTest[1113:2479641] JXcore Cordova plugin initializing
,2016-03-15 12:44:07.076 ThaliTest[1113:2479834] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 12:44:32.467 ThaliTest[1113:2479834] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 12:44:32.469 ThaliTest[1113:2479834] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 12:44:32.469 ThaliTest[1113:2479834] jxcore: didRegisterToNative networkChanged
,2016-03-15 12:44:32.471 ThaliTest[1113:2479834] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C28BF055-8E9D-4A45-85E0-3C9BF20DA898/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
