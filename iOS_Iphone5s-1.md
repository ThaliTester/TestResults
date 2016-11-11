#### Test 93390913232c8a0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0627B4EB-FA7D-449C-9C3D-205E5D1B21DF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0627B4EB-FA7D-449C-9C3D-205E5D1B21DF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E2A0AFF6-16F2-42DB-9A8F-0DFF228267C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54359"
,(lldb)     command script import "/tmp/0627B4EB-FA7D-449C-9C3D-205E5D1B21DF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-11 21:57:43.427 ThaliTest[5561:14013534] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4DFFF6A9-B914-4A71-A008-D597B2ACE293/Library/Cookies/Cookies.binarycookies
,2016-11-11 21:57:43.493 ThaliTest[5561:14013534] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-11 21:57:43.494 ThaliTest[5561:14013534] Multi-tasking -> Device: YES, App: YES
,2016-11-11 21:57:43.509 ThaliTest[5561:14013534] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-11 21:57:44.249 ThaliTest[5561:14013534] Using UIWebView
2016-11-11 21:57:44.252 ThaliTest[5561:14013534] [CDVTimer][handleopenurl] 0.182986ms
,2016-11-11 21:57:44.256 ThaliTest[5561:14013534] [CDVTimer][intentandnavigationfilter] 2.988040ms
2016-11-11 21:57:44.256 ThaliTest[5561:14013534] [CDVTimer][gesturehandler] 0.154018ms
2016-11-11 21:57:44.256 ThaliTest[5561:14013534] [CDVTimer][TotalPluginStartup] 3.964961ms
,2016-11-11 21:57:47.460 ThaliTest[5561:14013534] Resetting plugins due to page load.
,2016-11-11 21:57:49.159 ThaliTest[5561:14013534] Finished load of: file:///var/mobile/Containers/Bundle/Application/E2A0AFF6-16F2-42DB-9A8F-0DFF228267C5/ThaliTest.app/www/index.html
,2016-11-11 21:57:49.360 ThaliTest[5561:14013534] JXcore Cordova plugin initializing
,2016-11-11 21:57:49.362 ThaliTest[5561:14013704] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-11 20:58:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-11 20:58:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-11 20:58:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-11 20:58:01 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-11 20:58:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x12fed0340> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-11 20:58:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  113
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  34.15574997663498
Failed to execute UT.
2016-11-11 20:58:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
