#### Test 921522868c3974a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A498E117-E164-4007-86E3-88E20FF690DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A498E117-E164-4007-86E3-88E20FF690DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522868c3974a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/84C20721-6303-4B40-BE11-A2AAD2006997/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53786"
,(lldb)     command script import "/tmp/A498E117-E164-4007-86E3-88E20FF690DA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 11:02:47.369 ThaliTest[5352:11494770] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2D9F745C-EC70-4DEB-A6A0-19EF4A419EB5/Library/Cookies/Cookies.binarycookies
,2016-11-10 11:02:47.593 ThaliTest[5352:11494770] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 11:02:47.594 ThaliTest[5352:11494770] Multi-tasking -> Device: YES, App: YES
,2016-11-10 11:02:47.607 ThaliTest[5352:11494770] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 11:02:48.446 ThaliTest[5352:11494770] Using UIWebView
,2016-11-10 11:02:48.449 ThaliTest[5352:11494770] [CDVTimer][handleopenurl] 0.099003ms
,2016-11-10 11:02:48.451 ThaliTest[5352:11494770] [CDVTimer][intentandnavigationfilter] 1.877010ms
,2016-11-10 11:02:48.451 ThaliTest[5352:11494770] [CDVTimer][gesturehandler] 0.082016ms
,2016-11-10 11:02:48.451 ThaliTest[5352:11494770] [CDVTimer][TotalPluginStartup] 2.488017ms
,2016-11-10 11:02:51.580 ThaliTest[5352:11494770] Resetting plugins due to page load.
,2016-11-10 11:02:52.985 ThaliTest[5352:11494770] Finished load of: file:///var/mobile/Containers/Bundle/Application/84C20721-6303-4B40-BE11-A2AAD2006997/ThaliTest.app/www/index.html
,2016-11-10 11:02:53.120 ThaliTest[5352:11494770] JXcore Cordova plugin initializing
,2016-11-10 11:02:53.121 ThaliTest[5352:11494976] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 10:03:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-11-10 10:03:35 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  102
Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  33.06921297311783
,Failed to execute UT.
,2016-11-10 10:03:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
