#### Test 927335313b70e13_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B22BC3B3-73BD-45AB-A67B-5F39A5D7E5F8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B22BC3B3-73BD-45AB-A67B-5F39A5D7E5F8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/927335313b70e13/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3EEA885B-02EA-4123-8FA0-4F69502070C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65507"
,(lldb)     command script import "/tmp/B22BC3B3-73BD-45AB-A67B-5F39A5D7E5F8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 11:42:05.285 ThaliTest[5337:13477158] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C321E11-5101-4FC7-AFD3-60CDE981B0DB/Library/Cookies/Cookies.binarycookies
,2016-11-08 11:42:05.401 ThaliTest[5337:13477158] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 11:42:05.403 ThaliTest[5337:13477158] Multi-tasking -> Device: YES, App: YES
,2016-11-08 11:42:05.426 ThaliTest[5337:13477158] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 11:42:06.975 ThaliTest[5337:13477158] Using UIWebView
,2016-11-08 11:42:06.984 ThaliTest[5337:13477158] [CDVTimer][handleopenurl] 0.568986ms
,2016-11-08 11:42:06.994 ThaliTest[5337:13477158] [CDVTimer][intentandnavigationfilter] 8.828998ms
2016-11-08 11:42:06.995 ThaliTest[5337:13477158] [CDVTimer][gesturehandler] 0.392020ms
2016-11-08 11:42:06.995 ThaliTest[5337:13477158] [CDVTimer][TotalPlug,inStartup] 12.261033ms
,2016-11-08 11:42:12.878 ThaliTest[5337:13477158] Resetting plugins due to page load.
,2016-11-08 11:42:16.305 ThaliTest[5337:13477158] Finished load of: file:///var/mobile/Containers/Bundle/Application/3EEA885B-02EA-4123-8FA0-4F69502070C4/ThaliTest.app/www/index.html
,2016-11-08 11:42:16.612 ThaliTest[5337:13477158] JXcore Cordova plugin initializing
,2016-11-08 11:42:16.614 ThaliTest[5337:13477388] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x140108860> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-08 10:42:54 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  96
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  25.15205496549606
,Failed to execute UT.
,2016-11-08 10:42:54 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
