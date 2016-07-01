#### Test 757892686fd65a6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/AFDB1A21-17C8-4C30-90B7-46C508586318/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AFDB1A21-17C8-4C30-90B7-46C508586318/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65197"
,(lldb)     command script import "/tmp/AFDB1A21-17C8-4C30-90B7-46C508586318/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 08:55:44.264 ThaliTest[6182:18700171] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC894EC7-4B69-4477-8119-FDDBF8B534A8/Library/Cookies/Cookies.binarycookies
,2016-07-01 08:55:44.657 ThaliTest[6182:18700171] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 08:55:44.658 ThaliTest[6182:18700171] Multi-tasking -> Device: YES, App: YES
,2016-07-01 08:55:44.682 ThaliTest[6182:18700171] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 08:55:46.344 ThaliTest[6182:18700171] Using UIWebView
,2016-07-01 08:55:46.351 ThaliTest[6182:18700171] [CDVTimer][handleopenurl] 0.499010ms
,2016-07-01 08:55:46.360 ThaliTest[6182:18700171] [CDVTimer][intentandnavigationfilter] 8.202970ms
2016-07-01 08:55:46.361 ThaliTest[6182:18700171] [CDVTimer][gesturehandler] 0.388026ms
2016-07-01 08:55:46.362 ThaliTest[6182:18700171] [CDVTimer][TotalPluginStartup] 11.043966ms
,2016-07-01 08:55:53.137 ThaliTest[6182:18700171] Resetting plugins due to page load.
,2016-07-01 08:55:57.050 ThaliTest[6182:18700171] Finished load of: file:///var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/index.html
,2016-07-01 08:55:57.296 ThaliTest[6182:18700171] JXcore Cordova plugin initializing
2016-07-01 08:55:57.297 ThaliTest[6182:18700411] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 08:56:06.443 ThaliTest[6182:18700411] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 08:56:06.444 ThaliTest[6182:18700411] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 08:56:06.444 ThaliTest[6182:18700411] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 08:56:06.447 ThaliTest[6182:18700411] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CF05E57-D97E-402C-AFF2-240F49246F93/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-01 08:56:13.702 ThaliTest[6182:18700171] THREAD WARNING: ['JXcore'] took '6887.194824' ms. Plugin should use a background thread.
2016-07-01 08:56:13.702 ThaliTest[6182:18700171] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 08:56:13.702 ThaliTest[6182:18700171] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore316130832","JXcore","Test",[]]

```
