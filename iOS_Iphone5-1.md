#### Test 6177688874f8189_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/392B9051-DF95-49B5-9DA4-FD92E43C4B26/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/392B9051-DF95-49B5-9DA4-FD92E43C4B26/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50042"
,(lldb)     command script import "/tmp/392B9051-DF95-49B5-9DA4-FD92E43C4B26/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
,(lldb)     autoexit
,2016-03-04 23:20:31.144 ThaliTest[566:897142] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D5ECCD4-6BB5-40E6-8731-8D63923450FA/Library/Cookies/Cookies.binarycookies
,2016-03-04 23:20:31.260 ThaliTest[566:897142] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 23:20:31.261 ThaliTest[566:897142] Multi-tasking -> Device: YES, App: YES
,2016-03-04 23:20:31.280 ThaliTest[566:897142] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 23:20:33.394 ThaliTest[566:897142] Using UIWebView
,2016-03-04 23:20:33.399 ThaliTest[566:897142] [CDVTimer][handleopenurl] 0.382006ms
,2016-03-04 23:20:33.405 ThaliTest[566:897142] [CDVTimer][intentandnavigationfilter] 5.325973ms
2016-03-04 23:20:33.405 ThaliTest[566:897142] [CDVTimer][gesturehandler] 0.395954ms
2016-03-04 23:20:33.406 ThaliTest[566:897142] [CDVTimer][TotalPluginStartup] 7.236004ms
,2016-03-04 23:20:41.916 ThaliTest[566:897142] Resetting plugins due to page load.
,2016-03-04 23:20:46.061 ThaliTest[566:897142] Finished load of: file:///var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/index.html
,2016-03-04 23:20:46.264 ThaliTest[566:897142] JXcore Cordova plugin initializing
,2016-03-04 23:20:46.266 ThaliTest[566:897339] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 23:21:02.789 ThaliTest[566:897339] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-04 23:21:02.790 ThaliTest[566:897339] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 23:21:02.791 ThaliTest[566:897339] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 23:21:02.796 ThaliTest[566:897339] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AAF82CD6-2951-41F2-BAB5-84AA176E8404/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
