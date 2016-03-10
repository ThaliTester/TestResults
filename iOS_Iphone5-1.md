#### Test 623288225dc9f88_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9ED844E1-82BD-44FD-A329-6CD15B5CBFCA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9ED844E1-82BD-44FD-A329-6CD15B5CBFCA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/623288225dc9f88/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50168"
,(lldb)     command script import "/tmp/9ED844E1-82BD-44FD-A329-6CD15B5CBFCA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 03:31:33.094 ThaliTest[784:1680795] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE339A55-169D-4E6C-8270-A5022B6363BC/Library/Cookies/Cookies.binarycookies
,2016-03-10 03:31:33.209 ThaliTest[784:1680795] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 03:31:33.210 ThaliTest[784:1680795] Multi-tasking -> Device: YES, App: YES
,2016-03-10 03:31:33.231 ThaliTest[784:1680795] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 03:31:35.277 ThaliTest[784:1680795] Using UIWebView
,2016-03-10 03:31:35.282 ThaliTest[784:1680795] [CDVTimer][handleopenurl] 0.307024ms
,2016-03-10 03:31:35.288 ThaliTest[784:1680795] [CDVTimer][intentandnavigationfilter] 5.447030ms
2016-03-10 03:31:35.289 ThaliTest[784:1680795] [CDVTimer][gesturehandler] 0.280023ms
2016-03-10 03:31:35.289 ThaliTest[784:1680795] [CDVTimer][TotalPluginStartup] 7.109046ms
,2016-03-10 03:31:43.622 ThaliTest[784:1680795] Resetting plugins due to page load.
,2016-03-10 03:31:47.697 ThaliTest[784:1680795] Finished load of: file:///var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/index.html
,2016-03-10 03:31:47.905 ThaliTest[784:1680795] JXcore Cordova plugin initializing
,2016-03-10 03:31:47.907 ThaliTest[784:1680979] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 03:32:04.863 ThaliTest[784:1680979] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 03:32:04.863 ThaliTest[784:1680979] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 03:32:04.864 ThaliTest[784:1680979] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 03:32:04.870 ThaliTest[784:1680979] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35B0BC98-B7FD-4172-B04F-FF2534F2742E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
