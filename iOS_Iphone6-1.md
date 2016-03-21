#### Test 625481246a7d362_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AE49AB59-F5E5-490D-A8C0-9B2F66E5EC37/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AE49AB59-F5E5-490D-A8C0-9B2F66E5EC37/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54370"
,(lldb)     command script import "/tmp/AE49AB59-F5E5-490D-A8C0-9B2F66E5EC37/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 15:48:31.486 ThaliTest[1897:3206728] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C8F7CB5-30FB-4371-B65C-B34EA4BDE1FE/Library/Cookies/Cookies.binarycookies
,2016-03-21 15:48:31.892 ThaliTest[1897:3206728] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 15:48:31.894 ThaliTest[1897:3206728] Multi-tasking -> Device: YES, App: YES
,2016-03-21 15:48:31.922 ThaliTest[1897:3206728] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 15:48:33.902 ThaliTest[1897:3206728] Using UIWebView
,2016-03-21 15:48:33.909 ThaliTest[1897:3206728] [CDVTimer][handleopenurl] 0.594020ms
,2016-03-21 15:48:33.917 ThaliTest[1897:3206728] [CDVTimer][intentandnavigationfilter] 7.286012ms
2016-03-21 15:48:33.918 ThaliTest[1897:3206728] [CDVTimer][gesturehandler] 0.373006ms
2016-03-21 15:48:33.918 ThaliTest[1897:3206728] [CDVTimer][TotalPluginStartup] 10.071039ms
,2016-03-21 15:48:40.839 ThaliTest[1897:3206728] Resetting plugins due to page load.
,2016-03-21 15:48:44.274 ThaliTest[1897:3206728] Finished load of: file:///var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/index.html
,2016-03-21 15:48:44.497 ThaliTest[1897:3206728] JXcore Cordova plugin initializing
2016-03-21 15:48:44.499 ThaliTest[1897:3206929] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 15:48:51.774 ThaliTest[1897:3206929] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 15:48:51.775 ThaliTest[1897:3206929] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 15:48:51.776 ThaliTest[1897:3206929] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 15:48:51.777 ThaliTest[1897:3206929] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/377DD723-F073-4051-A465-28EF630E3C0C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 15:48:57.692 ThaliTest[1897:3206728] THREAD WARNING: ['JXcore'] took '5601.516846' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
