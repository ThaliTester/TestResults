#### Test 62509094c3ee53f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EA940C2D-D579-457E-B79C-906F5ED025F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EA940C2D-D579-457E-B79C-906F5ED025F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50345"
,(lldb)     command script import "/tmp/EA940C2D-D579-457E-B79C-906F5ED025F4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 10:38:03.044 ThaliTest[1553:2497105] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/884EB920-9B19-4A1C-BF5E-427239C6C5B0/Library/Cookies/Cookies.binarycookies
,2016-03-16 10:38:03.492 ThaliTest[1553:2497105] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 10:38:03.493 ThaliTest[1553:2497105] Multi-tasking -> Device: YES, App: YES
,2016-03-16 10:38:03.518 ThaliTest[1553:2497105] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 10:38:05.424 ThaliTest[1553:2497105] Using UIWebView
,2016-03-16 10:38:05.432 ThaliTest[1553:2497105] [CDVTimer][handleopenurl] 0.461996ms
,2016-03-16 10:38:05.440 ThaliTest[1553:2497105] [CDVTimer][intentandnavigationfilter] 7.992983ms
2016-03-16 10:38:05.441 ThaliTest[1553:2497105] [CDVTimer][gesturehandler] 0.382006ms
2016-03-16 10:38:05.442 ThaliTest[1553:2497105] [CDVTimer][TotalPluginS,tartup] 10.711014ms
,2016-03-16 10:38:12.458 ThaliTest[1553:2497105] Resetting plugins due to page load.
,2016-03-16 10:38:16.478 ThaliTest[1553:2497105] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/index.html
,2016-03-16 10:38:16.708 ThaliTest[1553:2497105] JXcore Cordova plugin initializing
,2016-03-16 10:38:16.709 ThaliTest[1553:2497323] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 10:38:21.844 ThaliTest[1553:2497323] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 10:38:21.844 ThaliTest[1553:2497323] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 10:38:21.844 ThaliTest[1553:2497323] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 10:38:21.848 ThaliTest[1553:2497323] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D47FBD3-2AB2-40F4-A53C-AFE4A7231130/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 10:38:32.432 ThaliTest[1553:2497105] THREAD WARNING: ['JXcore'] took '7593.811035' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
