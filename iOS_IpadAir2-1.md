#### Test 92339050883a779_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4C171AC1-581B-4BD5-8A3F-8B7AF1295B3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4C171AC1-581B-4BD5-8A3F-8B7AF1295B3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/92339050883a779/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9E3678F9-E86E-4D4A-AECE-7AB45498FF55/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54551"
,(lldb)     command script import "/tmp/4C171AC1-581B-4BD5-8A3F-8B7AF1295B3C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 19:52:33.101 ThaliTest[5259:11288811] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/087D8F53-9A75-4407-9594-B34CE1C629B9/Library/Cookies/Cookies.binarycookies
,2016-11-08 19:52:33.436 ThaliTest[5259:11288811] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 19:52:33.437 ThaliTest[5259:11288811] Multi-tasking -> Device: YES, App: YES
,2016-11-08 19:52:33.453 ThaliTest[5259:11288811] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 19:52:35.333 ThaliTest[5259:11288811] Using UIWebView
,2016-11-08 19:52:35.339 ThaliTest[5259:11288811] [CDVTimer][handleopenurl] 0.343025ms
,2016-11-08 19:52:35.346 ThaliTest[5259:11288811] [CDVTimer][intentandnavigationfilter] 6.452978ms
,2016-11-08 19:52:35.347 ThaliTest[5259:11288811] [CDVTimer][gesturehandler] 0.277996ms
,2016-11-08 19:52:35.347 ThaliTest[5259:11288811] [CDVTimer][TotalPluginStartup] 8.547008ms
,2016-11-08 19:52:41.630 ThaliTest[5259:11288811] Resetting plugins due to page load.
,2016-11-08 19:52:44.525 ThaliTest[5259:11288811] Finished load of: file:///var/mobile/Containers/Bundle/Application/9E3678F9-E86E-4D4A-AECE-7AB45498FF55/ThaliTest.app/www/index.html
,2016-11-08 19:52:44.803 ThaliTest[5259:11288811] JXcore Cordova plugin initializing
,2016-11-08 19:52:44.803 ThaliTest[5259:11289049] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 18:52:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 18:52:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 18:52:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 18:52:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 18:52:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 18:53:29 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  34.55827403068542
,Failed to execute UT.
,2016-11-08 18:53:29 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
