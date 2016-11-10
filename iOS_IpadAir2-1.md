#### Test 896247969cd5996_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/71FE2B66-1E54-474A-8999-9C6F18519AD7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/71FE2B66-1E54-474A-8999-9C6F18519AD7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F46170E0-51DD-4D2F-98E6-A1799939B960/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55120"
,(lldb)     command script import "/tmp/71FE2B66-1E54-474A-8999-9C6F18519AD7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 12:15:46.452 ThaliTest[5362:11502166] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68B0F54A-28FB-475B-BEE7-EA11DB68127C/Library/Cookies/Cookies.binarycookies
,2016-11-10 12:15:46.712 ThaliTest[5362:11502166] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 12:15:46.713 ThaliTest[5362:11502166] Multi-tasking -> Device: YES, App: YES
,2016-11-10 12:15:46.725 ThaliTest[5362:11502166] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 12:15:47.603 ThaliTest[5362:11502166] Using UIWebView
,2016-11-10 12:15:47.605 ThaliTest[5362:11502166] [CDVTimer][handleopenurl] 0.138998ms
,2016-11-10 12:15:47.607 ThaliTest[5362:11502166] [CDVTimer][intentandnavigationfilter] 1.785994ms
2016-11-10 12:15:47.607 ThaliTest[5362:11502166] [CDVTimer][gesturehandler] 0.078976ms
2016-11-10 12:15:47.607 ThaliTest[5362:11502166] [CDVTimer][TotalPluginStartup] 2.430975ms
,2016-11-10 12:15:50.734 ThaliTest[5362:11502166] Resetting plugins due to page load.
,2016-11-10 12:15:52.141 ThaliTest[5362:11502166] Finished load of: file:///var/mobile/Containers/Bundle/Application/F46170E0-51DD-4D2F-98E6-A1799939B960/ThaliTest.app/www/index.html
,2016-11-10 12:15:52.270 ThaliTest[5362:11502166] JXcore Cordova plugin initializing
,2016-11-10 12:15:52.271 ThaliTest[5362:11502348] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 11:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 11:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 11:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-10 11:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 11:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected connect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 40
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-10 11:16:37 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
Number of ignored tests:  0
Total duration:  35.65257000923157
,Failed to execute UT.
2016-11-10 11:16:37 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
