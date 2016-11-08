#### Test 927335313b70e13_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/966B0810-8783-45A0-B885-F8BF17F63437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/966B0810-8783-45A0-B885-F8BF17F63437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CDC2DBEA-0A48-4704-BB3E-B6C1114F36B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65504"
,(lldb)     command script import "/tmp/966B0810-8783-45A0-B885-F8BF17F63437/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 11:42:08.417 ThaliTest[5225:11241418] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C35CE69D-00ED-4E2E-AC35-4B3854DAC6F6/Library/Cookies/Cookies.binarycookies
,2016-11-08 11:42:08.740 ThaliTest[5225:11241418] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 11:42:08.741 ThaliTest[5225:11241418] Multi-tasking -> Device: YES, App: YES
,2016-11-08 11:42:08.758 ThaliTest[5225:11241418] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 11:42:10.567 ThaliTest[5225:11241418] Using UIWebView
,2016-11-08 11:42:10.574 ThaliTest[5225:11241418] [CDVTimer][handleopenurl] 0.437975ms
,2016-11-08 11:42:10.581 ThaliTest[5225:11241418] [CDVTimer][intentandnavigationfilter] 6.667972ms
,2016-11-08 11:42:10.582 ThaliTest[5225:11241418] [CDVTimer][gesturehandler] 0.304997ms
,2016-11-08 11:42:10.582 ThaliTest[5225:11241418] [CDVTimer][TotalPluginStartup] 9.002984ms
,2016-11-08 11:42:16.977 ThaliTest[5225:11241418] Resetting plugins due to page load.
,2016-11-08 11:42:19.941 ThaliTest[5225:11241418] Finished load of: file:///var/mobile/Containers/Bundle/Application/CDC2DBEA-0A48-4704-BB3E-B6C1114F36B3/ThaliTest.app/www/index.html
,2016-11-08 11:42:20.209 ThaliTest[5225:11241418] JXcore Cordova plugin initializing
,2016-11-08 11:42:20.211 ThaliTest[5225:11241667] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x155557170> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-11-08 10:43:04 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  98
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  34.64465296268463
,Failed to execute UT.
,2016-11-08 10:43:04 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
