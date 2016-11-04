#### Test 92300911d00ab7e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EFB87805-A045-4F36-98F0-9902DC6AA18B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EFB87805-A045-4F36-98F0-9902DC6AA18B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDAA3306-57D0-4DA9-9BED-594D4E54095F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60784"
,(lldb)     command script import "/tmp/EFB87805-A045-4F36-98F0-9902DC6AA18B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 09:57:22.993 ThaliTest[5139:12819852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8E5B36AE-7C48-40BB-8EA3-EAD22A4D3D6C/Library/Cookies/Cookies.binarycookies
,2016-11-04 09:57:23.112 ThaliTest[5139:12819852] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 09:57:23.114 ThaliTest[5139:12819852] Multi-tasking -> Device: YES, App: YES
,2016-11-04 09:57:23.137 ThaliTest[5139:12819852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 09:57:24.524 ThaliTest[5139:12819852] Using UIWebView
,2016-11-04 09:57:24.532 ThaliTest[5139:12819852] [CDVTimer][handleopenurl] 0.476003ms
,2016-11-04 09:57:24.541 ThaliTest[5139:12819852] [CDVTimer][intentandnavigationfilter] 8.348942ms
2016-11-04 09:57:24.542 ThaliTest[5139:12819852] [CDVTimer][gesturehandler] 0.369012ms
2016-11-04 09:57:24.543 ThaliTest[5139:12819852] [CDVTimer][TotalPlug,inStartup] 11.047006ms
,2016-11-04 09:57:30.193 ThaliTest[5139:12819852] Resetting plugins due to page load.
,2016-11-04 09:57:33.612 ThaliTest[5139:12819852] Finished load of: file:///var/mobile/Containers/Bundle/Application/EDAA3306-57D0-4DA9-9BED-594D4E54095F/ThaliTest.app/www/index.html
,2016-11-04 09:57:33.921 ThaliTest[5139:12819852] JXcore Cordova plugin initializing
,2016-11-04 09:57:33.922 ThaliTest[5139:12820065] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 08:57:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 08:57:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 08:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-04 08:57:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 08:57:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-04 08:58:10 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  102
Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  23.56044501066208
,Failed to execute UT.
,2016-11-04 08:58:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
