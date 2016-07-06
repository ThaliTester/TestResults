#### Test 721454315fe531f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/721454315fe531f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8E08E641-3878-43D1-AAFC-6D9E8FAC04A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8E08E641-3878-43D1-AAFC-6D9E8FAC04A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/721454315fe531f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/721454315fe531f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50598"
,(lldb)     command script import "/tmp/8E08E641-3878-43D1-AAFC-6D9E8FAC04A5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 10:28:51.333 ThaliTest[6456:19486465] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2AF39C77-E075-4E7F-9077-2AFA23B031E2/Library/Cookies/Cookies.binarycookies
,2016-07-06 10:28:51.589 ThaliTest[6456:19486465] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 10:28:51.590 ThaliTest[6456:19486465] Multi-tasking -> Device: YES, App: YES
,2016-07-06 10:28:51.609 ThaliTest[6456:19486465] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 10:28:52.433 ThaliTest[6456:19486465] Using UIWebView
2016-07-06 10:28:52.436 ThaliTest[6456:19486465] [CDVTimer][handleopenurl] 0.169992ms
,2016-07-06 10:28:52.440 ThaliTest[6456:19486465] [CDVTimer][intentandnavigationfilter] 3.925025ms
2016-07-06 10:28:52.440 ThaliTest[6456:19486465] [CDVTimer][gesturehandler] 0.149965ms
2016-07-06 10:28:52.440 ThaliTest[6456:19486465] [CDVTimer][TotalPluginStartup] 4.858017ms
,2016-07-06 10:28:55.754 ThaliTest[6456:19486465] Resetting plugins due to page load.
,2016-07-06 10:28:57.117 ThaliTest[6456:19486465] Finished load of: file:///var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/index.html
,2016-07-06 10:28:57.314 ThaliTest[6456:19486465] JXcore Cordova plugin initializing
,2016-07-06 10:28:57.406 ThaliTest[6456:19486620] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 10:29:06.018 ThaliTest[6456:19486620] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-06 10:29:06.020 ThaliTest[6456:19486620] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-06 10:29:06.020 ThaliTest[6456:19486620] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-06 10:29:06.023 ThaliTest[6456:19486620] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/96432164-5210-4A4D-8B89-74F65E5FCEF3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,appEnteringBackground wasn't registered

```
