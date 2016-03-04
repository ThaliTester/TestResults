#### Test 617161634bd7322_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A8519676-69A7-4C54-A9B0-0FDDE985A5B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A8519676-69A7-4C54-A9B0-0FDDE985A5B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/617161634bd7322/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49888"
,(lldb)     command script import "/tmp/A8519676-69A7-4C54-A9B0-0FDDE985A5B3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 15:42:39.404 ThaliTest[643:754261] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F550B2F9-0ACD-41A6-B850-F4FDF9DF7E57/Library/Cookies/Cookies.binarycookies
,2016-03-04 15:42:39.817 ThaliTest[643:754261] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 15:42:39.819 ThaliTest[643:754261] Multi-tasking -> Device: YES, App: YES
,2016-03-04 15:42:39.844 ThaliTest[643:754261] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 15:42:41.819 ThaliTest[643:754261] Using UIWebView
,2016-03-04 15:42:41.826 ThaliTest[643:754261] [CDVTimer][handleopenurl] 0.517964ms
,2016-03-04 15:42:41.834 ThaliTest[643:754261] [CDVTimer][intentandnavigationfilter] 7.410944ms
,2016-03-04 15:42:41.835 ThaliTest[643:754261] [CDVTimer][gesturehandler] 0.600040ms
2016-03-04 15:42:41.835 ThaliTest[643:754261] [CDVTimer][TotalPluginStartup] 10.293007ms
,2016-03-04 15:42:48.893 ThaliTest[643:754261] Resetting plugins due to page load.
,2016-03-04 15:42:52.264 ThaliTest[643:754261] Finished load of: file:///var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/index.html
,2016-03-04 15:42:52.488 ThaliTest[643:754261] JXcore Cordova plugin initializing
2016-03-04 15:42:52.489 ThaliTest[643:754474] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 15:42:59.931 ThaliTest[643:754474] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 15:42:59.931 ThaliTest[643:754474] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 15:42:59.932 ThaliTest[643:754474] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 15:42:59.935 ThaliTest[643:754474] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/06DE366D-E66C-4906-8D5E-5CB4493AC771/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded


```
