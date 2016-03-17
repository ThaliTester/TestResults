#### Test 62509094764c200_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D77543F1-EB41-43F2-8C8F-AAC69BB06404/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D77543F1-EB41-43F2-8C8F-AAC69BB06404/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50951"
,(lldb)     command script import "/tmp/D77543F1-EB41-43F2-8C8F-AAC69BB06404/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 06:43:36.659 ThaliTest[1574:2551354] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BB340B23-C7AD-428B-80FD-F3CA993AC7CC/Library/Cookies/Cookies.binarycookies
,2016-03-17 06:43:37.092 ThaliTest[1574:2551354] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 06:43:37.094 ThaliTest[1574:2551354] Multi-tasking -> Device: YES, App: YES
,2016-03-17 06:43:37.118 ThaliTest[1574:2551354] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 06:43:38.910 ThaliTest[1574:2551354] Using UIWebView
,2016-03-17 06:43:38.917 ThaliTest[1574:2551354] [CDVTimer][handleopenurl] 0.382006ms
,2016-03-17 06:43:38.925 ThaliTest[1574:2551354] [CDVTimer][intentandnavigationfilter] 7.139981ms
2016-03-17 06:43:38.926 ThaliTest[1574:2551354] [CDVTimer][gesturehandler] 0.388026ms
2016-03-17 06:43:38.926 ThaliTest[1574:2551354] [CDVTimer][TotalPluginStartup] 9.513974ms
,2016-03-17 06:43:45.286 ThaliTest[1574:2551354] Resetting plugins due to page load.
,2016-03-17 06:43:48.201 ThaliTest[1574:2551354] Finished load of: file:///var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/index.html
,2016-03-17 06:43:48.419 ThaliTest[1574:2551354] JXcore Cordova plugin initializing
,2016-03-17 06:43:48.421 ThaliTest[1574:2551559] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-17 06:43:52.663 ThaliTest[1574:2551559] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 06:43:52.663 ThaliTest[1574:2551559] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 06:43:52.663 ThaliTest[1574:2551559] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-17 06:43:52.666 ThaliTest[1574:2551559] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/17D01150-1E13-41F0-ABD1-86AA6F73AA5A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-17 06:44:01.437 ThaliTest[1574:2551354] THREAD WARNING: ['JXcore'] took '6294.020020' ms. Plugin should use a background thread.

```
