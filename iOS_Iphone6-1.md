#### Test 91818238ff180c4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/66C088B4-D730-4CF1-8332-47DC23A8F963/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/66C088B4-D730-4CF1-8332-47DC23A8F963/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B3EA773E-304F-4AD2-856C-53EDA2C31BAC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58763"
,(lldb)     command script import "/tmp/66C088B4-D730-4CF1-8332-47DC23A8F963/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-03 12:11:23.230 ThaliTest[2985:7205689] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30B4D40E-1FAA-4A90-9664-302C37448E75/Library/Cookies/Cookies.binarycookies
,2016-11-03 12:11:23.270 ThaliTest[2985:7205689] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 12:11:23.271 ThaliTest[2985:7205689] Multi-tasking -> Device: YES, App: YES
,2016-11-03 12:11:23.282 ThaliTest[2985:7205689] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 12:11:23.565 ThaliTest[2985:7205689] Using UIWebView
,2016-11-03 12:11:23.568 ThaliTest[2985:7205689] [CDVTimer][handleopenurl] 0.140965ms
,2016-11-03 12:11:23.571 ThaliTest[2985:7205689] [CDVTimer][intentandnavigationfilter] 2.668977ms
2016-11-03 12:11:23.571 ThaliTest[2985:7205689] [CDVTimer][gesturehandler] 0.105023ms
2016-11-03 12:11:23.571 ThaliTest[2985:7205689] [CDVTimer][TotalPluginStartup] 3.542006ms
,2016-11-03 12:11:28.865 ThaliTest[2985:7205689] Resetting plugins due to page load.
,2016-11-03 12:11:29.162 ThaliTest[2985:7205689] Finished load of: file:///var/containers/Bundle/Application/B3EA773E-304F-4AD2-856C-53EDA2C31BAC/ThaliTest.app/www/index.html
,2016-11-03 12:11:29.496 ThaliTest[2985:7205689] JXcore Cordova plugin initializing
,2016-11-03 12:11:29.497 ThaliTest[2985:7205870] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:11:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:11:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:11:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:11:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:11:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x129024ee0> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-03 11:12:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
Number of passed tests:  98
Number of failed tests:  4
Number of ignored tests:  0
Total duration:  24.97855198383331
Fa,iled to execute UT.
2016-11-03 11:12:05 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered

```
