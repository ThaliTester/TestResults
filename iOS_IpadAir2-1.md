#### Test 91818238ff180c4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E222C9C9-C48E-4E2D-A456-D08964FC257D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E222C9C9-C48E-4E2D-A456-D08964FC257D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3793B4B9-5528-489D-86FF-7C36CB110B24/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58824"
,(lldb)     command script import "/tmp/E222C9C9-C48E-4E2D-A456-D08964FC257D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-03 12:11:36.216 ThaliTest[5011:10623298] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/454864F5-01F6-4C0A-93F1-04C73F12FC84/Library/Cookies/Cookies.binarycookies
,2016-11-03 12:11:36.603 ThaliTest[5011:10623298] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 12:11:36.605 ThaliTest[5011:10623298] Multi-tasking -> Device: YES, App: YES
,2016-11-03 12:11:36.627 ThaliTest[5011:10623298] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 12:11:38.690 ThaliTest[5011:10623298] Using UIWebView
,2016-11-03 12:11:38.697 ThaliTest[5011:10623298] [CDVTimer][handleopenurl] 0.316978ms
,2016-11-03 12:11:38.705 ThaliTest[5011:10623298] [CDVTimer][intentandnavigationfilter] 7.536948ms
,2016-11-03 12:11:38.706 ThaliTest[5011:10623298] [CDVTimer][gesturehandler] 0.458956ms
2016-11-03 12:11:38.706 ThaliTest[5011:10623298] [CDVTimer][TotalPluginStartup] 9.981990ms
,2016-11-03 12:11:45.437 ThaliTest[5011:10623298] Resetting plugins due to page load.
,2016-11-03 12:11:48.538 ThaliTest[5011:10623298] Finished load of: file:///var/mobile/Containers/Bundle/Application/3793B4B9-5528-489D-86FF-7C36CB110B24/ThaliTest.app/www/index.html
,2016-11-03 12:11:48.768 ThaliTest[5011:10623298] JXcore Cordova plugin initializing
,2016-11-03 12:11:48.769 ThaliTest[5011:10623580] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:11:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:11:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:11:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:11:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:11:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-11-03 11:12:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  33.20554405450821
,Failed to execute UT.
,2016-11-03 11:12:31 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
