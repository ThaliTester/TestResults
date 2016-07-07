#### Test 7214543179cc02a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543179cc02a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8B67B729-9037-4043-A27F-C10C48F86A4C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8B67B729-9037-4043-A27F-C10C48F86A4C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543179cc02a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543179cc02a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51102"
,(lldb)     command script import "/tmp/8B67B729-9037-4043-A27F-C10C48F86A4C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 12:09:49.799 ThaliTest[6522:19651918] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1051E5AA-3890-4D15-B132-E95A07244275/Library/Cookies/Cookies.binarycookies
,2016-07-07 12:09:50.061 ThaliTest[6522:19651918] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 12:09:50.062 ThaliTest[6522:19651918] Multi-tasking -> Device: YES, App: YES
,2016-07-07 12:09:50.081 ThaliTest[6522:19651918] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 12:09:50.912 ThaliTest[6522:19651918] Using UIWebView
,2016-07-07 12:09:50.916 ThaliTest[6522:19651918] [CDVTimer][handleopenurl] 0.172019ms
2016-07-07 12:09:50.919 ThaliTest[6522:19651918] [CDVTimer][intentandnavigationfilter] 2.632022ms
2016-07-07 12:09:50.919 ThaliTest[6522:19651918] [CDVTimer][gesturehan,dler] 0.115991ms
2016-07-07 12:09:50.919 ThaliTest[6522:19651918] [CDVTimer][TotalPluginStartup] 3.524005ms
,2016-07-07 12:09:54.204 ThaliTest[6522:19651918] Resetting plugins due to page load.
,2016-07-07 12:09:55.743 ThaliTest[6522:19651918] Finished load of: file:///var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/index.html
,2016-07-07 12:09:55.926 ThaliTest[6522:19651918] JXcore Cordova plugin initializing
,2016-07-07 12:09:56.019 ThaliTest[6522:19652075] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-07 12:10:04.568 ThaliTest[6522:19652075] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-07 12:10:04.569 ThaliTest[6522:19652075] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-07 12:10:04.569 ThaliTest[6522:19652075] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-07 12:10:04.572 ThaliTest[6522:19652075] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CDBEFA8-2055-48FD-A30C-4E1D6C1002C0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
