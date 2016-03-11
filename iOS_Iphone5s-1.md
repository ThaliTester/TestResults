#### Test 62509094aba5909_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094aba5909/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E1101BFA-BBFB-453E-B9CE-32A3DB433378/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E1101BFA-BBFB-453E-B9CE-32A3DB433378/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094aba5909/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094aba5909/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49290"
,(lldb)     command script import "/tmp/E1101BFA-BBFB-453E-B9CE-32A3DB433378/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 09:55:27.714 ThaliTest[1143:1735738] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E89D5687-6D89-48C5-A833-9A18E8663273/Library/Cookies/Cookies.binarycookies
,2016-03-11 09:55:28.043 ThaliTest[1143:1735738] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 09:55:28.045 ThaliTest[1143:1735738] Multi-tasking -> Device: YES, App: YES
,2016-03-11 09:55:28.070 ThaliTest[1143:1735738] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 09:55:29.074 ThaliTest[1143:1735738] Using UIWebView
2016-03-11 09:55:29.077 ThaliTest[1143:1735738] [CDVTimer][handleopenurl] 0.194013ms
2016-03-11 09:55:29.082 ThaliTest[1143:1735738] [CDVTimer][intentandnavigationfilter] 4.354000ms
2016-03,-11 09:55:29.082 ThaliTest[1143:1735738] [CDVTimer][gesturehandler] 0.209987ms
2016-03-11 09:55:29.082 ThaliTest[1143:1735738] [CDVTimer][TotalPluginStartup] 5.541980ms
,2016-03-11 09:55:33.040 ThaliTest[1143:1735738] Resetting plugins due to page load.
,2016-03-11 09:55:34.891 ThaliTest[1143:1735738] Finished load of: file:///var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/index.html
,2016-03-11 09:55:35.184 ThaliTest[1143:1735738] JXcore Cordova plugin initializing
,2016-03-11 09:55:35.186 ThaliTest[1143:1735888] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 09:55:58.231 ThaliTest[1143:1735888] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 09:55:58.233 ThaliTest[1143:1735888] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-11 09:55:58.234 ThaliTest[1143:1735888] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 09:55:58.237 ThaliTest[1143:1735888] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8199A060-EBC6-4375-B8B3-E4842E1D16E1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
