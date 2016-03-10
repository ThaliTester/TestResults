#### Test 61362366b6c9a6f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8DCE69EA-3AFC-4452-A0C0-A91A6D1DDCCC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8DCE69EA-3AFC-4452-A0C0-A91A6D1DDCCC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50538"
,(lldb)     command script import "/tmp/8DCE69EA-3AFC-4452-A0C0-A91A6D1DDCCC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 09:36:41.755 ThaliTest[1045:1618765] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0955FF20-DED2-4D73-804F-BE6FA3D0FB1C/Library/Cookies/Cookies.binarycookies
,2016-03-10 09:36:42.118 ThaliTest[1045:1618765] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 09:36:42.119 ThaliTest[1045:1618765] Multi-tasking -> Device: YES, App: YES
,2016-03-10 09:36:42.142 ThaliTest[1045:1618765] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 09:36:44.025 ThaliTest[1045:1618765] Using UIWebView
,2016-03-10 09:36:44.036 ThaliTest[1045:1618765] [CDVTimer][handleopenurl] 0.561953ms
,2016-03-10 09:36:44.044 ThaliTest[1045:1618765] [CDVTimer][intentandnavigationfilter] 7.987022ms
2016-03-10 09:36:44.045 ThaliTest[1045:1618765] [CDVTimer][gesturehandler] 0.388980ms
2016-03-10 09:36:44.046 ThaliTest[1045:1618765] [CDVTimer][TotalPluginStartup] 10.793030ms
,2016-03-10 09:36:51.358 ThaliTest[1045:1618765] Resetting plugins due to page load.
,2016-03-10 09:36:55.339 ThaliTest[1045:1618765] Finished load of: file:///var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/index.html
,2016-03-10 09:36:55.596 ThaliTest[1045:1618765] JXcore Cordova plugin initializing
,2016-03-10 09:36:55.597 ThaliTest[1045:1619007] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 09:37:09.442 ThaliTest[1045:1619007] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 09:37:09.442 ThaliTest[1045:1619007] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 09:37:09.442 ThaliTest[1045:1619007] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 09:37:09.444 ThaliTest[1045:1619007] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E12EF6F6-87EE-4797-BC96-0BE95DDA8AD0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
