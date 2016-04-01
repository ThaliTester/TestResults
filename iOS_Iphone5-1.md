#### Test 648991491c812df_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C1AC3364-6FFC-4E39-884A-943FEC34FF84/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C1AC3364-6FFC-4E39-884A-943FEC34FF84/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648991491c812df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50124"
,(lldb)     command script import "/tmp/C1AC3364-6FFC-4E39-884A-943FEC34FF84/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 09:10:24.364 ThaliTest[1991:5064731] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32E8749B-D4B3-4678-B799-E8A41AC5B3A5/Library/Cookies/Cookies.binarycookies
,2016-04-01 09:10:24.469 ThaliTest[1991:5064731] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 09:10:24.470 ThaliTest[1991:5064731] Multi-tasking -> Device: YES, App: YES
,2016-04-01 09:10:24.487 ThaliTest[1991:5064731] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 09:10:25.672 ThaliTest[1991:5064731] Using UIWebView
2016-04-01 09:10:25.676 ThaliTest[1991:5064731] [CDVTimer][handleopenurl] 0.289023ms
,2016-04-01 09:10:25.682 ThaliTest[1991:5064731] [CDVTimer][intentandnavigationfilter] 5.411029ms
2016-04-01 09:10:25.682 ThaliTest[1991:5064731] [CDVTimer][gesturehandler] 0.222981ms
2016-04-01 09:10:25.683 ThaliTest[1991:5064731] [CDVTimer][TotalPluginStartup] 6.803989ms
,2016-04-01 09:10:30.681 ThaliTest[1991:5064731] Resetting plugins due to page load.
,2016-04-01 09:10:32.878 ThaliTest[1991:5064731] Finished load of: file:///var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/index.html
,2016-04-01 09:10:32.889 ThaliTest[1991:5064731] JXcore Cordova plugin initializing
,2016-04-01 09:10:32.891 ThaliTest[1991:5064876] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 09:10:47.717 ThaliTest[1991:5064876] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 09:10:47.717 ThaliTest[1991:5064876] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 09:10:47.718 ThaliTest[1991:5,064876] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 09:10:47.720 ThaliTest[1991:5064876] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369F0B50-3092-4A4D-AE80-AE0A55EE6A3B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# name
,ok 1 sane
# teardown
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
