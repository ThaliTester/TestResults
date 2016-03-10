#### Test 61362366b225741_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9A638076-94CA-4A6E-919B-BFA67BF165C9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9A638076-94CA-4A6E-919B-BFA67BF165C9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50605"
,(lldb)     command script import "/tmp/9A638076-94CA-4A6E-919B-BFA67BF165C9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 11:11:19.927 ThaliTest[812:1732490] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1CF1046C-63A0-430C-80BD-5F1DE98CA815/Library/Cookies/Cookies.binarycookies
,2016-03-10 11:11:20.484 ThaliTest[812:1732490] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 11:11:20.486 ThaliTest[812:1732490] Multi-tasking -> Device: YES, App: YES
,2016-03-10 11:11:20.506 ThaliTest[812:1732490] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 11:11:22.718 ThaliTest[812:1732490] Using UIWebView
,2016-03-10 11:11:22.725 ThaliTest[812:1732490] [CDVTimer][handleopenurl] 0.286043ms
,2016-03-10 11:11:22.730 ThaliTest[812:1732490] [CDVTimer][intentandnavigationfilter] 5.167961ms
2016-03-10 11:11:22.731 ThaliTest[812:1732490] [CDVTimer][gesturehandler] 0.296056ms
2016-03-10 11:11:22.731 ThaliTest[812:1732490] [CDVTimer][TotalPluginStartup] 6.794989ms
,2016-03-10 11:11:30.401 ThaliTest[812:1732490] Resetting plugins due to page load.
,2016-03-10 11:11:33.711 ThaliTest[812:1732490] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/index.html
,2016-03-10 11:11:33.920 ThaliTest[812:1732490] JXcore Cordova plugin initializing
,2016-03-10 11:11:33.921 ThaliTest[812:1732662] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 11:11:55.617 ThaliTest[812:1732662] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 11:11:55.618 ThaliTest[812:1732662] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 11:11:55.619 ThaliTest[812:1732662] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 11:11:55.621 ThaliTest[812:1732662] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7F230F5-082B-4E1B-9102-CFD268A2998B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
