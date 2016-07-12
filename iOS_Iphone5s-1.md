#### Test 757892685a40176_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685a40176/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C34286AA-BC60-428E-B1E6-ABFDB8389472/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C34286AA-BC60-428E-B1E6-ABFDB8389472/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685a40176/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685a40176/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52771"
,(lldb)     command script import "/tmp/C34286AA-BC60-428E-B1E6-ABFDB8389472/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-12 17:42:28.134 ThaliTest[220:42517] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9383BA0F-9015-4047-ADCE-20FE66674615/Library/Cookies/Cookies.binarycookies
,2016-07-12 17:42:28.515 ThaliTest[220:42517] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-12 17:42:28.516 ThaliTest[220:42517] Multi-tasking -> Device: YES, App: YES
,2016-07-12 17:42:28.536 ThaliTest[220:42517] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-12 17:42:30.405 ThaliTest[220:42517] Using UIWebView
,2016-07-12 17:42:30.413 ThaliTest[220:42517] [CDVTimer][handleopenurl] 0.651002ms
,2016-07-12 17:42:30.422 ThaliTest[220:42517] [CDVTimer][intentandnavigationfilter] 8.013010ms
2016-07-12 17:42:30.422 ThaliTest[220:42517] [CDVTimer][gesturehandler] 0.373006ms
2016-07-12 17:42:30.423 ThaliTest[220:42517] [CDVTimer][TotalPluginStartup] 10.885000ms
,2016-07-12 17:42:37.180 ThaliTest[220:42517] Resetting plugins due to page load.
,2016-07-12 17:42:40.999 ThaliTest[220:42517] Finished load of: file:///var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/index.html
,2016-07-12 17:42:41.252 ThaliTest[220:42517] JXcore Cordova plugin initializing
,2016-07-12 17:42:41.254 ThaliTest[220:42760] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-12 17:42:50.236 ThaliTest[220:42760] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-12 17:42:50.236 ThaliTest[220:42760] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-12 17:42:50.237 ThaliTest[220:42760] j,xcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-12 17:42:50.239 ThaliTest[220:42760] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loadeded
,runUTtestsBefore
,2016-07-12 17:42:50.606 ThaliTest[220:42760] Native method ExecuteNativeTests not found.
PromiseSuccess
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BE608D6E-AF40-4845-9C41-FA82B90D8439/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-12 17:42:58.117 ThaliTest[220:42517] THREAD WARNING: ['JXcore'] took '7511.787109' ms. Plugin should use a background thread.

```
