#### Test 721454313afe4e8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/721454313afe4e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/EDC78EEC-160F-41BF-922A-526DC138A6CF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EDC78EEC-160F-41BF-922A-526DC138A6CF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/721454313afe4e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/721454313afe4e8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59038"
,(lldb)     command script import "/tmp/EDC78EEC-160F-41BF-922A-526DC138A6CF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-06 13:13:58.207 ThaliTest[5186:14697311] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A51E2997-EA42-4539-AE85-C15EF8ED7E26/Library/Cookies/Cookies.binarycookies
,2016-06-06 13:13:58.467 ThaliTest[5186:14697311] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-06 13:13:58.469 ThaliTest[5186:14697311] Multi-tasking -> Device: YES, App: YES
,2016-06-06 13:13:58.487 ThaliTest[5186:14697311] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-06 13:13:59.317 ThaliTest[5186:14697311] Using UIWebView
,2016-06-06 13:13:59.321 ThaliTest[5186:14697311] [CDVTimer][handleopenurl] 0.193000ms
,2016-06-06 13:13:59.324 ThaliTest[5186:14697311] [CDVTimer][intentandnavigationfilter] 2.803981ms
2016-06-06 13:13:59.324 ThaliTest[5186:14697311] [CDVTimer][gesturehandler] 0.137031ms
2016-06-06 13:13:59.324 ThaliTest[5186:14697311] [CDVTimer][TotalPluginStartup] 3.841996ms
,2016-06-06 13:14:02.620 ThaliTest[5186:14697311] Resetting plugins due to page load.
,2016-06-06 13:14:04.145 ThaliTest[5186:14697311] Finished load of: file:///var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/index.html
,2016-06-06 13:14:04.155 ThaliTest[5186:14697311] JXcore Cordova plugin initializing
2016-06-06 13:14:04.156 ThaliTest[5186:14697449] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-06 13:14:13.034 ThaliTest[5186:14697449] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-06 13:14:13.034 ThaliTest[5186:14697449] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-06 13:14:13.035 ThaliTest[5186:14697449] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-06-06 13:14:13.038 ThaliTest[5186:14697449] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBCD8A6F-4A14-44AD-A267-D214D0CC3B29/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
