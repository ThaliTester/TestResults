#### Test 89808901ab206e8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/05D43E0D-2DC4-4620-9426-1073DCC74B69/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/05D43E0D-2DC4-4620-9426-1073DCC74B69/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/76EFD498-B101-48EE-B92B-0779523FF828/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61376"
,(lldb)     command script import "/tmp/05D43E0D-2DC4-4620-9426-1073DCC74B69/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 15:14:58.311 ThaliTest[2407:5079966] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05ABA3B8-10B9-444F-95E1-BC6BA6600071/Library/Cookies/Cookies.binarycookies
,2016-10-18 15:14:58.388 ThaliTest[2407:5079966] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 15:14:58.390 ThaliTest[2407:5079966] Multi-tasking -> Device: YES, App: YES
,2016-10-18 15:14:58.411 ThaliTest[2407:5079966] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 15:14:58.861 ThaliTest[2407:5079966] Using UIWebView
,2016-10-18 15:14:58.868 ThaliTest[2407:5079966] [CDVTimer][handleopenurl] 0.353992ms
,2016-10-18 15:14:58.877 ThaliTest[2407:5079966] [CDVTimer][intentandnavigationfilter] 7.979989ms
2016-10-18 15:14:58.877 ThaliTest[2407:5079966] [CDVTimer][gesturehandler] 0.293016ms
2016-10-18 15:14:58.878 ThaliTest[2407:5079966] [CDVTimer][TotalPluginStartup] 10.238945ms
,2016-10-18 15:15:03.900 ThaliTest[2407:5079966] Resetting plugins due to page load.
,2016-10-18 15:15:04.238 ThaliTest[2407:5079966] Finished load of: file:///var/containers/Bundle/Application/76EFD498-B101-48EE-B92B-0779523FF828/ThaliTest.app/www/index.html
,2016-10-18 15:15:04.568 ThaliTest[2407:5079966] JXcore Cordova plugin initializing
,2016-10-18 15:15:04.569 ThaliTest[2407:5080154] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 13:15:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 13:15:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 13:15:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 13:15:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 13:15:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-18 13:15:40 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  101
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  25.33706796169281
F,ailed to execute UT.
2016-10-18 13:15:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
