#### Test 72145431744cc2c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/FB28E6A1-9EEC-4B14-8138-93C4C2BF36CE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FB28E6A1-9EEC-4B14-8138-93C4C2BF36CE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431744cc2c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52637"
,(lldb)     command script import "/tmp/FB28E6A1-9EEC-4B14-8138-93C4C2BF36CE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-12 11:34:34.123 ThaliTest[201:9187] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE6095F9-6BA1-4299-9C25-2DAEE8C45E9B/Library/Cookies/Cookies.binarycookies
,2016-07-12 11:34:34.763 ThaliTest[201:9187] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-12 11:34:34.765 ThaliTest[201:9187] Multi-tasking -> Device: YES, App: YES
,2016-07-12 11:34:34.797 ThaliTest[201:9187] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-12 11:34:36.813 ThaliTest[201:9187] Using UIWebView
,2016-07-12 11:34:36.822 ThaliTest[201:9187] [CDVTimer][handleopenurl] 0.550985ms
,2016-07-12 11:34:36.832 ThaliTest[201:9187] [CDVTimer][intentandnavigationfilter] 9.431005ms
2016-07-12 11:34:36.833 ThaliTest[201:9187] [CDVTimer][gesturehandler] 0.391006ms
2016-07-12 11:34:36.834 ThaliTest[201:9187] [CDVTimer][TotalPluginStartup] 12.582004ms
,2016-07-12 11:34:44.423 ThaliTest[201:9187] Resetting plugins due to page load.
,2016-07-12 11:34:48.657 ThaliTest[201:9187] Finished load of: file:///var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/index.html
,2016-07-12 11:34:48.964 ThaliTest[201:9187] JXcore Cordova plugin initializing
,2016-07-12 11:34:48.965 ThaliTest[201:9413] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-12 11:34:58.240 ThaliTest[201:9413] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-12 11:34:58.241 ThaliTest[201:9413] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-12 11:34:58.242 ThaliTest[201:9413] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-12 11:34:58.244 ThaliTest[201:9413] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A352BDBF-9CB6-437D-985B-9FC01AE136BA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-12 11:35:06.161 ThaliTest[201:9187] THREAD WARNING: ['JXcore'] took '7551.479980' ms. Plugin should use a background thread.

```
