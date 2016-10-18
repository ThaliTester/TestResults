#### Test 884969631c94703_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BEF9526C-D1D8-4C18-8D69-E360DC87452E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BEF9526C-D1D8-4C18-8D69-E360DC87452E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0E387B0A-BDC4-49E3-95E3-C3CE62B2CA32/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51803"
,(lldb)     command script import "/tmp/BEF9526C-D1D8-4C18-8D69-E360DC87452E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 20:56:06.482 ThaliTest[2438:5114952] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F14C54E3-5E97-4090-8A1C-3404CB8E33DD/Library/Cookies/Cookies.binarycookies
,2016-10-18 20:56:06.523 ThaliTest[2438:5114952] Apache Cordova native platform version 4.2.1 is starting.
2016-10-18 20:56:06.524 ThaliTest[2438:5114952] Multi-tasking -> Device: YES, App: YES
,2016-10-18 20:56:06.536 ThaliTest[2438:5114952] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 20:56:06.821 ThaliTest[2438:5114952] Using UIWebView
,2016-10-18 20:56:06.824 ThaliTest[2438:5114952] [CDVTimer][handleopenurl] 0.164032ms
,2016-10-18 20:56:06.829 ThaliTest[2438:5114952] [CDVTimer][intentandnavigationfilter] 4.328966ms
2016-10-18 20:56:06.829 ThaliTest[2438:5114952] [CDVTimer][gesturehandler] 0.169992ms
2016-10-18 20:56:06.829 ThaliTest[2438:5114952] [CDVTimer][TotalPluginS,tartup] 5.496979ms
,2016-10-18 20:56:12.313 ThaliTest[2438:5114952] Resetting plugins due to page load.
,2016-10-18 20:56:12.718 ThaliTest[2438:5114952] Finished load of: file:///var/containers/Bundle/Application/0E387B0A-BDC4-49E3-95E3-C3CE62B2CA32/ThaliTest.app/www/index.html
,2016-10-18 20:56:13.049 ThaliTest[2438:5114952] JXcore Cordova plugin initializing
,2016-10-18 20:56:13.050 ThaliTest[2438:5115121] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 18:56:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 18:56:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 18:56:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 18:56:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 18:56:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 18:56:46 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  22.11378198862076
,Failed to execute UT.
,2016-10-18 18:56:46 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
