#### Test 921522868c3974a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1EC22CDB-F3E7-40A4-A911-7796659ADAA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1EC22CDB-F3E7-40A4-A911-7796659ADAA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D74DE932-6647-4BA1-BC69-D6A6335DCB0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53788"
,(lldb)     command script import "/tmp/1EC22CDB-F3E7-40A4-A911-7796659ADAA7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 11:02:45.065 ThaliTest[5470:13792612] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A6A744E7-BC3C-4458-996C-5076C866E50D/Library/Cookies/Cookies.binarycookies
,2016-11-10 11:02:45.126 ThaliTest[5470:13792612] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 11:02:45.127 ThaliTest[5470:13792612] Multi-tasking -> Device: YES, App: YES
,2016-11-10 11:02:45.148 ThaliTest[5470:13792612] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 11:02:45.931 ThaliTest[5470:13792612] Using UIWebView
,2016-11-10 11:02:45.934 ThaliTest[5470:13792612] [CDVTimer][handleopenurl] 0.177979ms
,2016-11-10 11:02:45.937 ThaliTest[5470:13792612] [CDVTimer][intentandnavigationfilter] 2.860010ms
2016-11-10 11:02:45.937 ThaliTest[5470:13792612] [CDVTimer][gesturehandler] 0.147045ms
2016-11-10 11:02:45.937 ThaliTest[5470:13792612] [CDVTimer][TotalPlug,inStartup] 3.892004ms
,2016-11-10 11:02:48.884 ThaliTest[5470:13792612] Resetting plugins due to page load.
,2016-11-10 11:02:50.510 ThaliTest[5470:13792612] Finished load of: file:///var/mobile/Containers/Bundle/Application/D74DE932-6647-4BA1-BC69-D6A6335DCB0B/ThaliTest.app/www/index.html
,2016-11-10 11:02:50.702 ThaliTest[5470:13792612] JXcore Cordova plugin initializing
,2016-11-10 11:02:50.703 ThaliTest[5470:13792772] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-10 10:03:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 10:03:26 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
Number of passed tests:  99
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  22.49765700101852
Fa,iled to execute UT.
2016-11-10 10:03:26 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
