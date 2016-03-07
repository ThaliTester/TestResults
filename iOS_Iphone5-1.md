#### Test 61362366345141a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7430A60F-F04B-4A9E-8457-C2FD9D62991E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7430A60F-F04B-4A9E-8457-C2FD9D62991E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51537"
,(lldb)     command script import "/tmp/7430A60F-F04B-4A9E-8457-C2FD9D62991E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 15:35:31.860 ThaliTest[662:1300625] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/16A40E58-2E84-47BE-87C5-9699B7FECADB/Library/Cookies/Cookies.binarycookies
,2016-03-07 15:35:31.985 ThaliTest[662:1300625] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 15:35:31.986 ThaliTest[662:1300625] Multi-tasking -> Device: YES, App: YES
,2016-03-07 15:35:32.006 ThaliTest[662:1300625] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 15:35:34.132 ThaliTest[662:1300625] Using UIWebView
,2016-03-07 15:35:34.137 ThaliTest[662:1300625] [CDVTimer][handleopenurl] 0.290990ms
,2016-03-07 15:35:34.143 ThaliTest[662:1300625] [CDVTimer][intentandnavigationfilter] 5.213022ms
2016-03-07 15:35:34.143 ThaliTest[662:1300625] [CDVTimer][gesturehandler] 0.253975ms
2016-03-07 15:35:34.144 ThaliTest[662:1300625] [CDVTimer][TotalPluginStartup] 6.922007ms
,2016-03-07 15:35:42.414 ThaliTest[662:1300625] Resetting plugins due to page load.
,2016-03-07 15:35:46.476 ThaliTest[662:1300625] Finished load of: file:///var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/index.html
,2016-03-07 15:35:46.679 ThaliTest[662:1300625] JXcore Cordova plugin initializing
,2016-03-07 15:35:46.681 ThaliTest[662:1300806] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 15:36:08.416 ThaliTest[662:1300806] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 15:36:08.416 ThaliTest[662:1300806] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 15:36:08.417 ThaliTest[662:1300806] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 15:36:08.420 ThaliTest[662:1300806] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/563A4280-9877-44A0-989E-112355838D8C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```
