#### Test 6012434713fea37_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/55C35F90-3C10-4EF4-9A22-98798EB35FE3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/55C35F90-3C10-4EF4-9A22-98798EB35FE3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50041"
,(lldb)     command script import "/tmp/55C35F90-3C10-4EF4-9A22-98798EB35FE3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 02:42:03.950 ThaliTest[778:1674646] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/361852E1-CE57-43E9-B711-0FD3FD487605/Library/Cookies/Cookies.binarycookies
,2016-03-10 02:42:04.477 ThaliTest[778:1674646] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 02:42:04.479 ThaliTest[778:1674646] Multi-tasking -> Device: YES, App: YES
,2016-03-10 02:42:04.498 ThaliTest[778:1674646] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 02:42:06.583 ThaliTest[778:1674646] Using UIWebView
,2016-03-10 02:42:06.588 ThaliTest[778:1674646] [CDVTimer][handleopenurl] 0.406027ms
,2016-03-10 02:42:06.594 ThaliTest[778:1674646] [CDVTimer][intentandnavigationfilter] 5.198002ms
2016-03-10 02:42:06.594 ThaliTest[778:1674646] [CDVTimer][gesturehandler] 0.256002ms
2016-03-10 02:42:06.594 ThaliTest[778:1674646] [CDVTimer][TotalPluginStar,tup] 6.949961ms
,2016-03-10 02:42:14.823 ThaliTest[778:1674646] Resetting plugins due to page load.
,2016-03-10 02:42:18.430 ThaliTest[778:1674646] Finished load of: file:///var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/index.html
,2016-03-10 02:42:18.634 ThaliTest[778:1674646] JXcore Cordova plugin initializing
,2016-03-10 02:42:18.636 ThaliTest[778:1674823] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 02:42:35.543 ThaliTest[778:1674823] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 02:42:35.544 ThaliTest[778:1674823] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-10 02:42:35.544 ThaliTest[778:1674823] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 02:42:35.551 ThaliTest[778:1674823] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D9909712-9674-4FEC-9441-0216C93C316F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded
,

```
