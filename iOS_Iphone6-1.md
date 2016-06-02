#### Test 7214543191b6842_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0FD0F163-3125-47CF-AC7D-6347AF991BCD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0FD0F163-3125-47CF-AC7D-6347AF991BCD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58256"
,(lldb)     command script import "/tmp/0FD0F163-3125-47CF-AC7D-6347AF991BCD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-02 09:28:47.343 ThaliTest[5023:14315415] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7167C2DB-692A-4030-82CA-1C20034049FF/Library/Cookies/Cookies.binarycookies
,2016-06-02 09:28:47.576 ThaliTest[5023:14315415] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-02 09:28:47.577 ThaliTest[5023:14315415] Multi-tasking -> Device: YES, App: YES
,2016-06-02 09:28:47.594 ThaliTest[5023:14315415] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-02 09:28:48.374 ThaliTest[5023:14315415] Using UIWebView
,2016-06-02 09:28:48.376 ThaliTest[5023:14315415] [CDVTimer][handleopenurl] 0.138998ms
,2016-06-02 09:28:48.379 ThaliTest[5023:14315415] [CDVTimer][intentandnavigationfilter] 2.345979ms
2016-06-02 09:28:48.379 ThaliTest[5023:14315415] [CDVTimer][gesturehandler] 0.111043ms
2016-06-02 09:28:48.379 ThaliTest[5023:14315415] [CDVTimer][TotalPlug,inStartup] 3.113985ms
,2016-06-02 09:28:51.498 ThaliTest[5023:14315415] Resetting plugins due to page load.
,2016-06-02 09:28:52.938 ThaliTest[5023:14315415] Finished load of: file:///var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/index.html
,2016-06-02 09:28:53.103 ThaliTest[5023:14315415] JXcore Cordova plugin initializing
2016-06-02 09:28:53.104 ThaliTest[5023:14315584] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-02 09:29:00.609 ThaliTest[5023:14315584] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-06-02 09:29:00.610 ThaliTest[5023:14315584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-06-02 09:29:00.610 ThaliTest[5023:14315584] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-02 09:29:00.613 ThaliTest[5023:14315584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08860E9A-D855-4BCC-B5CD-852834A7EED5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-02 09:29:06.371 ThaliTest[5023:14315415] THREAD WARNING: ['JXcore'] took '5457.085205' ms. Plugin should use a background thread.

```
