#### Test 7214543191b6842_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/AB898B10-8ED4-4D6C-ACF5-4B8710DC7B1F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AB898B10-8ED4-4D6C-ACF5-4B8710DC7B1F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58258"
,(lldb)     command script import "/tmp/AB898B10-8ED4-4D6C-ACF5-4B8710DC7B1F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-02 09:28:51.243 ThaliTest[5022:14086057] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4D377A18-C93E-4196-B226-902CA552F241/Library/Cookies/Cookies.binarycookies
,2016-06-02 09:28:51.503 ThaliTest[5022:14086057] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-02 09:28:51.504 ThaliTest[5022:14086057] Multi-tasking -> Device: YES, App: YES
,2016-06-02 09:28:51.523 ThaliTest[5022:14086057] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-02 09:28:52.347 ThaliTest[5022:14086057] Using UIWebView
,2016-06-02 09:28:52.351 ThaliTest[5022:14086057] [CDVTimer][handleopenurl] 0.183046ms
2016-06-02 09:28:52.354 ThaliTest[5022:14086057] [CDVTimer][intentandnavigationfilter] 2.629995ms
2016-06-02 09:28:52.354 ThaliTest[5022:14086057] [CDVTimer][gesturehan,dler] 0.133991ms
2016-06-02 09:28:52.354 ThaliTest[5022:14086057] [CDVTimer][TotalPluginStartup] 3.558040ms
,2016-06-02 09:28:55.640 ThaliTest[5022:14086057] Resetting plugins due to page load.
,2016-06-02 09:28:56.984 ThaliTest[5022:14086057] Finished load of: file:///var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/index.html
,2016-06-02 09:28:57.172 ThaliTest[5022:14086057] JXcore Cordova plugin initializing
,2016-06-02 09:28:57.173 ThaliTest[5022:14086218] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-02 09:29:05.831 ThaliTest[5022:14086218] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-02 09:29:05.831 ThaliTest[5022:14086218] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-02 09:29:05.832 ThaliTest[5022,:14086218] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-06-02 09:29:05.835 ThaliTest[5022:14086218] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/04F9D94B-A1E5-4E2F-A22E-706ABCA17307/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
