#### Test 90009723439aaa5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FB27C81D-B13D-4517-8880-BE653C3EAACB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FB27C81D-B13D-4517-8880-BE653C3EAACB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/25C8306B-C2AB-4F78-999C-96C9FE59B84B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58968"
,(lldb)     command script import "/tmp/FB27C81D-B13D-4517-8880-BE653C3EAACB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 16:22:54.350 ThaliTest[2473:5219392] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF5946B7-ECB4-4226-BF37-A08746FA454A/Library/Cookies/Cookies.binarycookies
,2016-10-19 16:22:54.425 ThaliTest[2473:5219392] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 16:22:54.427 ThaliTest[2473:5219392] Multi-tasking -> Device: YES, App: YES
,2016-10-19 16:22:54.445 ThaliTest[2473:5219392] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 16:22:54.890 ThaliTest[2473:5219392] Using UIWebView
,2016-10-19 16:22:54.897 ThaliTest[2473:5219392] [CDVTimer][handleopenurl] 0.468969ms
,2016-10-19 16:22:54.906 ThaliTest[2473:5219392] [CDVTimer][intentandnavigationfilter] 8.022010ms
2016-10-19 16:22:54.906 ThaliTest[2473:5219392] [CDVTimer][gesturehandler] 0.326991ms
2016-10-19 16:22:54.907 ThaliTest[2473:5219392] [CDVTimer][TotalPluginS,tartup] 10.564029ms
,2016-10-19 16:23:00.238 ThaliTest[2473:5219392] Resetting plugins due to page load.
,2016-10-19 16:23:00.607 ThaliTest[2473:5219392] Finished load of: file:///var/containers/Bundle/Application/25C8306B-C2AB-4F78-999C-96C9FE59B84B/ThaliTest.app/www/index.html
,2016-10-19 16:23:00.935 ThaliTest[2473:5219392] JXcore Cordova plugin initializing
2016-10-19 16:23:00.936 ThaliTest[2473:5219572] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 14:23:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 14:23:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 14:23:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 14:23:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 14:23:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found two advertisers". in file: Optional("<unknown>"), line: 0
,XCTAssertEqual failed: ("nil") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 209
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x158194270> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-19 14:23:37 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  98
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  25.88479202985764
,Failed to execute UT.
,2016-10-19 14:23:37 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
