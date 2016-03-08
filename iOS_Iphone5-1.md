#### Test 60124347d4f5b03_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A0EC277B-059A-4920-A70A-9ABC7EFA03CD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A0EC277B-059A-4920-A70A-9ABC7EFA03CD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51860"
,(lldb)     command script import "/tmp/A0EC277B-059A-4920-A70A-9ABC7EFA03CD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 02:10:14.635 ThaliTest[688:1369568] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F1F2364-5291-4246-AE13-F5F007A0EB2E/Library/Cookies/Cookies.binarycookies
,2016-03-08 02:10:14.761 ThaliTest[688:1369568] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-08 02:10:14.763 ThaliTest[688:1369568] Multi-tasking -> Device: YES, App: YES
,2016-03-08 02:10:14.785 ThaliTest[688:1369568] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 02:10:16.867 ThaliTest[688:1369568] Using UIWebView
,2016-03-08 02:10:16.872 ThaliTest[688:1369568] [CDVTimer][handleopenurl] 0.387013ms
,2016-03-08 02:10:16.877 ThaliTest[688:1369568] [CDVTimer][intentandnavigationfilter] 5.136013ms
2016-03-08 02:10:16.878 ThaliTest[688:1369568] [CDVTimer][gesturehandler] 0.259995ms
2016-03-08 02:10:16.878 ThaliTest[688:1369568] [CDVTimer][TotalPluginStartup] 6.810963ms
,2016-03-08 02:10:25.120 ThaliTest[688:1369568] Resetting plugins due to page load.
,2016-03-08 02:10:29.230 ThaliTest[688:1369568] Finished load of: file:///var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/index.html
,2016-03-08 02:10:29.432 ThaliTest[688:1369568] JXcore Cordova plugin initializing
,2016-03-08 02:10:29.433 ThaliTest[688:1369733] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-08 02:10:46.402 ThaliTest[688:1369733] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-08 02:10:46.403 ThaliTest[688:1369733] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-08 02:10:46.403 ThaliTest[688:1369733] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-08 02:10:46.409 ThaliTest[688:1369733] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/55C781E1-C047-4EC7-ADA8-2A1789372B72/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
