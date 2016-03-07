#### Test 6012434797f7ca7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CB74C9FB-19A1-4608-A307-8901713BA451/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CB74C9FB-19A1-4608-A307-8901713BA451/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51747"
,(lldb)     command script import "/tmp/CB74C9FB-19A1-4608-A307-8901713BA451/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 20:27:43.891 ThaliTest[835:1205078] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8C4DB05E-7D3E-4E52-886E-15635D2BF275/Library/Cookies/Cookies.binarycookies
,2016-03-07 20:27:44.268 ThaliTest[835:1205078] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 20:27:44.270 ThaliTest[835:1205078] Multi-tasking -> Device: YES, App: YES
,2016-03-07 20:27:44.299 ThaliTest[835:1205078] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 20:27:46.263 ThaliTest[835:1205078] Using UIWebView
,2016-03-07 20:27:46.270 ThaliTest[835:1205078] [CDVTimer][handleopenurl] 0.431001ms
,2016-03-07 20:27:46.278 ThaliTest[835:1205078] [CDVTimer][intentandnavigationfilter] 7.135034ms
2016-03-07 20:27:46.279 ThaliTest[835:1205078] [CDVTimer][gesturehandler] 0.375986ms
2016-03-07 20:27:46.279 ThaliTest[835:1205078] [CDVTimer][TotalPluginStartup] 9.607017ms
,2016-03-07 20:27:53.282 ThaliTest[835:1205078] Resetting plugins due to page load.
,2016-03-07 20:27:56.932 ThaliTest[835:1205078] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/index.html
,2016-03-07 20:27:57.154 ThaliTest[835:1205078] JXcore Cordova plugin initializing
,2016-03-07 20:27:57.157 ThaliTest[835:1205292] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 20:28:04.724 ThaliTest[835:1205292] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 20:28:04.725 ThaliTest[835:1205292] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 20:28:04.725 ThaliTest[835:1205292] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-07 20:28:04.727 ThaliTest[835:1205292] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD644338-0885-4CF6-B719-01F0292EFC2B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
