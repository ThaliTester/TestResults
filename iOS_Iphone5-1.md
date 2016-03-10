#### Test 60124347e678b8e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/EEE2126A-AB92-445D-9A45-A2A2F8CF9CEE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EEE2126A-AB92-445D-9A45-A2A2F8CF9CEE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51079"
,(lldb)     command script import "/tmp/EEE2126A-AB92-445D-9A45-A2A2F8CF9CEE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 19:25:48.292 ThaliTest[843:1789292] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF6AAC1F-FD5D-4168-9026-73F68B9863F7/Library/Cookies/Cookies.binarycookies
,2016-03-10 19:25:48.409 ThaliTest[843:1789292] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 19:25:48.411 ThaliTest[843:1789292] Multi-tasking -> Device: YES, App: YES
,2016-03-10 19:25:48.433 ThaliTest[843:1789292] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 19:25:50.721 ThaliTest[843:1789292] Using UIWebView
,2016-03-10 19:25:50.726 ThaliTest[843:1789292] [CDVTimer][handleopenurl] 0.451028ms
,2016-03-10 19:25:50.732 ThaliTest[843:1789292] [CDVTimer][intentandnavigationfilter] 5.246997ms
2016-03-10 19:25:50.732 ThaliTest[843:1789292] [CDVTimer][gesturehandler] 0.263035ms
2016-03-10 19:25:50.732 ThaliTest[843:1789292] [CDVTimer][TotalPluginStartup] 6.978035ms
,2016-03-10 19:25:59.223 ThaliTest[843:1789292] Resetting plugins due to page load.
,2016-03-10 19:26:03.687 ThaliTest[843:1789292] Finished load of: file:///var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/index.html
,2016-03-10 19:26:03.890 ThaliTest[843:1789292] JXcore Cordova plugin initializing
,2016-03-10 19:26:03.891 ThaliTest[843:1789475] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 19:26:20.797 ThaliTest[843:1789475] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 19:26:20.798 ThaliTest[843:1789475] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 19:26:20.799 ThaliTest[843:1789475] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 19:26:20.804 ThaliTest[843:1789475] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F0D96DC8-7238-4888-ADF9-5358BDD5D50E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
