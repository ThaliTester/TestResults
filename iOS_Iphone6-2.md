#### Test 921522868c3974a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/46D0291D-4DA1-4D83-A5D2-75122EF11AAB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/46D0291D-4DA1-4D83-A5D2-75122EF11AAB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EDA62B0E-17AE-4573-A71E-46D95E23E2F7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53790"
,(lldb)     command script import "/tmp/46D0291D-4DA1-4D83-A5D2-75122EF11AAB/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 02:03:06.013 ThaliTest[3251:7282237] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2F7E0AFC-A3BB-4976-8531-22750DB12221/Library/Cookies/Cookies.binarycookies
,2016-11-10 02:03:06.106 ThaliTest[3251:7282237] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 02:03:06.108 ThaliTest[3251:7282237] Multi-tasking -> Device: YES, App: YES
,2016-11-10 02:03:06.133 ThaliTest[3251:7282237] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 02:03:06.614 ThaliTest[3251:7282237] Using UIWebView
2016-11-10 02:03:06.622 ThaliTest[3251:7282237] [CDVTimer][handleopenurl] 0.419021ms
,2016-11-10 02:03:06.630 ThaliTest[3251:7282237] [CDVTimer][intentandnavigationfilter] 7.176995ms
2016-11-10 02:03:06.630 ThaliTest[3251:7282237] [CDVTimer][gesturehandler] 0.277042ms
2016-11-10 02:03:06.631 ThaliTest[3251:7282237] [CDVTimer][TotalPluginStartup] 9.469986ms
,2016-11-10 02:03:13.532 ThaliTest[3251:7282237] Resetting plugins due to page load.
,2016-11-10 02:03:13.930 ThaliTest[3251:7282237] Finished load of: file:///var/containers/Bundle/Application/EDA62B0E-17AE-4573-A71E-46D95E23E2F7/ThaliTest.app/www/index.html
,2016-11-10 02:03:14.271 ThaliTest[3251:7282237] JXcore Cordova plugin initializing
,2016-11-10 02:03:14.272 ThaliTest[3251:7282434] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 10:03:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 10:03:48 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  23.58627599477768
,Failed to execute UT.
,2016-11-10 10:03:48 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
