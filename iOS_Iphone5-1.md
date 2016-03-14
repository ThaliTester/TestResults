#### Test 6250909442642cd_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC1CFC6D-49C4-46AD-B21C-38ED26C9E980/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AC1CFC6D-49C4-46AD-B21C-38ED26C9E980/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6250909442642cd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49964"
,(lldb)     command script import "/tmp/AC1CFC6D-49C4-46AD-B21C-38ED26C9E980/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 07:35:48.983 ThaliTest[1006:2283485] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ECBCEF7D-A53D-4C76-ACF2-4A9014619A2E/Library/Cookies/Cookies.binarycookies
,2016-03-14 07:35:49.111 ThaliTest[1006:2283485] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 07:35:49.113 ThaliTest[1006:2283485] Multi-tasking -> Device: YES, App: YES
,2016-03-14 07:35:49.136 ThaliTest[1006:2283485] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 07:35:51.210 ThaliTest[1006:2283485] Using UIWebView
,2016-03-14 07:35:51.215 ThaliTest[1006:2283485] [CDVTimer][handleopenurl] 0.356019ms
,2016-03-14 07:35:51.221 ThaliTest[1006:2283485] [CDVTimer][intentandnavigationfilter] 5.145013ms
2016-03-14 07:35:51.221 ThaliTest[1006:2283485] [CDVTimer][gesturehandler] 0.259995ms
2016-03-14 07:35:51.221 ThaliTest[1006:2283485] [CDVTimer][TotalPluginStartup] 6.805003ms
,2016-03-14 07:36:00.359 ThaliTest[1006:2283485] Resetting plugins due to page load.
,2016-03-14 07:36:04.258 ThaliTest[1006:2283485] Finished load of: file:///var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/index.html
,2016-03-14 07:36:04.460 ThaliTest[1006:2283485] JXcore Cordova plugin initializing
2016-03-14 07:36:04.461 ThaliTest[1006:2283671] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 07:36:26.358 ThaliTest[1006:2283671] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 07:36:26.359 ThaliTest[1006:2283671] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-14 07:36:26.360 ThaliTest[1006:2283671] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 07:36:26.363 ThaliTest[1006:2283671] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F41C44F0-EB2C-4612-8F66-1D73FA008B25/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
