#### Test 64613803adf70b9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/3E442050-3054-499A-B646-77A18576D84A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3E442050-3054-499A-B646-77A18576D84A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803adf70b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49844"
,(lldb)     command script import "/tmp/3E442050-3054-499A-B646-77A18576D84A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 16:26:40.578 ThaliTest[2592:4740942] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CE1CCE6F-65E7-4DFB-B262-A5C74F2B3E26/Library/Cookies/Cookies.binarycookies
,2016-03-31 16:26:40.838 ThaliTest[2592:4740942] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 16:26:40.839 ThaliTest[2592:4740942] Multi-tasking -> Device: YES, App: YES
,2016-03-31 16:26:40.858 ThaliTest[2592:4740942] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 16:26:41.669 ThaliTest[2592:4740942] Using UIWebView
2016-03-31 16:26:41.672 ThaliTest[2592:4740942] [CDVTimer][handleopenurl] 0.154972ms
,2016-03-31 16:26:41.676 ThaliTest[2592:4740942] [CDVTimer][intentandnavigationfilter] 3.812969ms
2016-03-31 16:26:41.676 ThaliTest[2592:4740942] [CDVTimer][gesturehandler] 0.138998ms
2016-03-31 16:26:41.676 ThaliTest[2592:4740942] [CDVTimer][TotalPluginS,tartup] 4.730999ms
,2016-03-31 16:26:44.913 ThaliTest[2592:4740942] Resetting plugins due to page load.
,2016-03-31 16:26:46.399 ThaliTest[2592:4740942] Finished load of: file:///var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/index.html
,2016-03-31 16:26:46.586 ThaliTest[2592:4740942] JXcore Cordova plugin initializing
,2016-03-31 16:26:46.589 ThaliTest[2592:4741120] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 16:26:54.962 ThaliTest[2592:4741120] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 16:26:54.963 ThaliTest[2592:4741120] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 16:26:54.963 ThaliTest[2592:4,741120] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 16:26:54.964 ThaliTest[2592:4741120] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D3EA30E2-9859-494A-BCEF-A9D6B8918CAE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
