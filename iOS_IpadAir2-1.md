#### Test 89786516a9cd264_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6A4D0803-5E3B-4061-8421-D3D720AF1840/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6A4D0803-5E3B-4061-8421-D3D720AF1840/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F9A387E1-AB10-4B6B-B32B-07B955BAA3D0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59334"
,(lldb)     command script import "/tmp/6A4D0803-5E3B-4061-8421-D3D720AF1840/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 12:43:25.886 ThaliTest[4391:8657559] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/03266329-5130-414C-B2F5-6F93E2842B73/Library/Cookies/Cookies.binarycookies
,2016-10-18 12:43:26.155 ThaliTest[4391:8657559] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 12:43:26.156 ThaliTest[4391:8657559] Multi-tasking -> Device: YES, App: YES
,2016-10-18 12:43:26.171 ThaliTest[4391:8657559] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 12:43:27.064 ThaliTest[4391:8657559] Using UIWebView
,2016-10-18 12:43:27.067 ThaliTest[4391:8657559] [CDVTimer][handleopenurl] 0.106990ms
,2016-10-18 12:43:27.069 ThaliTest[4391:8657559] [CDVTimer][intentandnavigationfilter] 2.004981ms
2016-10-18 12:43:27.069 ThaliTest[4391:8657559] [CDVTimer][gesturehandler] 0.078976ms
2016-10-18 12:43:27.069 ThaliTest[4391:8657559] [CDVTimer][TotalPluginStartup] 2.660990ms
,2016-10-18 12:43:30.344 ThaliTest[4391:8657559] Resetting plugins due to page load.
,2016-10-18 12:43:31.592 ThaliTest[4391:8657559] Finished load of: file:///var/mobile/Containers/Bundle/Application/F9A387E1-AB10-4B6B-B32B-07B955BAA3D0/ThaliTest.app/www/index.html
,2016-10-18 12:43:31.748 ThaliTest[4391:8657559] JXcore Cordova plugin initializing
2016-10-18 12:43:31.749 ThaliTest[4391:8657730] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 10:43:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-18 10:43:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 10:43:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 10:43:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-18 10:43:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 321
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 10:44:13 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  31.76964098215103
,Failed to execute UT.
,2016-10-18 10:44:13 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
