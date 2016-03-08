#### Test 60124347d4f5b03_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EEB77A80-6A19-4EF9-BD94-E95CE1855F0A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EEB77A80-6A19-4EF9-BD94-E95CE1855F0A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51890"
,(lldb)     command script import "/tmp/EEB77A80-6A19-4EF9-BD94-E95CE1855F0A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 02:11:23.251 ThaliTest[875:1274135] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3A59D341-2085-4E42-9AC7-479CCAF7D6A7/Library/Cookies/Cookies.binarycookies
,2016-03-08 02:11:23.621 ThaliTest[875:1274135] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-08 02:11:23.623 ThaliTest[875:1274135] Multi-tasking -> Device: YES, App: YES
,2016-03-08 02:11:23.645 ThaliTest[875:1274135] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 02:11:25.637 ThaliTest[875:1274135] Using UIWebView
,2016-03-08 02:11:25.648 ThaliTest[875:1274135] [CDVTimer][handleopenurl] 0.542998ms
,2016-03-08 02:11:25.657 ThaliTest[875:1274135] [CDVTimer][intentandnavigationfilter] 8.856952ms
2016-03-08 02:11:25.658 ThaliTest[875:1274135] [CDVTimer][gesturehandler] 0.420988ms
2016-03-08 02:11:25.659 ThaliTest[875:1274135] [CDVTimer][TotalPluginStar,tup] 11.874020ms
,2016-03-08 02:11:32.872 ThaliTest[875:1274135] Resetting plugins due to page load.
,2016-03-08 02:11:36.790 ThaliTest[875:1274135] Finished load of: file:///var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/index.html
,2016-03-08 02:11:37.025 ThaliTest[875:1274135] JXcore Cordova plugin initializing
,2016-03-08 02:11:37.027 ThaliTest[875:1274372] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-08 02:11:45.792 ThaliTest[875:1274372] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-08 02:11:45.793 ThaliTest[875:1274372] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-08 02:11:45.793 ThaliTest[875:1274372] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-08 02:11:45.796 ThaliTest[875:1274372] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4536641F-EDD2-4DA3-8950-CC0A7F65F849/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
