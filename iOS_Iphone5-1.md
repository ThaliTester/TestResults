#### Test 62509094ffd3875_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/EA89C844-0A72-4F0D-8C66-A8AD16043928/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EA89C844-0A72-4F0D-8C66-A8AD16043928/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094ffd3875/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49396"
,(lldb)     command script import "/tmp/EA89C844-0A72-4F0D-8C66-A8AD16043928/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-11 11:03:14.312 ThaliTest[886:1850315] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/708D202C-2A92-499E-ADDC-8816373779BA/Library/Cookies/Cookies.binarycookies
,2016-03-11 11:03:14.838 ThaliTest[886:1850315] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 11:03:14.840 ThaliTest[886:1850315] Multi-tasking -> Device: YES, App: YES
,2016-03-11 11:03:14.859 ThaliTest[886:1850315] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 11:03:16.827 ThaliTest[886:1850315] Using UIWebView
,2016-03-11 11:03:16.834 ThaliTest[886:1850315] [CDVTimer][handleopenurl] 0.306964ms
,2016-03-11 11:03:16.839 ThaliTest[886:1850315] [CDVTimer][intentandnavigationfilter] 5.230963ms
2016-03-11 11:03:16.840 ThaliTest[886:1850315] [CDVTimer][gesturehandler] 0.279009ms
2016-03-11 11:03:16.840 ThaliTest[886:1850315] [CDVTimer][TotalPluginStartup] 6.889999ms
,2016-03-11 11:03:24.633 ThaliTest[886:1850315] Resetting plugins due to page load.
,2016-03-11 11:03:27.992 ThaliTest[886:1850315] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/index.html
,2016-03-11 11:03:28.195 ThaliTest[886:1850315] JXcore Cordova plugin initializing
,2016-03-11 11:03:28.197 ThaliTest[886:1850488] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 11:03:50.196 ThaliTest[886:1850488] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 11:03:50.196 ThaliTest[886:1850488] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 11:03:50.197 ThaliTest[886:1850488] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 11:03:50.199 ThaliTest[886:1850488] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B4839C9-5D78-496F-B415-A5D14F62F876/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
