#### Test 625481240f1d9b8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2D3FEFD2-7557-4793-846C-94513BA8D778/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D3FEFD2-7557-4793-846C-94513BA8D778/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54445"
,(lldb)     command script import "/tmp/2D3FEFD2-7557-4793-846C-94513BA8D778/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 16:43:53.512 ThaliTest[1941:3295071] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EDFCBAF8-B7D9-40B8-80BA-6AF87FF3D025/Library/Cookies/Cookies.binarycookies
,2016-03-21 16:43:53.868 ThaliTest[1941:3295071] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 16:43:53.870 ThaliTest[1941:3295071] Multi-tasking -> Device: YES, App: YES
,2016-03-21 16:43:53.894 ThaliTest[1941:3295071] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 16:43:55.883 ThaliTest[1941:3295071] Using UIWebView
,2016-03-21 16:43:55.891 ThaliTest[1941:3295071] [CDVTimer][handleopenurl] 0.894964ms
,2016-03-21 16:43:55.900 ThaliTest[1941:3295071] [CDVTimer][intentandnavigationfilter] 7.955015ms
2016-03-21 16:43:55.901 ThaliTest[1941:3295071] [CDVTimer][gesturehandler] 0.571966ms
2016-03-21 16:43:55.902 ThaliTest[1941:3295071] [CDVTimer][TotalPluginS,tartup] 11.332989ms
,2016-03-21 16:44:02.710 ThaliTest[1941:3295071] Resetting plugins due to page load.
,2016-03-21 16:44:06.408 ThaliTest[1941:3295071] Finished load of: file:///var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/index.html
,2016-03-21 16:44:06.659 ThaliTest[1941:3295071] JXcore Cordova plugin initializing
,2016-03-21 16:44:06.661 ThaliTest[1941:3295308] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 16:44:15.384 ThaliTest[1941:3295308] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 16:44:15.385 ThaliTest[1941:3295308] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 16:44:15.386 ThaliTest[1941:3295308] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 16:44:15.388 ThaliTest[1941:3295308] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D16266A3-26D7-4F44-B045-7A5D4F23DC02/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 16:44:22.418 ThaliTest[1941:3295071] THREAD WARNING: ['JXcore'] took '6655.946533' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
