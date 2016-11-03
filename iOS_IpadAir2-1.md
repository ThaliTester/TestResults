#### Test 91818238c75484c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8EA2A84D-5425-47EF-97DE-E4AD7CD46625/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8EA2A84D-5425-47EF-97DE-E4AD7CD46625/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C39F3FC2-FE4B-4B76-870B-50A33B6E97F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60068"
,(lldb)     command script import "/tmp/8EA2A84D-5425-47EF-97DE-E4AD7CD46625/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-03 12:28:58.401 ThaliTest[5019:10626154] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/421E420C-FF4E-4A48-990E-19BA4D85785F/Library/Cookies/Cookies.binarycookies
,2016-11-03 12:28:58.777 ThaliTest[5019:10626154] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 12:28:58.779 ThaliTest[5019:10626154] Multi-tasking -> Device: YES, App: YES
,2016-11-03 12:28:58.801 ThaliTest[5019:10626154] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 12:29:00.782 ThaliTest[5019:10626154] Using UIWebView
,2016-11-03 12:29:00.789 ThaliTest[5019:10626154] [CDVTimer][handleopenurl] 0.353992ms
,2016-11-03 12:29:00.797 ThaliTest[5019:10626154] [CDVTimer][intentandnavigationfilter] 7.185996ms
,2016-11-03 12:29:00.797 ThaliTest[5019:10626154] [CDVTimer][gesturehandler] 0.304997ms
,2016-11-03 12:29:00.798 ThaliTest[5019:10626154] [CDVTimer][TotalPluginStartup] 9.407997ms
,2016-11-03 12:29:07.534 ThaliTest[5019:10626154] Resetting plugins due to page load.
,2016-11-03 12:29:10.479 ThaliTest[5019:10626154] Finished load of: file:///var/mobile/Containers/Bundle/Application/C39F3FC2-FE4B-4B76-870B-50A33B6E97F4/ThaliTest.app/www/index.html
,2016-11-03 12:29:10.746 ThaliTest[5019:10626154] JXcore Cordova plugin initializing
,2016-11-03 12:29:10.746 ThaliTest[5019:10626402] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:29:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x162fb9770> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-03 11:29:54 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  98
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  33.92973202466965
,Failed to execute UT.
,2016-11-03 11:29:54 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
