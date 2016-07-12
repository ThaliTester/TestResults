#### Test 72145431744cc2c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F22CA48F-8988-467D-8327-3A648DAB629E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F22CA48F-8988-467D-8327-3A648DAB629E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52631"
,(lldb)     command script import "/tmp/F22CA48F-8988-467D-8327-3A648DAB629E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-12 11:34:31.178 ThaliTest[192:8361] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CCDF02FF-2E76-4B24-BAB9-E90D59B1F745/Library/Cookies/Cookies.binarycookies
,2016-07-12 11:34:31.738 ThaliTest[192:8361] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-12 11:34:31.740 ThaliTest[192:8361] Multi-tasking -> Device: YES, App: YES
,2016-07-12 11:34:31.767 ThaliTest[192:8361] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-12 11:34:33.895 ThaliTest[192:8361] Using UIWebView
,2016-07-12 11:34:33.902 ThaliTest[192:8361] [CDVTimer][handleopenurl] 0.367999ms
,2016-07-12 11:34:33.910 ThaliTest[192:8361] [CDVTimer][intentandnavigationfilter] 7.273972ms
,2016-07-12 11:34:33.910 ThaliTest[192:8361] [CDVTimer][gesturehandler] 0.307977ms
,2016-07-12 11:34:33.911 ThaliTest[192:8361] [CDVTimer][TotalPluginStartup] 9.449959ms
,2016-07-12 11:34:41.692 ThaliTest[192:8361] Resetting plugins due to page load.
,2016-07-12 11:34:45.654 ThaliTest[192:8361] Finished load of: file:///var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/index.html
,2016-07-12 11:34:45.894 ThaliTest[192:8361] JXcore Cordova plugin initializing
,2016-07-12 11:34:45.895 ThaliTest[192:8622] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-12 11:34:52.881 ThaliTest[192:8622] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-12 11:34:52.881 ThaliTest[192:8622] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-12 11:34:52.882 ThaliTest[192:8622] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-12 11:34:52.883 ThaliTest[192:8622] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/21A8B0CF-6C83-468C-BD17-E7482A30F29C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-12 11:34:58.868 ThaliTest[192:8361] THREAD WARNING: ['JXcore'] took '5704.704834' ms. Plugin should use a background thread.

```
