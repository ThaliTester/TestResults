#### Test 60124347d4f5b03_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3475B7C4-4BA7-4058-A724-B423A7FCD9EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3475B7C4-4BA7-4058-A724-B423A7FCD9EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347d4f5b03/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51885"
,(lldb)     command script import "/tmp/3475B7C4-4BA7-4058-A724-B423A7FCD9EC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 02:11:23.287 ThaliTest[876:1285842] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/53B2659A-A55E-4189-A24E-300B3D8286E1/Library/Cookies/Cookies.binarycookies
,2016-03-08 02:11:23.653 ThaliTest[876:1285842] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-08 02:11:23.655 ThaliTest[876:1285842] Multi-tasking -> Device: YES, App: YES
,2016-03-08 02:11:23.673 ThaliTest[876:1285842] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 02:11:25.581 ThaliTest[876:1285842] Using UIWebView
,2016-03-08 02:11:25.590 ThaliTest[876:1285842] [CDVTimer][handleopenurl] 0.483990ms
,2016-03-08 02:11:25.597 ThaliTest[876:1285842] [CDVTimer][intentandnavigationfilter] 6.556034ms
,2016-03-08 02:11:25.598 ThaliTest[876:1285842] [CDVTimer][gesturehandler] 0.342011ms
,2016-03-08 02:11:25.598 ThaliTest[876:1285842] [CDVTimer][TotalPluginStartup] 8.944988ms
,2016-03-08 02:11:33.242 ThaliTest[876:1285842] Resetting plugins due to page load.
,2016-03-08 02:11:36.959 ThaliTest[876:1285842] Finished load of: file:///var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/index.html
,2016-03-08 02:11:37.169 ThaliTest[876:1285842] JXcore Cordova plugin initializing
,2016-03-08 02:11:37.170 ThaliTest[876:1286109] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-08 02:11:43.778 ThaliTest[876:1286109] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-08 02:11:43.778 ThaliTest[876:1286109] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-08 02:11:43.778 ThaliTest[876:1286109] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

2016-03-08 02:11:43.781 ThaliTest[876:1286109] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7ED47311-7D21-460B-B3F5-7688FC037B18/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
