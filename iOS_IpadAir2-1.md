#### Test 89808901ab206e8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8DB59C17-A427-45A4-8FC4-B30DD997E000/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8DB59C17-A427-45A4-8FC4-B30DD997E000/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4D49B87B-E9C8-414D-831F-1748BE617426/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61322"
,(lldb)     command script import "/tmp/8DB59C17-A427-45A4-8FC4-B30DD997E000/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 15:14:59.091 ThaliTest[4401:8670801] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B108444-2F4F-445E-B467-F8712E784DE0/Library/Cookies/Cookies.binarycookies
,2016-10-18 15:14:59.442 ThaliTest[4401:8670801] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 15:14:59.443 ThaliTest[4401:8670801] Multi-tasking -> Device: YES, App: YES
,2016-10-18 15:14:59.461 ThaliTest[4401:8670801] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 15:15:01.342 ThaliTest[4401:8670801] Using UIWebView
,2016-10-18 15:15:01.352 ThaliTest[4401:8670801] [CDVTimer][handleopenurl] 0.395000ms
,2016-10-18 15:15:01.360 ThaliTest[4401:8670801] [CDVTimer][intentandnavigationfilter] 7.021010ms
,2016-10-18 15:15:01.361 ThaliTest[4401:8670801] [CDVTimer][gesturehandler] 0.320017ms
,2016-10-18 15:15:01.361 ThaliTest[4401:8670801] [CDVTimer][TotalPluginStartup] 10.394990ms
,2016-10-18 15:15:07.707 ThaliTest[4401:8670801] Resetting plugins due to page load.
,2016-10-18 15:15:10.722 ThaliTest[4401:8670801] Finished load of: file:///var/mobile/Containers/Bundle/Application/4D49B87B-E9C8-414D-831F-1748BE617426/ThaliTest.app/www/index.html
,2016-10-18 15:15:10.939 ThaliTest[4401:8670801] JXcore Cordova plugin initializing
,2016-10-18 15:15:10.940 ThaliTest[4401:8671073] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 13:15:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 13:15:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 13:15:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 13:15:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 13:15:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 13:15:52 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  32.3271290063858
,Failed to execute UT.
,2016-10-18 13:15:52 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
