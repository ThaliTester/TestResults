#### Test 90009723439aaa5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/05E4A5D1-0EEB-47FC-B880-0169B25CCC6C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/05E4A5D1-0EEB-47FC-B880-0169B25CCC6C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50E4979A-1937-4BA4-9640-9C53003B8966/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58958"
,(lldb)     command script import "/tmp/05E4A5D1-0EEB-47FC-B880-0169B25CCC6C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 16:22:54.543 ThaliTest[4488:10296815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/55126903-A97A-4598-9B75-436F767D66D9/Library/Cookies/Cookies.binarycookies
,2016-10-19 16:22:54.659 ThaliTest[4488:10296815] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 16:22:54.661 ThaliTest[4488:10296815] Multi-tasking -> Device: YES, App: YES
,2016-10-19 16:22:54.682 ThaliTest[4488:10296815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 16:22:56.168 ThaliTest[4488:10296815] Using UIWebView
,2016-10-19 16:22:56.177 ThaliTest[4488:10296815] [CDVTimer][handleopenurl] 0.433981ms
,2016-10-19 16:22:56.187 ThaliTest[4488:10296815] [CDVTimer][intentandnavigationfilter] 9.382010ms
2016-10-19 16:22:56.188 ThaliTest[4488:10296815] [CDVTimer][gesturehandler] 0.380039ms
2016-10-19 16:22:56.188 ThaliTest[4488:10296815] [CDVTimer][TotalPlug,inStartup] 12.242019ms
,2016-10-19 16:23:01.878 ThaliTest[4488:10296815] Resetting plugins due to page load.
,2016-10-19 16:23:05.182 ThaliTest[4488:10296815] Finished load of: file:///var/mobile/Containers/Bundle/Application/50E4979A-1937-4BA4-9640-9C53003B8966/ThaliTest.app/www/index.html
,2016-10-19 16:23:05.477 ThaliTest[4488:10296815] JXcore Cordova plugin initializing
,2016-10-19 16:23:05.478 ThaliTest[4488:10297034] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 14:23:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 14:23:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 14:23:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 14:23:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 14:23:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-19 14:23:42 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.46383100748062
,Failed to execute UT.
,2016-10-19 14:23:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
