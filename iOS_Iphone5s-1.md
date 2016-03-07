#### Test 6012434797f7ca7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/77F86AD7-9DA0-4BE9-86DB-2DAE9FE2FC61/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/77F86AD7-9DA0-4BE9-86DB-2DAE9FE2FC61/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434797f7ca7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51749"
,(lldb)     command script import "/tmp/77F86AD7-9DA0-4BE9-86DB-2DAE9FE2FC61/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 20:27:48.549 ThaliTest[861:1238176] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B850A947-6DC1-41B6-B95A-57284A7C6A76/Library/Cookies/Cookies.binarycookies
,2016-03-07 20:27:48.916 ThaliTest[861:1238176] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 20:27:48.917 ThaliTest[861:1238176] Multi-tasking -> Device: YES, App: YES
,2016-03-07 20:27:48.940 ThaliTest[861:1238176] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 20:27:50.656 ThaliTest[861:1238176] Using UIWebView
,2016-03-07 20:27:50.667 ThaliTest[861:1238176] [CDVTimer][handleopenurl] 0.546992ms
,2016-03-07 20:27:50.676 ThaliTest[861:1238176] [CDVTimer][intentandnavigationfilter] 8.183002ms
2016-03-07 20:27:50.677 ThaliTest[861:1238176] [CDVTimer][gesturehandler] 0.371993ms
2016-03-07 20:27:50.678 ThaliTest[861:1238176] [CDVTimer][TotalPluginStartup] 11.876047ms
,2016-03-07 20:27:57.733 ThaliTest[861:1238176] Resetting plugins due to page load.
,2016-03-07 20:28:01.746 ThaliTest[861:1238176] Finished load of: file:///var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/index.html
,2016-03-07 20:28:01.932 ThaliTest[861:1238176] JXcore Cordova plugin initializing
,2016-03-07 20:28:01.934 ThaliTest[861:1238436] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 20:28:10.579 ThaliTest[861:1238436] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 20:28:10.580 ThaliTest[861:1238436] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 20:28:10.580 ThaliTest[861:1238436] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-07 20:28:10.583 ThaliTest[861:1238436] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/89AF7E51-430A-44A1-B49D-EB7A555362FB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
