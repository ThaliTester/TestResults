#### Test 92339050883a779_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9361B125-A3ED-47F1-8F34-61FA2266E5EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9361B125-A3ED-47F1-8F34-61FA2266E5EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/679B6B78-968B-4773-9DF4-ACAFB0275768/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54637"
,(lldb)     command script import "/tmp/9361B125-A3ED-47F1-8F34-61FA2266E5EE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 19:52:42.091 ThaliTest[5368:13535300] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EF0657B2-7A3C-4C5A-A661-B97FE9147BA9/Library/Cookies/Cookies.binarycookies
,2016-11-08 19:52:42.688 ThaliTest[5368:13535300] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 19:52:42.689 ThaliTest[5368:13535300] Multi-tasking -> Device: YES, App: YES
,2016-11-08 19:52:42.708 ThaliTest[5368:13535300] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 19:52:44.146 ThaliTest[5368:13535300] Using UIWebView
,2016-11-08 19:52:44.154 ThaliTest[5368:13535300] [CDVTimer][handleopenurl] 0.683963ms
,2016-11-08 19:52:44.164 ThaliTest[5368:13535300] [CDVTimer][intentandnavigationfilter] 8.674979ms
2016-11-08 19:52:44.165 ThaliTest[5368:13535300] [CDVTimer][gesturehandler] 0.411987ms
2016-11-08 19:52:44.165 ThaliTest[5368:13535300] [CDVTimer][TotalPlug,inStartup] 11.631012ms
,2016-11-08 19:52:50.202 ThaliTest[5368:13535300] Resetting plugins due to page load.
,2016-11-08 19:52:53.236 ThaliTest[5368:13535300] Finished load of: file:///var/mobile/Containers/Bundle/Application/679B6B78-968B-4773-9DF4-ACAFB0275768/ThaliTest.app/www/index.html
,2016-11-08 19:52:53.562 ThaliTest[5368:13535300] JXcore Cordova plugin initializing
,2016-11-08 19:52:53.563 ThaliTest[5368:13535528] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 18:53:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 18:53:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 18:53:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 18:53:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 18:53:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x14fe10d70> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-08 18:53:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
,Number of passed tests:  96
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  23.35227996110916
,Failed to execute UT.
,2016-11-08 18:53:30 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
