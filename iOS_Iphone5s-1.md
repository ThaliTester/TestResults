#### Test 91818238c75484c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E8150274-A3E5-4716-B343-64732A5898C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E8150274-A3E5-4716-B343-64732A5898C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238c75484c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/20285CF0-5382-4211-AE12-474C2D973226/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60030"
,(lldb)     command script import "/tmp/E8150274-A3E5-4716-B343-64732A5898C2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-03 12:28:51.707 ThaliTest[5099:12676810] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7870D491-AAD7-4AD8-A84A-962A922C1C4A/Library/Cookies/Cookies.binarycookies
,2016-11-03 12:28:51.835 ThaliTest[5099:12676810] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 12:28:51.837 ThaliTest[5099:12676810] Multi-tasking -> Device: YES, App: YES
,2016-11-03 12:28:51.863 ThaliTest[5099:12676810] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 12:28:53.371 ThaliTest[5099:12676810] Using UIWebView
,2016-11-03 12:28:53.383 ThaliTest[5099:12676810] [CDVTimer][handleopenurl] 0.482976ms
,2016-11-03 12:28:53.392 ThaliTest[5099:12676810] [CDVTimer][intentandnavigationfilter] 8.337975ms
2016-11-03 12:28:53.393 ThaliTest[5099:12676810] [CDVTimer][gesturehandler] 0.361979ms
2016-11-03 12:28:53.393 ThaliTest[5099:12676810] [CDVTimer][TotalPlug,inStartup] 11.055946ms
,2016-11-03 12:28:59.477 ThaliTest[5099:12676810] Resetting plugins due to page load.
,2016-11-03 12:29:02.850 ThaliTest[5099:12676810] Finished load of: file:///var/mobile/Containers/Bundle/Application/20285CF0-5382-4211-AE12-474C2D973226/ThaliTest.app/www/index.html
,2016-11-03 12:29:03.037 ThaliTest[5099:12676810] JXcore Cordova plugin initializing
,2016-11-03 12:29:03.038 ThaliTest[5099:12677035] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:29:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:29:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:29:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:29:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:29:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x1409a1d20> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-03 11:29:40 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  98
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  24.33001798391342
,Failed to execute UT.
,2016-11-03 11:29:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
