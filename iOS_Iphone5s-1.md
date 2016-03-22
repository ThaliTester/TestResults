#### Test 63680118d4cb974_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/66BC6358-ADF5-40C8-B90D-38971DAC1957/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/66BC6358-ADF5-40C8-B90D-38971DAC1957/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54800"
,(lldb)     command script import "/tmp/66BC6358-ADF5-40C8-B90D-38971DAC1957/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 14:36:40.976 ThaliTest[1993:3431991] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E508439F-79DC-4242-8B14-5470BC3A6AA7/Library/Cookies/Cookies.binarycookies
,2016-03-22 14:36:41.369 ThaliTest[1993:3431991] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 14:36:41.370 ThaliTest[1993:3431991] Multi-tasking -> Device: YES, App: YES
,2016-03-22 14:36:41.393 ThaliTest[1993:3431991] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 14:36:43.373 ThaliTest[1993:3431991] Using UIWebView
,2016-03-22 14:36:43.382 ThaliTest[1993:3431991] [CDVTimer][handleopenurl] 0.494003ms
,2016-03-22 14:36:43.390 ThaliTest[1993:3431991] [CDVTimer][intentandnavigationfilter] 8.170009ms
2016-03-22 14:36:43.391 ThaliTest[1993:3431991] [CDVTimer][gesturehandler] 0.395000ms
2016-03-22 14:36:43.392 ThaliTest[1993:3431991] [CDVTimer][TotalPluginS,tartup] 10.955036ms
,2016-03-22 14:36:50.489 ThaliTest[1993:3431991] Resetting plugins due to page load.
,2016-03-22 14:36:54.446 ThaliTest[1993:3431991] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/index.html
,2016-03-22 14:36:54.714 ThaliTest[1993:3431991] JXcore Cordova plugin initializing
,2016-03-22 14:36:54.715 ThaliTest[1993:3432215] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 14:37:03.456 ThaliTest[1993:3432215] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:37:03.457 ThaliTest[1993:3432215] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:37:03.458 ThaliTest[1993:3432215] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:37:03.460 ThaliTest[1993:3432215] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA680E6C-4E59-4596-A0DA-57EDFF5C8F80/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 14:37:10.487 ThaliTest[1993:3431991] THREAD WARNING: ['JXcore'] took '6659.024902' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
