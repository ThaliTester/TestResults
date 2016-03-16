#### Test 630369953a3bebd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/630369953a3bebd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8DACBF9D-9612-46C8-AA4E-4407CFD7DE03/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8DACBF9D-9612-46C8-AA4E-4407CFD7DE03/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/630369953a3bebd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/630369953a3bebd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50447"
,(lldb)     command script import "/tmp/8DACBF9D-9612-46C8-AA4E-4407CFD7DE03/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 11:16:48.764 ThaliTest[1561:2502385] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2343C162-8F10-4828-8895-94FCCDE45516/Library/Cookies/Cookies.binarycookies
,2016-03-16 11:16:49.140 ThaliTest[1561:2502385] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 11:16:49.141 ThaliTest[1561:2502385] Multi-tasking -> Device: YES, App: YES
,2016-03-16 11:16:49.162 ThaliTest[1561:2502385] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 11:16:50.902 ThaliTest[1561:2502385] Using UIWebView
,2016-03-16 11:16:50.910 ThaliTest[1561:2502385] [CDVTimer][handleopenurl] 0.432014ms
,2016-03-16 11:16:50.918 ThaliTest[1561:2502385] [CDVTimer][intentandnavigationfilter] 7.915974ms
2016-03-16 11:16:50.919 ThaliTest[1561:2502385] [CDVTimer][gesturehandler] 0.405014ms
2016-03-16 11:16:50.920 ThaliTest[1561:2502385] [CDVTimer][TotalPluginStartup] 10.582983ms
,2016-03-16 11:16:58.141 ThaliTest[1561:2502385] Resetting plugins due to page load.
,2016-03-16 11:17:02.176 ThaliTest[1561:2502385] Finished load of: file:///var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/index.html
,2016-03-16 11:17:02.366 ThaliTest[1561:2502385] JXcore Cordova plugin initializing
,2016-03-16 11:17:02.368 ThaliTest[1561:2502619] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-16 11:17:17.980 ThaliTest[1561:2502619] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 11:17:17.981 ThaliTest[1561:2502619] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 11:17:17.981 ThaliTest[1561:2502619] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 11:17:17.983 ThaliTest[1561:2502619] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3D07CA4B-DF8D-4366-92AE-86AF6754BB19/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
