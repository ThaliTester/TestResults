#### Test 62548124e8057a0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AEA85EEA-23DC-4A2B-A36D-B6E7F425CAD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AEA85EEA-23DC-4A2B-A36D-B6E7F425CAD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124e8057a0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54262"
,(lldb)     command script import "/tmp/AEA85EEA-23DC-4A2B-A36D-B6E7F425CAD6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 14:20:53.598 ThaliTest[1955:3261996] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF1189FE-E543-4D21-A76D-2A0EF29D50A3/Library/Cookies/Cookies.binarycookies
,2016-03-21 14:20:53.963 ThaliTest[1955:3261996] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 14:20:53.964 ThaliTest[1955:3261996] Multi-tasking -> Device: YES, App: YES
,2016-03-21 14:20:53.982 ThaliTest[1955:3261996] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 14:20:55.825 ThaliTest[1955:3261996] Using UIWebView
,2016-03-21 14:20:55.832 ThaliTest[1955:3261996] [CDVTimer][handleopenurl] 0.479996ms
,2016-03-21 14:20:55.839 ThaliTest[1955:3261996] [CDVTimer][intentandnavigationfilter] 6.673038ms
,2016-03-21 14:20:55.840 ThaliTest[1955:3261996] [CDVTimer][gesturehandler] 0.308990ms
,2016-03-21 14:20:55.840 ThaliTest[1955:3261996] [CDVTimer][TotalPluginStartup] 9.029984ms
,2016-03-21 14:21:02.907 ThaliTest[1955:3261996] Resetting plugins due to page load.
,2016-03-21 14:21:06.568 ThaliTest[1955:3261996] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/index.html
,2016-03-21 14:21:06.756 ThaliTest[1955:3261996] JXcore Cordova plugin initializing
,2016-03-21 14:21:06.757 ThaliTest[1955:3262216] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 14:21:13.228 ThaliTest[1955:3262216] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 14:21:13.228 ThaliTest[1955:3262216] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 14:21:13.228 ThaliTest[1955:3262216] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 14:21:13.230 ThaliTest[1955:3262216] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB20FA3F-7FFC-4339-AC63-6D3D6358A05F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 14:21:18.447 ThaliTest[1955:3261996] THREAD WARNING: ['JXcore'] took '4942.018799' ms. Plugin should use a background thread.

```
