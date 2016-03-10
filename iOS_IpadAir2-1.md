#### Test 6012434713fea37_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F55B37F6-F3F2-41F5-B339-F6CFFC9AB4C7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F55B37F6-F3F2-41F5-B339-F6CFFC9AB4C7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434713fea37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50056"
,(lldb)     command script import "/tmp/F55B37F6-F3F2-41F5-B339-F6CFFC9AB4C7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 02:43:10.374 ThaliTest[1009:1571137] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7D9E298-D518-4443-AE2B-2A32BAF170E9/Library/Cookies/Cookies.binarycookies
,2016-03-10 02:43:10.678 ThaliTest[1009:1571137] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 02:43:10.679 ThaliTest[1009:1571137] Multi-tasking -> Device: YES, App: YES
,2016-03-10 02:43:10.693 ThaliTest[1009:1571137] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 02:43:12.140 ThaliTest[1009:1571137] Using UIWebView
,2016-03-10 02:43:12.147 ThaliTest[1009:1571137] [CDVTimer][handleopenurl] 0.387013ms
,2016-03-10 02:43:12.154 ThaliTest[1009:1571137] [CDVTimer][intentandnavigationfilter] 6.704032ms
,2016-03-10 02:43:12.155 ThaliTest[1009:1571137] [CDVTimer][gesturehandler] 0.315964ms
,2016-03-10 02:43:12.155 ThaliTest[1009:1571137] [CDVTimer][TotalPluginStartup] 8.971989ms
,2016-03-10 02:43:19.577 ThaliTest[1009:1571137] Resetting plugins due to page load.
,2016-03-10 02:43:23.230 ThaliTest[1009:1571137] Finished load of: file:///var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/index.html
,2016-03-10 02:43:23.437 ThaliTest[1009:1571137] JXcore Cordova plugin initializing
,2016-03-10 02:43:23.438 ThaliTest[1009:1571400] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 02:43:30.041 ThaliTest[1009:1571400] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 02:43:30.041 ThaliTest[1009:1571400] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-10 02:43:30.042 ThaliTest[1009:1571400] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 02:43:30.044 ThaliTest[1009:1571400] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1651259A-207C-4330-95B5-47B03CF2C2C5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
