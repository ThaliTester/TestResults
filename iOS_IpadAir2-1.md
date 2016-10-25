#### Test 90793797671d7b3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/88E91169-3823-4088-85D5-4DCCB2CE4ACB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/88E91169-3823-4088-85D5-4DCCB2CE4ACB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5CD7E63E-A732-482B-AF4A-E71C1816E1EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64243"
,(lldb)     command script import "/tmp/88E91169-3823-4088-85D5-4DCCB2CE4ACB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-25 14:25:58.161 ThaliTest[4717:9516140] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1F7190C7-52D7-4121-A291-2DCEC5B0AD1A/Library/Cookies/Cookies.binarycookies
,2016-10-25 14:25:58.559 ThaliTest[4717:9516140] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-25 14:25:58.560 ThaliTest[4717:9516140] Multi-tasking -> Device: YES, App: YES
,2016-10-25 14:25:58.578 ThaliTest[4717:9516140] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-25 14:26:01.042 ThaliTest[4717:9516140] Using UIWebView
,2016-10-25 14:26:01.052 ThaliTest[4717:9516140] [CDVTimer][handleopenurl] 0.365019ms
,2016-10-25 14:26:01.059 ThaliTest[4717:9516140] [CDVTimer][intentandnavigationfilter] 6.475031ms
,2016-10-25 14:26:01.059 ThaliTest[4717:9516140] [CDVTimer][gesturehandler] 0.294983ms
,2016-10-25 14:26:01.060 ThaliTest[4717:9516140] [CDVTimer][TotalPluginStartup] 8.832037ms
,2016-10-25 14:26:09.229 ThaliTest[4717:9516140] Resetting plugins due to page load.
,2016-10-25 14:26:12.939 ThaliTest[4717:9516140] Finished load of: file:///var/mobile/Containers/Bundle/Application/5CD7E63E-A732-482B-AF4A-E71C1816E1EE/ThaliTest.app/www/index.html
,2016-10-25 14:26:13.220 ThaliTest[4717:9516140] JXcore Cordova plugin initializing
,2016-10-25 14:26:13.220 ThaliTest[4717:9516447] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-25 12:26:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-25 12:26:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-25 12:26:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-25 12:26:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-25 12:26:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-25 12:26:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  32.50637501478195
,Failed to execute UT.
,2016-10-25 12:26:55 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
