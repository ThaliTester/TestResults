#### Test 62548124ece3ba0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/65FD8A24-003A-4FE5-84F4-B53AD6F93E15/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/65FD8A24-003A-4FE5-84F4-B53AD6F93E15/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53364"
,(lldb)     command script import "/tmp/65FD8A24-003A-4FE5-84F4-B53AD6F93E15/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-20 17:19:12.154 ThaliTest[1857:3144366] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/16AB2659-F410-461B-86AF-7AF32D2BA71D/Library/Cookies/Cookies.binarycookies
,2016-03-20 17:19:12.535 ThaliTest[1857:3144366] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 17:19:12.537 ThaliTest[1857:3144366] Multi-tasking -> Device: YES, App: YES
,2016-03-20 17:19:12.563 ThaliTest[1857:3144366] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 17:19:14.569 ThaliTest[1857:3144366] Using UIWebView
,2016-03-20 17:19:14.580 ThaliTest[1857:3144366] [CDVTimer][handleopenurl] 0.463009ms
,2016-03-20 17:19:14.589 ThaliTest[1857:3144366] [CDVTimer][intentandnavigationfilter] 7.974982ms
2016-03-20 17:19:14.590 ThaliTest[1857:3144366] [CDVTimer][gesturehandler] 0.407994ms
2016-03-20 17:19:14.590 ThaliTest[1857:3144366] [CDVTimer][TotalPluginS,tartup] 11.061013ms
,2016-03-20 17:19:21.701 ThaliTest[1857:3144366] Resetting plugins due to page load.
,2016-03-20 17:19:25.702 ThaliTest[1857:3144366] Finished load of: file:///var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/index.html
,2016-03-20 17:19:25.939 ThaliTest[1857:3144366] JXcore Cordova plugin initializing
,2016-03-20 17:19:25.941 ThaliTest[1857:3144585] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 17:19:34.596 ThaliTest[1857:3144585] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 17:19:34.598 ThaliTest[1857:3144585] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 17:19:34.598 ThaliTest[1857:3144585] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 17:19:34.600 ThaliTest[1857:3144585] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F4A4CAC9-4DD3-4FB4-9F14-175D3EE8A0B6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 17:19:41.595 ThaliTest[1857:3144366] THREAD WARNING: ['JXcore'] took '6620.356201' ms. Plugin should use a background thread.

```
