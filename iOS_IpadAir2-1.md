#### Test 72145431eb52a3d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B01D347A-3B55-41FB-87FD-32C02602457F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B01D347A-3B55-41FB-87FD-32C02602457F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50730"
,(lldb)     command script import "/tmp/B01D347A-3B55-41FB-87FD-32C02602457F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 12:14:54.108 ThaliTest[3754:13743636] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96633B38-E50F-4973-A226-39F5DA2476D3/Library/Cookies/Cookies.binarycookies
,2016-07-06 12:14:54.332 ThaliTest[3754:13743636] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 12:14:54.332 ThaliTest[3754:13743636] Multi-tasking -> Device: YES, App: YES
,2016-07-06 12:14:54.345 ThaliTest[3754:13743636] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 12:14:55.163 ThaliTest[3754:13743636] Using UIWebView
,2016-07-06 12:14:55.165 ThaliTest[3754:13743636] [CDVTimer][handleopenurl] 0.140011ms
,2016-07-06 12:14:55.167 ThaliTest[3754:13743636] [CDVTimer][intentandnavigationfilter] 1.902997ms
2016-07-06 12:14:55.167 ThaliTest[3754:13743636] [CDVTimer][gesturehandler] 0.093997ms
2016-07-06 12:14:55.167 ThaliTest[3754:13743636] [CDVTimer][TotalPlug,inStartup] 2.567053ms
,2016-07-06 12:14:58.341 ThaliTest[3754:13743636] Resetting plugins due to page load.
,2016-07-06 12:14:59.801 ThaliTest[3754:13743636] Finished load of: file:///var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/index.html
,2016-07-06 12:14:59.938 ThaliTest[3754:13743636] JXcore Cordova plugin initializing
2016-07-06 12:14:59.939 ThaliTest[3754:13743797] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 12:15:06.397 ThaliTest[3754:13743797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-06 12:15:06.397 ThaliTest[3754:13743797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-06 12:15:06.397 ThaliTest[3754:13743797] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-06 12:15:06.399 ThaliTest[3754:13743797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1D827C00-10CB-4ECA-869D-FE6F7A9A2619/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-06 12:15:11.598 ThaliTest[3754:13743636] THREAD WARNING: ['JXcore'] took '4930.468018' ms. Plugin should use a background thread.
,appEnteredForeground wasn't registered

```
