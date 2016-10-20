#### Test 901473369726ba5_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F9A90BC2-9875-4826-8784-7FDB4D0183D8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F9A90BC2-9875-4826-8784-7FDB4D0183D8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/948037EA-A77B-466E-A19A-8F3001CD6E2D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52433"
,(lldb)     command script import "/tmp/F9A90BC2-9875-4826-8784-7FDB4D0183D8/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 00:57:44.174 ThaliTest[2615:4787617] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE207E17-5754-4769-A42C-61F6B0F4D237/Library/Cookies/Cookies.binarycookies
,2016-10-20 00:57:44.249 ThaliTest[2615:4787617] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 00:57:44.251 ThaliTest[2615:4787617] Multi-tasking -> Device: YES, App: YES
,2016-10-20 00:57:44.272 ThaliTest[2615:4787617] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 00:57:44.769 ThaliTest[2615:4787617] Using UIWebView
2016-10-20 00:57:44.775 ThaliTest[2615:4787617] [CDVTimer][handleopenurl] 0.321031ms
,2016-10-20 00:57:44.785 ThaliTest[2615:4787617] [CDVTimer][intentandnavigationfilter] 9.105980ms
2016-10-20 00:57:44.786 ThaliTest[2615:4787617] [CDVTimer][gesturehandler] 0.275016ms
2016-10-20 00:57:44.786 ThaliTest[2615:4787617] [CDVTimer][TotalPluginStartup] 11.165023ms
,2016-10-20 00:57:51.319 ThaliTest[2615:4787617] Resetting plugins due to page load.
,2016-10-20 00:57:52.021 ThaliTest[2615:4787617] Finished load of: file:///var/containers/Bundle/Application/948037EA-A77B-466E-A19A-8F3001CD6E2D/ThaliTest.app/www/index.html
,2016-10-20 00:57:52.388 ThaliTest[2615:4787617] JXcore Cordova plugin initializing
,2016-10-20 00:57:52.389 ThaliTest[2615:4787789] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-20 07:58:43 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  40.10246598720551
,Failed to execute UT.
,2016-10-20 07:58:43 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
