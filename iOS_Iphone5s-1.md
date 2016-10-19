#### Test 88496963ea5ebba_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/03250FDD-0FEF-4ABB-B741-BE2B60857E3F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/03250FDD-0FEF-4ABB-B741-BE2B60857E3F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963ea5ebba/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5A7471A-B6EB-4BE9-AAD0-4E3F47F47107/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49343"
,(lldb)     command script import "/tmp/03250FDD-0FEF-4ABB-B741-BE2B60857E3F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 22:40:50.670 ThaliTest[4513:10341953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CFFD6CC6-0B5A-4D6F-BB9B-D55F1CA8ED2E/Library/Cookies/Cookies.binarycookies
,2016-10-19 22:40:50.791 ThaliTest[4513:10341953] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 22:40:50.794 ThaliTest[4513:10341953] Multi-tasking -> Device: YES, App: YES
,2016-10-19 22:40:50.814 ThaliTest[4513:10341953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 22:40:52.436 ThaliTest[4513:10341953] Using UIWebView
,2016-10-19 22:40:52.444 ThaliTest[4513:10341953] [CDVTimer][handleopenurl] 0.451028ms
,2016-10-19 22:40:52.455 ThaliTest[4513:10341953] [CDVTimer][intentandnavigationfilter] 9.921014ms
2016-10-19 22:40:52.456 ThaliTest[4513:10341953] [CDVTimer][gesturehandler] 0.375986ms
2016-10-19 22:40:52.456 ThaliTest[4513:10341953] [CDVTimer][TotalPlug,inStartup] 12.638986ms
,2016-10-19 22:40:58.299 ThaliTest[4513:10341953] Resetting plugins due to page load.
,2016-10-19 22:41:02.003 ThaliTest[4513:10341953] Finished load of: file:///var/mobile/Containers/Bundle/Application/F5A7471A-B6EB-4BE9-AAD0-4E3F47F47107/ThaliTest.app/www/index.html
,2016-10-19 22:41:02.196 ThaliTest[4513:10341953] JXcore Cordova plugin initializing
,2016-10-19 22:41:02.197 ThaliTest[4513:10342175] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 20:41:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 20:41:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 20:41:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-19 20:41:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 20:41:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-19 20:41:40 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
Total duration:  25.11973601579666
,Failed to execute UT.
,2016-10-19 20:41:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
