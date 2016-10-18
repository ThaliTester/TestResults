#### Test 89808901ab206e8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/60B72467-1512-4252-BC4D-94E5C93C5BC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/60B72467-1512-4252-BC4D-94E5C93C5BC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89808901ab206e8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3F29406A-3641-4476-B544-FD398EF44245/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61225"
,(lldb)     command script import "/tmp/60B72467-1512-4252-BC4D-94E5C93C5BC4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 15:14:43.997 ThaliTest[4412:10123936] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8C5F6C92-CDE8-4526-BFBA-C3A21F9DD5F0/Library/Cookies/Cookies.binarycookies
,2016-10-18 15:14:44.110 ThaliTest[4412:10123936] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 15:14:44.111 ThaliTest[4412:10123936] Multi-tasking -> Device: YES, App: YES
,2016-10-18 15:14:44.138 ThaliTest[4412:10123936] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 15:14:45.729 ThaliTest[4412:10123936] Using UIWebView
,2016-10-18 15:14:45.739 ThaliTest[4412:10123936] [CDVTimer][handleopenurl] 1.845956ms
,2016-10-18 15:14:45.750 ThaliTest[4412:10123936] [CDVTimer][intentandnavigationfilter] 10.306954ms
2016-10-18 15:14:45.751 ThaliTest[4412:10123936] [CDVTimer][gesturehandler] 0.379980ms
2016-10-18 15:14:45.751 ThaliTest[4412:10123936] [CDVTimer][TotalPlu,ginStartup] 14.449000ms
,2016-10-18 15:14:51.504 ThaliTest[4412:10123936] Resetting plugins due to page load.
,2016-10-18 15:14:54.874 ThaliTest[4412:10123936] Finished load of: file:///var/mobile/Containers/Bundle/Application/3F29406A-3641-4476-B544-FD398EF44245/ThaliTest.app/www/index.html
,2016-10-18 15:14:55.177 ThaliTest[4412:10123936] JXcore Cordova plugin initializing
,2016-10-18 15:14:55.178 ThaliTest[4412:10124144] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 13:15:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 13:15:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 13:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 13:15:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 13:15:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-18 13:15:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.11715596914291
,Failed to execute UT.
,2016-10-18 13:15:31 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
