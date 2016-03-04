#### Test 6177688874f8189_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F1004D69-C652-4688-8940-281B0943B1AE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F1004D69-C652-4688-8940-281B0943B1AE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6177688874f8189/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50082"
,(lldb)     command script import "/tmp/F1004D69-C652-4688-8940-281B0943B1AE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 23:21:39.206 ThaliTest[701:814438] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B2778835-8C6F-4749-8F26-E26A01F4BF45/Library/Cookies/Cookies.binarycookies
,2016-03-04 23:21:39.618 ThaliTest[701:814438] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 23:21:39.620 ThaliTest[701:814438] Multi-tasking -> Device: YES, App: YES
,2016-03-04 23:21:39.644 ThaliTest[701:814438] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 23:21:41.568 ThaliTest[701:814438] Using UIWebView
,2016-03-04 23:21:41.576 ThaliTest[701:814438] [CDVTimer][handleopenurl] 0.446975ms
,2016-03-04 23:21:41.584 ThaliTest[701:814438] [CDVTimer][intentandnavigationfilter] 7.890999ms
2016-03-04 23:21:41.585 ThaliTest[701:814438] [CDVTimer][gesturehandler] 0.371993ms
2016-03-04 23:21:41.586 ThaliTest[701:814438] [CDVTimer][TotalPluginStartup] 10.544002ms
,2016-03-04 23:21:49.408 ThaliTest[701:814438] Resetting plugins due to page load.
,2016-03-04 23:21:53.533 ThaliTest[701:814438] Finished load of: file:///var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/index.html
,2016-03-04 23:21:53.777 ThaliTest[701:814438] JXcore Cordova plugin initializing
,2016-03-04 23:21:53.778 ThaliTest[701:814666] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 23:22:02.432 ThaliTest[701:814666] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 23:22:02.433 ThaliTest[701:814666] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 23:22:02.433 ThaliTest[701:814666] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 23:22:02.437 ThaliTest[701:814666] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAE906D5-374C-4D9A-8503-E2A6B85E376B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
