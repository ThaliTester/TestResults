#### Test 90009723439aaa5_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B4A58A9F-3AF1-4C3E-B255-2EDCA182E9FC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B4A58A9F-3AF1-4C3E-B255-2EDCA182E9FC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/098B05A3-2BF6-4746-A41E-0C55D22110E5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58988"
,(lldb)     command script import "/tmp/B4A58A9F-3AF1-4C3E-B255-2EDCA182E9FC/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 07:22:55.335 ThaliTest[2583:4702638] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C648D9F-2CCE-46BB-A866-82545E070F74/Library/Cookies/Cookies.binarycookies
,2016-10-19 07:22:55.371 ThaliTest[2583:4702638] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 07:22:55.372 ThaliTest[2583:4702638] Multi-tasking -> Device: YES, App: YES
,2016-10-19 07:22:55.383 ThaliTest[2583:4702638] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 07:22:55.705 ThaliTest[2583:4702638] Using UIWebView
2016-10-19 07:22:55.709 ThaliTest[2583:4702638] [CDVTimer][handleopenurl] 0.162005ms
,2016-10-19 07:22:55.715 ThaliTest[2583:4702638] [CDVTimer][intentandnavigationfilter] 5.212009ms
2016-10-19 07:22:55.715 ThaliTest[2583:4702638] [CDVTimer][gesturehandler] 0.170946ms
2016-10-19 07:22:55.715 ThaliTest[2583:4702638] [CDVTimer][TotalPluginStartup] 6.417990ms
,2016-10-19 07:23:01.254 ThaliTest[2583:4702638] Resetting plugins due to page load.
,2016-10-19 07:23:01.669 ThaliTest[2583:4702638] Finished load of: file:///var/containers/Bundle/Application/098B05A3-2BF6-4746-A41E-0C55D22110E5/ThaliTest.app/www/index.html
,2016-10-19 07:23:01.999 ThaliTest[2583:4702638] JXcore Cordova plugin initializing
,2016-10-19 07:23:02.000 ThaliTest[2583:4702891] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 14:23:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 14:23:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 14:23:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 14:23:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 14:23:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found two advertisers". in file: Optional("<unknown>"), line: 0
,XCTAssertEqual failed: ("nil") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 209
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-19 14:23:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  99
Number of failed tests:  5
Number of ignored tests:  0
Total duration:  25.87495195865631
Fa,iled to execute UT.
2016-10-19 14:23:38 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered

```
