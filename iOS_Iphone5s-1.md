#### Test 90793797671d7b3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BD31DE00-A27B-4782-B884-8F9AE8744344/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BD31DE00-A27B-4782-B884-8F9AE8744344/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90793797671d7b3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/18170C11-A25D-4FC5-B357-E065C2D1F08F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64237"
,(lldb)     command script import "/tmp/BD31DE00-A27B-4782-B884-8F9AE8744344/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-25 14:25:33.073 ThaliTest[4744:11242920] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B39C000-56F4-4170-BA93-063472590E6F/Library/Cookies/Cookies.binarycookies
,2016-10-25 14:25:33.209 ThaliTest[4744:11242920] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-25 14:25:33.210 ThaliTest[4744:11242920] Multi-tasking -> Device: YES, App: YES
,2016-10-25 14:25:33.233 ThaliTest[4744:11242920] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-25 14:25:34.750 ThaliTest[4744:11242920] Using UIWebView
,2016-10-25 14:25:34.759 ThaliTest[4744:11242920] [CDVTimer][handleopenurl] 0.506043ms
,2016-10-25 14:25:34.768 ThaliTest[4744:11242920] [CDVTimer][intentandnavigationfilter] 8.237004ms
2016-10-25 14:25:34.768 ThaliTest[4744:11242920] [CDVTimer][gesturehandler] 0.382006ms
2016-10-25 14:25:34.769 ThaliTest[4744:11242920] [CDVTimer][TotalPlug,inStartup] 11.041999ms
,2016-10-25 14:25:40.382 ThaliTest[4744:11242920] Resetting plugins due to page load.
,2016-10-25 14:25:43.743 ThaliTest[4744:11242920] Finished load of: file:///var/mobile/Containers/Bundle/Application/18170C11-A25D-4FC5-B357-E065C2D1F08F/ThaliTest.app/www/index.html
,2016-10-25 14:25:44.059 ThaliTest[4744:11242920] JXcore Cordova plugin initializing
,2016-10-25 14:25:44.060 ThaliTest[4744:11243145] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-25 12:25:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-25 12:25:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-25 12:25:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-25 12:25:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-25 12:25:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
,Optional(false)
,Optional(false)
,Optional(true)
,2016-10-25 12:26:21 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.77161395549774
,Failed to execute UT.
,2016-10-25 12:26:21 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
