#### Test 884969631c94703_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/664233C9-C345-48F8-93BC-8A598DBE28DF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/664233C9-C345-48F8-93BC-8A598DBE28DF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25DDC104-A4FF-4180-AAAB-6ED3F14E231B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51807"
,(lldb)     command script import "/tmp/664233C9-C345-48F8-93BC-8A598DBE28DF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 20:56:19.362 ThaliTest[4447:10166652] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EB5408E6-2366-47F5-A030-EC3D1F56B7E6/Library/Cookies/Cookies.binarycookies
,2016-10-18 20:56:19.479 ThaliTest[4447:10166652] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 20:56:19.481 ThaliTest[4447:10166652] Multi-tasking -> Device: YES, App: YES
,2016-10-18 20:56:19.499 ThaliTest[4447:10166652] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 20:56:21.332 ThaliTest[4447:10166652] Using UIWebView
,2016-10-18 20:56:21.343 ThaliTest[4447:10166652] [CDVTimer][handleopenurl] 0.436008ms
,2016-10-18 20:56:21.354 ThaliTest[4447:10166652] [CDVTimer][intentandnavigationfilter] 10.434985ms
2016-10-18 20:56:21.355 ThaliTest[4447:10166652] [CDVTimer][gesturehandler] 0.384033ms
2016-10-18 20:56:21.355 ThaliTest[4447:10166652] [CDVTimer][TotalPlu,ginStartup] 13.218045ms
,2016-10-18 20:56:27.672 ThaliTest[4447:10166652] Resetting plugins due to page load.
,2016-10-18 20:56:31.274 ThaliTest[4447:10166652] Finished load of: file:///var/mobile/Containers/Bundle/Application/25DDC104-A4FF-4180-AAAB-6ED3F14E231B/ThaliTest.app/www/index.html
,2016-10-18 20:56:31.569 ThaliTest[4447:10166652] JXcore Cordova plugin initializing
2016-10-18 20:56:31.570 ThaliTest[4447:10166902] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 18:56:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 18:56:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 18:56:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 18:56:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 18:56:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-18 18:57:09 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  24.30885696411133
,Failed to execute UT.
,2016-10-18 18:57:09 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
