#### Test 9015365044655ae_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9015365044655ae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AB196BB4-B9B2-4EAA-A6A1-E925FD627AC3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AB196BB4-B9B2-4EAA-A6A1-E925FD627AC3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9015365044655ae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9015365044655ae/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C2C3E44F-118D-41AF-9FC4-5E015AAD55D1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62894"
,(lldb)     command script import "/tmp/AB196BB4-B9B2-4EAA-A6A1-E925FD627AC3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 13:31:47.119 ThaliTest[4551:8918418] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B175AE3-6419-44CE-BA52-A1E9F5C96BA9/Library/Cookies/Cookies.binarycookies
,2016-10-20 13:31:47.511 ThaliTest[4551:8918418] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 13:31:47.513 ThaliTest[4551:8918418] Multi-tasking -> Device: YES, App: YES
,2016-10-20 13:31:47.535 ThaliTest[4551:8918418] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 13:31:49.520 ThaliTest[4551:8918418] Using UIWebView
,2016-10-20 13:31:49.529 ThaliTest[4551:8918418] [CDVTimer][handleopenurl] 0.333965ms
,2016-10-20 13:31:49.536 ThaliTest[4551:8918418] [CDVTimer][intentandnavigationfilter] 6.383002ms
,2016-10-20 13:31:49.537 ThaliTest[4551:8918418] [CDVTimer][gesturehandler] 0.288010ms
,2016-10-20 13:31:49.537 ThaliTest[4551:8918418] [CDVTimer][TotalPluginStartup] 8.529007ms
,2016-10-20 13:31:55.993 ThaliTest[4551:8918418] Resetting plugins due to page load.
,2016-10-20 13:31:59.117 ThaliTest[4551:8918418] Finished load of: file:///var/mobile/Containers/Bundle/Application/C2C3E44F-118D-41AF-9FC4-5E015AAD55D1/ThaliTest.app/www/index.html
,2016-10-20 13:31:59.334 ThaliTest[4551:8918418] JXcore Cordova plugin initializing
,2016-10-20 13:31:59.334 ThaliTest[4551:8918670] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 11:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-20 11:32:41 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  32.21639001369476
,Failed to execute UT.
,2016-10-20 11:32:41 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
