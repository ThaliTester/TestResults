#### Test 91818238c75484c_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/37070381-1F5E-4B38-B7C9-4A7FECDB686B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/37070381-1F5E-4B38-B7C9-4A7FECDB686B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3FB63DBF-9CA4-4F35-8741-1725522C1A3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60127"
,(lldb)     command script import "/tmp/37070381-1F5E-4B38-B7C9-4A7FECDB686B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-03 04:29:02.063 ThaliTest[2962:6428017] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/653FB58C-BE31-4C1B-81A2-FD2FCB8D30BA/Library/Cookies/Cookies.binarycookies
,2016-11-03 04:29:02.147 ThaliTest[2962:6428017] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 04:29:02.149 ThaliTest[2962:6428017] Multi-tasking -> Device: YES, App: YES
,2016-11-03 04:29:02.172 ThaliTest[2962:6428017] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 04:29:02.678 ThaliTest[2962:6428017] Using UIWebView
,2016-11-03 04:29:02.688 ThaliTest[2962:6428017] [CDVTimer][handleopenurl] 0.405967ms
,2016-11-03 04:29:02.696 ThaliTest[2962:6428017] [CDVTimer][intentandnavigationfilter] 7.182002ms
2016-11-03 04:29:02.697 ThaliTest[2962:6428017] [CDVTimer][gesturehandler] 0.292003ms
2016-11-03 04:29:02.697 ThaliTest[2962:6428017] [CDVTimer][TotalPluginStartup] 9.532988ms
,2016-11-03 04:29:08.688 ThaliTest[2962:6428017] Resetting plugins due to page load.
,2016-11-03 04:29:09.159 ThaliTest[2962:6428017] Finished load of: file:///var/containers/Bundle/Application/3FB63DBF-9CA4-4F35-8741-1725522C1A3C/ThaliTest.app/www/index.html
,2016-11-03 04:29:09.529 ThaliTest[2962:6428017] JXcore Cordova plugin initializing
,2016-11-03 04:29:09.530 ThaliTest[2962:6428188] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:29:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x1503155a0> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-03 11:29:45 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  97
,Number of failed tests:  5
,Number of ignored tests:  0
,Total duration:  25.05055302381516
,Failed to execute UT.
,2016-11-03 11:29:45 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
