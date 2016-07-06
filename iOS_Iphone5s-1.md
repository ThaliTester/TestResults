#### Test 72145431eb52a3d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/15603FBC-9201-4AA2-B10A-8C2C72E73AB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/15603FBC-9201-4AA2-B10A-8C2C72E73AB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431eb52a3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50734"
,(lldb)     command script import "/tmp/15603FBC-9201-4AA2-B10A-8C2C72E73AB4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 12:14:55.900 ThaliTest[6467:19499344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/42B5E775-1389-4D2A-A193-AC7E2F994B2C/Library/Cookies/Cookies.binarycookies
,2016-07-06 12:14:56.152 ThaliTest[6467:19499344] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 12:14:56.153 ThaliTest[6467:19499344] Multi-tasking -> Device: YES, App: YES
,2016-07-06 12:14:56.170 ThaliTest[6467:19499344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 12:14:57.015 ThaliTest[6467:19499344] Using UIWebView
2016-07-06 12:14:57.017 ThaliTest[6467:19499344] [CDVTimer][handleopenurl] 0.163019ms
,2016-07-06 12:14:57.021 ThaliTest[6467:19499344] [CDVTimer][intentandnavigationfilter] 3.686011ms
2016-07-06 12:14:57.022 ThaliTest[6467:19499344] [CDVTimer][gesturehandler] 0.172019ms
2016-07-06 12:14:57.022 ThaliTest[6467:19499344] [CDVTimer][TotalPlug,inStartup] 4.647970ms
,2016-07-06 12:15:00.397 ThaliTest[6467:19499344] Resetting plugins due to page load.
,2016-07-06 12:15:01.750 ThaliTest[6467:19499344] Finished load of: file:///var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/index.html
,2016-07-06 12:15:01.929 ThaliTest[6467:19499344] JXcore Cordova plugin initializing
,2016-07-06 12:15:01.931 ThaliTest[6467:19499491] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 12:15:10.572 ThaliTest[6467:19499491] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-06 12:15:10.573 ThaliTest[6467:19499491] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-06 12:15:10.573 ThaliTest[6467:19499491] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-06 12:15:10.575 ThaliTest[6467:19499491] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AB3D6E20-3E78-4076-85F3-E4E9EAE259EE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,appEnteredForeground wasn't registered

```
