#### Test 91818238ff180c4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD982CC6-A8CD-458D-9818-D6378B8CCECD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DD982CC6-A8CD-458D-9818-D6378B8CCECD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/91818238ff180c4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7AA2641-F061-4D6C-84FA-1A2D831C125D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58716"
,(lldb)     command script import "/tmp/DD982CC6-A8CD-458D-9818-D6378B8CCECD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-03 12:11:21.851 ThaliTest[5090:12673946] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9D60E40-BC97-4D7E-BEE4-8F974BD3F2A8/Library/Cookies/Cookies.binarycookies
,2016-11-03 12:11:21.986 ThaliTest[5090:12673946] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-03 12:11:21.987 ThaliTest[5090:12673946] Multi-tasking -> Device: YES, App: YES
,2016-11-03 12:11:22.006 ThaliTest[5090:12673946] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-03 12:11:23.494 ThaliTest[5090:12673946] Using UIWebView
,2016-11-03 12:11:23.503 ThaliTest[5090:12673946] [CDVTimer][handleopenurl] 0.693977ms
,2016-11-03 12:11:23.512 ThaliTest[5090:12673946] [CDVTimer][intentandnavigationfilter] 8.650005ms
2016-11-03 12:11:23.513 ThaliTest[5090:12673946] [CDVTimer][gesturehandler] 0.389993ms
2016-11-03 12:11:23.513 ThaliTest[5090:12673946] [CDVTimer][TotalPlug,inStartup] 11.657000ms
,2016-11-03 12:11:29.255 ThaliTest[5090:12673946] Resetting plugins due to page load.
,2016-11-03 12:11:32.720 ThaliTest[5090:12673946] Finished load of: file:///var/mobile/Containers/Bundle/Application/F7AA2641-F061-4D6C-84FA-1A2D831C125D/ThaliTest.app/www/index.html
,2016-11-03 12:11:33.032 ThaliTest[5090:12673946] JXcore Cordova plugin initializing
2016-11-03 12:11:33.034 ThaliTest[5090:12674190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-03 11:11:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-03 11:11:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-03 11:11:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-03 11:11:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-03 11:11:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-11-03 11:12:10 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
Number of passed tests:  98
Number of failed tests:  4
Number of ignored tests:  0
Total duration:  24.76780098676682
Fa,iled to execute UT.
2016-11-03 11:12:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
