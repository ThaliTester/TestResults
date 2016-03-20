#### Test 62548124ece3ba0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7AE95307-3DA7-4D5E-B647-1288191C4F04/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7AE95307-3DA7-4D5E-B647-1288191C4F04/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124ece3ba0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53359"
,(lldb)     command script import "/tmp/7AE95307-3DA7-4D5E-B647-1288191C4F04/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 17:19:10.311 ThaliTest[1881:3127917] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D5050A2-DA0D-4D93-B4D8-10A9A556AE29/Library/Cookies/Cookies.binarycookies
,2016-03-20 17:19:10.723 ThaliTest[1881:3127917] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 17:19:10.725 ThaliTest[1881:3127917] Multi-tasking -> Device: YES, App: YES
,2016-03-20 17:19:10.744 ThaliTest[1881:3127917] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 17:19:12.726 ThaliTest[1881:3127917] Using UIWebView
,2016-03-20 17:19:12.733 ThaliTest[1881:3127917] [CDVTimer][handleopenurl] 0.450015ms
,2016-03-20 17:19:12.741 ThaliTest[1881:3127917] [CDVTimer][intentandnavigationfilter] 7.220030ms
,2016-03-20 17:19:12.741 ThaliTest[1881:3127917] [CDVTimer][gesturehandler] 0.348985ms
,2016-03-20 17:19:12.742 ThaliTest[1881:3127917] [CDVTimer][TotalPluginStartup] 9.743989ms
,2016-03-20 17:19:20.315 ThaliTest[1881:3127917] Resetting plugins due to page load.
,2016-03-20 17:19:23.935 ThaliTest[1881:3127917] Finished load of: file:///var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/index.html
,2016-03-20 17:19:24.138 ThaliTest[1881:3127917] JXcore Cordova plugin initializing
,2016-03-20 17:19:24.139 ThaliTest[1881:3128127] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 17:19:30.587 ThaliTest[1881:3128127] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 17:19:30.588 ThaliTest[1881:3128127] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 17:19:30.588 ThaliTest[1881:3128127] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 17:19:30.590 ThaliTest[1881:3128127] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/24F9918A-8E55-4B47-A9CC-C74E830D424F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 17:19:35.797 ThaliTest[1881:3127917] THREAD WARNING: ['JXcore'] took '4929.627197' ms. Plugin should use a background thread.

```
