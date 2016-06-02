#### Test 7214543191b6842_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/3E5BC4A8-2746-4A0E-B5CF-1F90C04866DE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3E5BC4A8-2746-4A0E-B5CF-1F90C04866DE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7214543191b6842/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58254"
,(lldb)     command script import "/tmp/3E5BC4A8-2746-4A0E-B5CF-1F90C04866DE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-02 09:28:24.026 ThaliTest[3729:14895043] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6BE424F5-FF15-4502-8FD7-BC4526BFEA64/Library/Cookies/Cookies.binarycookies
,2016-06-02 09:28:24.391 ThaliTest[3729:14895043] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-02 09:28:24.392 ThaliTest[3729:14895043] Multi-tasking -> Device: YES, App: YES
,2016-06-02 09:28:24.410 ThaliTest[3729:14895043] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-02 09:28:25.606 ThaliTest[3729:14895043] Using UIWebView
2016-06-02 09:28:25.609 ThaliTest[3729:14895043] [CDVTimer][handleopenurl] 0.261009ms
,2016-06-02 09:28:25.615 ThaliTest[3729:14895043] [CDVTimer][intentandnavigationfilter] 5.544007ms
2016-06-02 09:28:25.616 ThaliTest[3729:14895043] [CDVTimer][gesturehandler] 0.219047ms
2016-06-02 09:28:25.616 ThaliTest[3729:14895043] [CDVTimer][TotalPluginStartup] 6.882012ms
,2016-06-02 09:28:30.679 ThaliTest[3729:14895043] Resetting plugins due to page load.
,2016-06-02 09:28:32.601 ThaliTest[3729:14895043] Finished load of: file:///var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/index.html
,2016-06-02 09:28:32.800 ThaliTest[3729:14895043] JXcore Cordova plugin initializing
2016-06-02 09:28:32.803 ThaliTest[3729:14895162] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-02 09:28:47.634 ThaliTest[3729:14895162] jxcore: didRegisterToNative peerAvailabilityChanged
2016-06-02 09:28:47.635 ThaliTest[3729:14895162] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-02 09:28:47.635 ThaliTest[3729,:14895162] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-06-02 09:28:47.639 ThaliTest[3729:14895162] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B60B8535-3F03-46CF-8FDA-D235FD111951/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```
