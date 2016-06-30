#### Test 72145431fdae11f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/A4320A6A-B9E7-4305-AF3C-9F1EB5EC21D8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A4320A6A-B9E7-4305-AF3C-9F1EB5EC21D8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64746"
,(lldb)     command script import "/tmp/A4320A6A-B9E7-4305-AF3C-9F1EB5EC21D8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-06-30 10:33:41.002 ThaliTest[6129:18544955] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FF726972-2491-4FE8-9C3C-D03FB611D497/Library/Cookies/Cookies.binarycookies
,2016-06-30 10:33:41.474 ThaliTest[6129:18544955] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 10:33:41.476 ThaliTest[6129:18544955] Multi-tasking -> Device: YES, App: YES
,2016-06-30 10:33:41.502 ThaliTest[6129:18544955] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 10:33:43.499 ThaliTest[6129:18544955] Using UIWebView
,2016-06-30 10:33:43.507 ThaliTest[6129:18544955] [CDVTimer][handleopenurl] 0.512004ms
,2016-06-30 10:33:43.515 ThaliTest[6129:18544955] [CDVTimer][intentandnavigationfilter] 7.924020ms
2016-06-30 10:33:43.516 ThaliTest[6129:18544955] [CDVTimer][gesturehandler] 0.384986ms
2016-06-30 10:33:43.517 ThaliTest[6129:18544955] [CDVTimer][TotalPlug,inStartup] 10.699034ms
,2016-06-30 10:33:51.083 ThaliTest[6129:18544955] Resetting plugins due to page load.
,2016-06-30 10:33:55.215 ThaliTest[6129:18544955] Finished load of: file:///var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/index.html
,2016-06-30 10:33:55.467 ThaliTest[6129:18544955] JXcore Cordova plugin initializing
,2016-06-30 10:33:55.469 ThaliTest[6129:18545190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 10:34:04.459 ThaliTest[6129:18545190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-30 10:34:04.460 ThaliTest[6129:18545190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 10:34:04.460 ThaliTest[6129,:18545190] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 10:34:04.463 ThaliTest[6129:18545190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBDF9F65-903D-4DF9-97AA-79D92003B294/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 10:34:11.734 ThaliTest[6129:18544955] THREAD WARNING: ['JXcore'] took '6899.209961' ms. Plugin should use a background thread.

```
