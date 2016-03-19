#### Test 62548124d9c0fd9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/24177948-BC06-4B76-AC73-5FF495C74BE8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/24177948-BC06-4B76-AC73-5FF495C74BE8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53099"
,(lldb)     command script import "/tmp/24177948-BC06-4B76-AC73-5FF495C74BE8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-19 12:51:27.440 ThaliTest[1747:2889038] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/034DAB28-681A-4D44-802F-6949B804F33A/Library/Cookies/Cookies.binarycookies
,2016-03-19 12:51:27.793 ThaliTest[1747:2889038] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-19 12:51:27.794 ThaliTest[1747:2889038] Multi-tasking -> Device: YES, App: YES
,2016-03-19 12:51:27.815 ThaliTest[1747:2889038] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-19 12:51:29.650 ThaliTest[1747:2889038] Using UIWebView
,2016-03-19 12:51:29.657 ThaliTest[1747:2889038] [CDVTimer][handleopenurl] 0.506997ms
,2016-03-19 12:51:29.665 ThaliTest[1747:2889038] [CDVTimer][intentandnavigationfilter] 7.802010ms
2016-03-19 12:51:29.666 ThaliTest[1747:2889038] [CDVTimer][gesturehandler] 0.406981ms
2016-03-19 12:51:29.666 ThaliTest[1747:2889038] [CDVTimer][TotalPluginS,tartup] 10.380030ms
,2016-03-19 12:51:36.455 ThaliTest[1747:2889038] Resetting plugins due to page load.
,2016-03-19 12:51:39.763 ThaliTest[1747:2889038] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/index.html
,2016-03-19 12:51:40.049 ThaliTest[1747:2889038] JXcore Cordova plugin initializing
,2016-03-19 12:51:40.050 ThaliTest[1747:2889229] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-19 12:51:47.320 ThaliTest[1747:2889229] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 12:51:47.320 ThaliTest[1747:2889229] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 12:51:47.320 ThaliTest[1747:2889229] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 12:51:47.322 ThaliTest[1747:2889229] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D95B05-46EE-44A0-A606-27DA2B7FD6C4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-19 12:51:53.211 ThaliTest[1747:2889038] THREAD WARNING: ['JXcore'] took '5575.542725' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
