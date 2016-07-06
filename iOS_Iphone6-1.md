#### Test 72145431aac82a0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431aac82a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AC7A55DC-CE0D-4AD4-B204-724BD70BC3A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AC7A55DC-CE0D-4AD4-B204-724BD70BC3A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431aac82a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431aac82a0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50538"
,(lldb)     command script import "/tmp/AC7A55DC-CE0D-4AD4-B204-724BD70BC3A6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 08:20:41.838 ThaliTest[6364:19816651] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/602EB6BA-CFF9-4AC8-A98B-3177CA4CAEEC/Library/Cookies/Cookies.binarycookies
,2016-07-06 08:20:42.066 ThaliTest[6364:19816651] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 08:20:42.067 ThaliTest[6364:19816651] Multi-tasking -> Device: YES, App: YES
,2016-07-06 08:20:42.082 ThaliTest[6364:19816651] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 08:20:42.844 ThaliTest[6364:19816651] Using UIWebView
2016-07-06 08:20:42.846 ThaliTest[6364:19816651] [CDVTimer][handleopenurl] 0.129998ms
2016-07-06 08:20:42.849 ThaliTest[6364:19816651] [CDVTimer][intentandnavigationfilter] 2.112031ms
2016,-07-06 08:20:42.849 ThaliTest[6364:19816651] [CDVTimer][gesturehandler] 0.096023ms
2016-07-06 08:20:42.849 ThaliTest[6364:19816651] [CDVTimer][TotalPluginStartup] 2.758980ms
,2016-07-06 08:20:46.037 ThaliTest[6364:19816651] Resetting plugins due to page load.
,2016-07-06 08:20:47.445 ThaliTest[6364:19816651] Finished load of: file:///var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/index.html
,2016-07-06 08:20:47.602 ThaliTest[6364:19816651] JXcore Cordova plugin initializing
2016-07-06 08:20:47.603 ThaliTest[6364:19816822] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-06 08:20:54.658 ThaliTest[6364:19816822] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-07-06 08:20:54.659 ThaliTest[6364:19816822] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-07-06 08:20:54.659 ThaliTest[6364:19816822] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-06 08:20:54.662 ThaliTest[6364:19816822] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D607E9A-AA75-4C01-BE12-E80FFD72C82A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
