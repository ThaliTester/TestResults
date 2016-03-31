#### Test 646138038d447f5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2AAFC7BD-120D-4320-A3DD-0A5500034CFC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2AAFC7BD-120D-4320-A3DD-0A5500034CFC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49573"
,(lldb)     command script import "/tmp/2AAFC7BD-120D-4320-A3DD-0A5500034CFC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 09:41:16.423 ThaliTest[2492:4658934] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A9DD54B3-8A2A-49E4-9019-4A495E3C8F1F/Library/Cookies/Cookies.binarycookies
,2016-03-31 09:41:16.658 ThaliTest[2492:4658934] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 09:41:16.659 ThaliTest[2492:4658934] Multi-tasking -> Device: YES, App: YES
,2016-03-31 09:41:16.674 ThaliTest[2492:4658934] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 09:41:17.441 ThaliTest[2492:4658934] Using UIWebView
2016-03-31 09:41:17.443 ThaliTest[2492:4658934] [CDVTimer][handleopenurl] 0.117004ms
2016-03-31 09:41:17.445 ThaliTest[2492:4658934] [CDVTimer][intentandnavigationfilter] 2.122998ms
2016-03-31 09:41:17.446 ThaliTest[2492:4658934] [CDVTimer][gesturehandler] 0.095010ms
2016-03-31 09:41:17.446 ThaliTest[2492:4658934] [CDVTimer][TotalPluginStartup] 2.746999ms
,2016-03-31 09:41:20.580 ThaliTest[2492:4658934] Resetting plugins due to page load.
,2016-03-31 09:41:21.822 ThaliTest[2492:4658934] Finished load of: file:///var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/index.html
,2016-03-31 09:41:21.979 ThaliTest[2492:4658934] JXcore Cordova plugin initializing
,2016-03-31 09:41:22.059 ThaliTest[2492:4659101] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 09:41:28.943 ThaliTest[2492:4659101] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 09:41:28.944 ThaliTest[2492:4659101] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 09:41:28.944 ThaliTest[2492:4659101] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 09:41:28.945 ThaliTest[2492:4659101] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5D920D9-542D-4947-A43C-05BF453ED96F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,Connected to the test server

```
