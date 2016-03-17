#### Test 63186632d456b18_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D07AB79C-04E9-48A2-BA64-736D8E85B696/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D07AB79C-04E9-48A2-BA64-736D8E85B696/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51297"
,(lldb)     command script import "/tmp/D07AB79C-04E9-48A2-BA64-736D8E85B696/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 09:49:00.845 ThaliTest[1668:2639926] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A5CFAFF7-9738-4C7A-979C-C2B2D1BC6CA5/Library/Cookies/Cookies.binarycookies
,2016-03-17 09:49:01.202 ThaliTest[1668:2639926] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 09:49:01.203 ThaliTest[1668:2639926] Multi-tasking -> Device: YES, App: YES
,2016-03-17 09:49:01.222 ThaliTest[1668:2639926] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 09:49:03.193 ThaliTest[1668:2639926] Using UIWebView
,2016-03-17 09:49:03.199 ThaliTest[1668:2639926] [CDVTimer][handleopenurl] 0.403047ms
,2016-03-17 09:49:03.207 ThaliTest[1668:2639926] [CDVTimer][intentandnavigationfilter] 7.443964ms
,2016-03-17 09:49:03.208 ThaliTest[1668:2639926] [CDVTimer][gesturehandler] 0.330985ms
,2016-03-17 09:49:03.209 ThaliTest[1668:2639926] [CDVTimer][TotalPluginStartup] 9.787023ms
,2016-03-17 09:49:10.249 ThaliTest[1668:2639926] Resetting plugins due to page load.
,2016-03-17 09:49:13.896 ThaliTest[1668:2639926] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/index.html
,2016-03-17 09:49:14.086 ThaliTest[1668:2639926] JXcore Cordova plugin initializing
,2016-03-17 09:49:14.088 ThaliTest[1668:2640140] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 09:49:17.874 ThaliTest[1668:2640140] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 09:49:17.874 ThaliTest[1668:2640140] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 09:49:17.874 ThaliTest[1668:2640140] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 09:49:17.877 ThaliTest[1668:2640140] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED4D59C8-2426-492B-A95F-607C24AF3E54/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 09:49:25.680 ThaliTest[1668:2639926] THREAD WARNING: ['JXcore'] took '5603.701904' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
