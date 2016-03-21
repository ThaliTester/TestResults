#### Test 62548124bd1cdb6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B8A8CA15-CCDD-40FA-9593-004280FE1307/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B8A8CA15-CCDD-40FA-9593-004280FE1307/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53527"
,(lldb)     command script import "/tmp/B8A8CA15-CCDD-40FA-9593-004280FE1307/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 07:31:46.853 ThaliTest[1885:3231869] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4D521832-A351-4A2B-A0AA-B7DF81E8541A/Library/Cookies/Cookies.binarycookies
,2016-03-21 07:31:47.323 ThaliTest[1885:3231869] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 07:31:47.325 ThaliTest[1885:3231869] Multi-tasking -> Device: YES, App: YES
,2016-03-21 07:31:47.351 ThaliTest[1885:3231869] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 07:31:49.208 ThaliTest[1885:3231869] Using UIWebView
,2016-03-21 07:31:49.219 ThaliTest[1885:3231869] [CDVTimer][handleopenurl] 0.519991ms
,2016-03-21 07:31:49.227 ThaliTest[1885:3231869] [CDVTimer][intentandnavigationfilter] 8.096993ms
2016-03-21 07:31:49.228 ThaliTest[1885:3231869] [CDVTimer][gesturehandler] 0.370026ms
2016-03-21 07:31:49.229 ThaliTest[1885:3231869] [CDVTimer][TotalPluginS,tartup] 10.981977ms
,2016-03-21 07:31:55.434 ThaliTest[1885:3231869] Resetting plugins due to page load.
,2016-03-21 07:31:58.690 ThaliTest[1885:3231869] Finished load of: file:///var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/index.html
,2016-03-21 07:31:58.924 ThaliTest[1885:3231869] JXcore Cordova plugin initializing
2016-03-21 07:31:58.926 ThaliTest[1885:3232077] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 07:32:07.555 ThaliTest[1885:3232077] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:32:07.556 ThaliTest[1885:3232077] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:32:07.556 ThaliTest[1885:3232077] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:32:07.559 ThaliTest[1885:3232077] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/436FE1A7-6D86-403A-A440-496F82F7A868/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 07:32:14.534 ThaliTest[1885:3231869] THREAD WARNING: ['JXcore'] took '6604.898926' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
