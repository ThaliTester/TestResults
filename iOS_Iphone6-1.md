#### Test 62509094c3ee53f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EB3E2EF5-4E41-43BF-9064-6382784486A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EB3E2EF5-4E41-43BF-9064-6382784486A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50334"
,(lldb)     command script import "/tmp/EB3E2EF5-4E41-43BF-9064-6382784486A9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 10:37:59.238 ThaliTest[1512:2428305] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B1705306-E088-40D4-B233-F29260FAA4D8/Library/Cookies/Cookies.binarycookies
,2016-03-16 10:37:59.619 ThaliTest[1512:2428305] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 10:37:59.620 ThaliTest[1512:2428305] Multi-tasking -> Device: YES, App: YES
,2016-03-16 10:37:59.647 ThaliTest[1512:2428305] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 10:38:01.415 ThaliTest[1512:2428305] Using UIWebView
,2016-03-16 10:38:01.422 ThaliTest[1512:2428305] [CDVTimer][handleopenurl] 0.631034ms
,2016-03-16 10:38:01.429 ThaliTest[1512:2428305] [CDVTimer][intentandnavigationfilter] 7.126987ms
2016-03-16 10:38:01.430 ThaliTest[1512:2428305] [CDVTimer][gesturehandler] 0.352025ms
2016-03-16 10:38:01.431 ThaliTest[1512:2428305] [CDVTimer][TotalPluginS,tartup] 9.729981ms
,2016-03-16 10:38:08.870 ThaliTest[1512:2428305] Resetting plugins due to page load.
,2016-03-16 10:38:12.152 ThaliTest[1512:2428305] Finished load of: file:///var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/index.html
,2016-03-16 10:38:12.377 ThaliTest[1512:2428305] JXcore Cordova plugin initializing
,2016-03-16 10:38:12.379 ThaliTest[1512:2428529] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 10:38:16.704 ThaliTest[1512:2428529] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 10:38:16.705 ThaliTest[1512:2428529] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 10:38:16.705 ThaliTest[1512:2428529] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 10:38:16.708 ThaliTest[1512:2428529] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E48D61B4-08C5-4157-A859-20CA757589E0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 10:38:25.609 ThaliTest[1512:2428305] THREAD WARNING: ['JXcore'] took '6392.382080' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
