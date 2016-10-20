#### Test 901767747b3ba04_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F3D211B8-9972-4B7E-8AA6-7935848EAA61/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F3D211B8-9972-4B7E-8AA6-7935848EAA61/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A8CE2AD6-CE05-4CA7-B950-AD953038E610/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61488"
,(lldb)     command script import "/tmp/F3D211B8-9972-4B7E-8AA6-7935848EAA61/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 13:14:30.469 ThaliTest[4551:10439370] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/90C775B6-C504-462D-9378-DC1A0C7F4330/Library/Cookies/Cookies.binarycookies
,2016-10-20 13:14:30.579 ThaliTest[4551:10439370] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 13:14:30.581 ThaliTest[4551:10439370] Multi-tasking -> Device: YES, App: YES
,2016-10-20 13:14:30.605 ThaliTest[4551:10439370] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 13:14:32.112 ThaliTest[4551:10439370] Using UIWebView
,2016-10-20 13:14:32.120 ThaliTest[4551:10439370] [CDVTimer][handleopenurl] 0.597000ms
,2016-10-20 13:14:32.131 ThaliTest[4551:10439370] [CDVTimer][intentandnavigationfilter] 10.079980ms
2016-10-20 13:14:32.132 ThaliTest[4551:10439370] [CDVTimer][gesturehandler] 0.383973ms
2016-10-20 13:14:32.132 ThaliTest[4551:10439370] [CDVTimer][TotalPluginStartup] 12.938023ms
,2016-10-20 13:14:38.074 ThaliTest[4551:10439370] Resetting plugins due to page load.
,2016-10-20 13:14:41.652 ThaliTest[4551:10439370] Finished load of: file:///var/mobile/Containers/Bundle/Application/A8CE2AD6-CE05-4CA7-B950-AD953038E610/ThaliTest.app/www/index.html
,2016-10-20 13:14:41.959 ThaliTest[4551:10439370] JXcore Cordova plugin initializing
,2016-10-20 13:14:41.960 ThaliTest[4551:10439584] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x131d01f20> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-20 11:15:20 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  104
Number of passed tests:  99
,Number of failed tests:  5
Number of ignored tests:  0
,Total duration:  25.26389098167419
,Failed to execute UT.
,2016-10-20 11:15:20 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
