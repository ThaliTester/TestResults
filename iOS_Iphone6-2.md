#### Test 88496963ea5ebba_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/37077B54-8BB3-4F4D-9A66-64A5C8F0D68A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/37077B54-8BB3-4F4D-9A66-64A5C8F0D68A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5B612883-4778-4E73-8FE2-B7DB2F207F4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49345"
,(lldb)     command script import "/tmp/37077B54-8BB3-4F4D-9A66-64A5C8F0D68A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 13:40:58.745 ThaliTest[2600:4734145] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF82312E-0873-47D5-B19B-0E05805C67DB/Library/Cookies/Cookies.binarycookies
,2016-10-19 13:40:58.798 ThaliTest[2600:4734145] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 13:40:58.799 ThaliTest[2600:4734145] Multi-tasking -> Device: YES, App: YES
,2016-10-19 13:40:58.811 ThaliTest[2600:4734145] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 13:40:59.130 ThaliTest[2600:4734145] Using UIWebView
,2016-10-19 13:40:59.133 ThaliTest[2600:4734145] [CDVTimer][handleopenurl] 0.213981ms
,2016-10-19 13:40:59.138 ThaliTest[2600:4734145] [CDVTimer][intentandnavigationfilter] 4.528046ms
2016-10-19 13:40:59.138 ThaliTest[2600:4734145] [CDVTimer][gesturehandler] 0.172019ms
2016-10-19 13:40:59.139 ThaliTest[2600:4734145] [CDVTimer][TotalPluginStartup] 5.737007ms
,2016-10-19 13:41:07.088 ThaliTest[2600:4734145] Resetting plugins due to page load.
,2016-10-19 13:41:07.798 ThaliTest[2600:4734145] Finished load of: file:///var/containers/Bundle/Application/5B612883-4778-4E73-8FE2-B7DB2F207F4C/ThaliTest.app/www/index.html
,2016-10-19 13:41:08.169 ThaliTest[2600:4734145] JXcore Cordova plugin initializing
,2016-10-19 13:41:08.170 ThaliTest[2600:4734340] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 20:41:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 20:41:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 20:41:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 20:41:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 20:41:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 334
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-19 20:41:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  100
Number of failed tests:  4
Number of ignored tests:  0
Total duration:  23.64912402629852
F,ailed to execute UT.
2016-10-19 20:41:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
