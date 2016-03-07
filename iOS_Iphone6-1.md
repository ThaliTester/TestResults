#### Test 613623665d5a4d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0DB6C59B-86E4-4AEC-995A-E989C03D02CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0DB6C59B-86E4-4AEC-995A-E989C03D02CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50760"
,(lldb)     command script import "/tmp/0DB6C59B-86E4-4AEC-995A-E989C03D02CC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 10:50:03.551 ThaliTest[780:1145142] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E26F9D33-99B4-4E94-8C24-20A65D479319/Library/Cookies/Cookies.binarycookies
,2016-03-07 10:50:03.977 ThaliTest[780:1145142] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 10:50:03.978 ThaliTest[780:1145142] Multi-tasking -> Device: YES, App: YES
,2016-03-07 10:50:03.997 ThaliTest[780:1145142] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 10:50:05.838 ThaliTest[780:1145142] Using UIWebView
,2016-03-07 10:50:05.845 ThaliTest[780:1145142] [CDVTimer][handleopenurl] 0.529945ms
,2016-03-07 10:50:05.854 ThaliTest[780:1145142] [CDVTimer][intentandnavigationfilter] 8.033991ms
2016-03-07 10:50:05.855 ThaliTest[780:1145142] [CDVTimer][gesturehandler] 0.378966ms
2016-03-07 10:50:05.855 ThaliTest[780:1145142] [CDVTimer][TotalPluginStartup] 10.621011ms
,2016-03-07 10:50:12.602 ThaliTest[780:1145142] Resetting plugins due to page load.
,2016-03-07 10:50:16.237 ThaliTest[780:1145142] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/index.html
,2016-03-07 10:50:16.456 ThaliTest[780:1145142] JXcore Cordova plugin initializing
,2016-03-07 10:50:16.459 ThaliTest[780:1145358] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 10:50:28.877 ThaliTest[780:1145358] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 10:50:28.878 ThaliTest[780:1145358] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 10:50:28.878 ThaliTest[780:1145358] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 10:50:28.879 ThaliTest[780:1145358] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F78F9D8-7BF3-4001-8A94-961E78C7968E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```
