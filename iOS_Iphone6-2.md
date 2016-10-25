#### Test 90793797671d7b3_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F7F3DB16-287B-4E44-A3B7-4FDB62EBEBCE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F7F3DB16-287B-4E44-A3B7-4FDB62EBEBCE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0442BB4B-38DC-41B4-B898-F3DCB3E0CD1B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64241"
,(lldb)     command script import "/tmp/F7F3DB16-287B-4E44-A3B7-4FDB62EBEBCE/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-25 05:25:42.486 ThaliTest[2755:5383965] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EB246587-A5F3-4D36-BA9C-0462A7804D96/Library/Cookies/Cookies.binarycookies
,2016-10-25 05:25:42.522 ThaliTest[2755:5383965] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-25 05:25:42.523 ThaliTest[2755:5383965] Multi-tasking -> Device: YES, App: YES
,2016-10-25 05:25:42.535 ThaliTest[2755:5383965] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-25 05:25:42.850 ThaliTest[2755:5383965] Using UIWebView
,2016-10-25 05:25:42.853 ThaliTest[2755:5383965] [CDVTimer][handleopenurl] 0.198960ms
,2016-10-25 05:25:42.857 ThaliTest[2755:5383965] [CDVTimer][intentandnavigationfilter] 3.421009ms
2016-10-25 05:25:42.858 ThaliTest[2755:5383965] [CDVTimer][gesturehandler] 0.137031ms
2016-10-25 05:25:42.858 ThaliTest[2755:5383965] [CDVTimer][TotalPluginStartup] 4.559994ms
,2016-10-25 05:25:49.151 ThaliTest[2755:5383965] Resetting plugins due to page load.
,2016-10-25 05:25:49.612 ThaliTest[2755:5383965] Finished load of: file:///var/containers/Bundle/Application/0442BB4B-38DC-41B4-B898-F3DCB3E0CD1B/ThaliTest.app/www/index.html
,2016-10-25 05:25:49.980 ThaliTest[2755:5383965] JXcore Cordova plugin initializing
,2016-10-25 05:25:49.981 ThaliTest[2755:5384132] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-25 12:26:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-25 12:26:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-25 12:26:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-25 12:26:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-25 12:26:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-25 12:26:25 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  25.08257299661636
,Failed to execute UT.
,2016-10-25 12:26:25 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
