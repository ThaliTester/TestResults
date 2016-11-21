#### Test 935721672bafbe2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BF0BF2BF-C822-49DF-B595-E8AA19EA55B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BF0BF2BF-C822-49DF-B595-E8AA19EA55B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CB49F091-14AB-475F-A6FD-93EE26B8473C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58177"
,(lldb)     command script import "/tmp/BF0BF2BF-C822-49DF-B595-E8AA19EA55B8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 16:48:26.281 ThaliTest[3820:9746230] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E19E9BF7-DA24-41C9-BB61-21A83073A20D/Library/Cookies/Cookies.binarycookies
,2016-11-21 16:48:26.358 ThaliTest[3820:9746230] Apache Cordova native platform version 4.2.1 is starting.
2016-11-21 16:48:26.359 ThaliTest[3820:9746230] Multi-tasking -> Device: YES, App: YES
,2016-11-21 16:48:26.379 ThaliTest[3820:9746230] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 16:48:26.812 ThaliTest[3820:9746230] Using UIWebView
,2016-11-21 16:48:26.819 ThaliTest[3820:9746230] [CDVTimer][handleopenurl] 0.515044ms
,2016-11-21 16:48:26.827 ThaliTest[3820:9746230] [CDVTimer][intentandnavigationfilter] 7.529974ms
2016-11-21 16:48:26.827 ThaliTest[3820:9746230] [CDVTimer][gesturehandler] 0.272036ms
2016-11-21 16:48:26.828 ThaliTest[3820:9746230] [CDVTimer][TotalPluginS,tartup] 9.860992ms
,2016-11-21 16:48:32.222 ThaliTest[3820:9746230] Resetting plugins due to page load.
,2016-11-21 16:48:32.576 ThaliTest[3820:9746230] Finished load of: file:///var/containers/Bundle/Application/CB49F091-14AB-475F-A6FD-93EE26B8473C/ThaliTest.app/www/index.html
,2016-11-21 16:48:32.941 ThaliTest[3820:9746230] JXcore Cordova plugin initializing
,2016-11-21 16:48:32.942 ThaliTest[3820:9746396] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 15:48:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 15:48:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 15:48:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 15:48:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 15:48:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 43
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 15:49:08 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  25.0290430188179
Fa,iled to execute UT.
,2016-11-21 15:49:08 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
