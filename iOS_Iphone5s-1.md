#### Test 648991491c812df_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/A1C43326-814B-4980-AAD3-07B32AF30D79/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A1C43326-814B-4980-AAD3-07B32AF30D79/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50128"
,(lldb)     command script import "/tmp/A1C43326-814B-4980-AAD3-07B32AF30D79/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 09:10:47.917 ThaliTest[2653:4844301] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB1C48DC-8770-451E-9A02-0FFA0F09C5A6/Library/Cookies/Cookies.binarycookies
,2016-04-01 09:10:48.171 ThaliTest[2653:4844301] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 09:10:48.172 ThaliTest[2653:4844301] Multi-tasking -> Device: YES, App: YES
,2016-04-01 09:10:48.191 ThaliTest[2653:4844301] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 09:10:48.993 ThaliTest[2653:4844301] Using UIWebView
,2016-04-01 09:10:48.996 ThaliTest[2653:4844301] [CDVTimer][handleopenurl] 0.190973ms
,2016-04-01 09:10:49.000 ThaliTest[2653:4844301] [CDVTimer][intentandnavigationfilter] 2.915978ms
2016-04-01 09:10:49.000 ThaliTest[2653:4844301] [CDVTimer][gesturehandler] 0.164986ms
2016-04-01 09:10:49.000 ThaliTest[2653:4844301] [CDVTimer][TotalPluginStartup] 3.971040ms
,2016-04-01 09:10:52.199 ThaliTest[2653:4844301] Resetting plugins due to page load.
,2016-04-01 09:10:53.546 ThaliTest[2653:4844301] Finished load of: file:///var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/index.html
,2016-04-01 09:10:53.729 ThaliTest[2653:4844301] JXcore Cordova plugin initializing
2016-04-01 09:10:53.730 ThaliTest[2653:4844464] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 09:11:02.091 ThaliTest[2653:4844464] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 09:11:02.092 ThaliTest[2653:4844464] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 09:11:02.092 ThaliTest[2653:4844464] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 09:11:02.094 ThaliTest[2653:4844464] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/894AA3BB-E7FC-4391-8C33-18720F4A1F3F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# name
,ok 1 sane
# teardown
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
