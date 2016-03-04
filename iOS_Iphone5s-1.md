#### Test 614329799926788_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/614329799926788/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8F609AED-9A90-45B2-A3BC-5EE70C5D2154/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8F609AED-9A90-45B2-A3BC-5EE70C5D2154/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/614329799926788/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/614329799926788/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49367"
,(lldb)     command script import "/tmp/8F609AED-9A90-45B2-A3BC-5EE70C5D2154/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 08:38:17.242 ThaliTest[640:722908] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BBCE0C60-715E-4421-A115-9750E3FC7F9D/Library/Cookies/Cookies.binarycookies
,2016-03-04 08:38:17.596 ThaliTest[640:722908] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 08:38:17.597 ThaliTest[640:722908] Multi-tasking -> Device: YES, App: YES
,2016-03-04 08:38:17.623 ThaliTest[640:722908] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 08:38:19.299 ThaliTest[640:722908] Using UIWebView
,2016-03-04 08:38:19.306 ThaliTest[640:722908] [CDVTimer][handleopenurl] 0.438988ms
,2016-03-04 08:38:19.315 ThaliTest[640:722908] [CDVTimer][intentandnavigationfilter] 8.105040ms
2016-03-04 08:38:19.316 ThaliTest[640:722908] [CDVTimer][gesturehandler] 0.415981ms
2016-03-04 08:38:19.316 ThaliTest[640:722908] [CDVTimer][TotalPluginStartup,] 10.725975ms
,2016-03-04 08:38:26.092 ThaliTest[640:722908] Resetting plugins due to page load.
,2016-03-04 08:38:29.355 ThaliTest[640:722908] Finished load of: file:///var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/index.html
,2016-03-04 08:38:29.618 ThaliTest[640:722908] JXcore Cordova plugin initializing
,2016-03-04 08:38:29.619 ThaliTest[640:723142] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 08:38:38.410 ThaliTest[640:723142] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 08:38:38.410 ThaliTest[640:723142] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 08:38:38.410 ThaliTest[640:723142] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 08:38:38.414 ThaliTest[640:723142] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F7511B2B-95A2-4C2D-8282-CA3E88AA4DA2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
