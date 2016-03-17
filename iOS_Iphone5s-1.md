#### Test 62509094764c200_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3FE5672E-605F-47A3-982A-4DE2FD52DEF0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3FE5672E-605F-47A3-982A-4DE2FD52DEF0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50955"
,(lldb)     command script import "/tmp/3FE5672E-605F-47A3-982A-4DE2FD52DEF0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 06:43:39.559 ThaliTest[1617:2622826] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/83696E23-F83D-45F7-8AA1-E8FD5E711B9A/Library/Cookies/Cookies.binarycookies
,2016-03-17 06:43:39.921 ThaliTest[1617:2622826] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 06:43:39.922 ThaliTest[1617:2622826] Multi-tasking -> Device: YES, App: YES
,2016-03-17 06:43:39.945 ThaliTest[1617:2622826] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 06:43:41.579 ThaliTest[1617:2622826] Using UIWebView
,2016-03-17 06:43:41.590 ThaliTest[1617:2622826] [CDVTimer][handleopenurl] 0.505984ms
,2016-03-17 06:43:41.599 ThaliTest[1617:2622826] [CDVTimer][intentandnavigationfilter] 8.504987ms
2016-03-17 06:43:41.600 ThaliTest[1617:2622826] [CDVTimer][gesturehandler] 0.413001ms
2016-03-17 06:43:41.601 ThaliTest[1617:2622826] [CDVTimer][TotalPluginS,tartup] 11.344016ms
,2016-03-17 06:43:47.853 ThaliTest[1617:2622826] Resetting plugins due to page load.
,2016-03-17 06:43:50.937 ThaliTest[1617:2622826] Finished load of: file:///var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/index.html
,2016-03-17 06:43:51.181 ThaliTest[1617:2622826] JXcore Cordova plugin initializing
,2016-03-17 06:43:51.183 ThaliTest[1617:2623048] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-17 06:43:56.207 ThaliTest[1617:2623048] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 06:43:56.207 ThaliTest[1617:2623048] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 06:43:56.207 ThaliTest[1617:2623048] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-17 06:43:56.211 ThaliTest[1617:2623048] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AA67E9-5F12-4556-B7F0-89F974AD7BB6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-17 06:44:06.638 ThaliTest[1617:2622826] THREAD WARNING: ['JXcore'] took '7488.730225' ms. Plugin should use a background thread.

```
