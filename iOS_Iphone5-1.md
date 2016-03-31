#### Test 64613803717efd7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0D3A48D7-A03D-4617-9FCB-898206D16624/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0D3A48D7-A03D-4617-9FCB-898206D16624/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803717efd7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49697"
,(lldb)     command script import "/tmp/0D3A48D7-A03D-4617-9FCB-898206D16624/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 12:57:01.230 ThaliTest[1929:4931204] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D9C4BD2-1DD4-4AC4-B612-D54BBDBE9E3D/Library/Cookies/Cookies.binarycookies
,2016-03-31 12:57:01.570 ThaliTest[1929:4931204] Apache Cordova native platform version 4.1.0 is starting.
2016-03-31 12:57:01.571 ThaliTest[1929:4931204] Multi-tasking -> Device: YES, App: YES
,2016-03-31 12:57:01.588 ThaliTest[1929:4931204] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 12:57:02.770 ThaliTest[1929:4931204] Using UIWebView
,2016-03-31 12:57:02.776 ThaliTest[1929:4931204] [CDVTimer][handleopenurl] 0.242054ms
2016-03-31 12:57:02.781 ThaliTest[1929:4931204] [CDVTimer][intentandnavigationfilter] 4.468024ms
2016-03-31 12:57:02.781 ThaliTest[1929:4931204] [CDVTimer][gesturehandler] 0.204980ms
2016-03-31 12:57:02.782 ThaliTest[1929:4931204] [CDVTimer][TotalPluginStartup] 5.746961ms
,2016-03-31 12:57:07.734 ThaliTest[1929:4931204] Resetting plugins due to page load.
,2016-03-31 12:57:09.584 ThaliTest[1929:4931204] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/index.html
,2016-03-31 12:57:09.774 ThaliTest[1929:4931204] JXcore Cordova plugin initializing
,2016-03-31 12:57:09.897 ThaliTest[1929:4931355] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 12:57:23.830 ThaliTest[1929:4931355] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 12:57:23.831 ThaliTest[1929:4931355] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 12:57:23.832 ThaliTest[1929:4931355] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 12:57:23.836 ThaliTest[1929:4931355] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E4408D30-C063-4944-AA98-EE39732DB099/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
