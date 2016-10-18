#### Test 884969631c94703_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DE454EAA-E70F-4931-BFBC-C227176A3260/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/DE454EAA-E70F-4931-BFBC-C227176A3260/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969631c94703/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0E1C99B3-EEC6-4518-AAAC-DA98E1D8B61E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51809"
,(lldb)     command script import "/tmp/DE454EAA-E70F-4931-BFBC-C227176A3260/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 11:56:34.351 ThaliTest[2549:4609396] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D3C00F78-584B-4A47-B1D4-89F2E35CB029/Library/Cookies/Cookies.binarycookies
,2016-10-18 11:56:34.429 ThaliTest[2549:4609396] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 11:56:34.431 ThaliTest[2549:4609396] Multi-tasking -> Device: YES, App: YES
,2016-10-18 11:56:34.452 ThaliTest[2549:4609396] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 11:56:35.051 ThaliTest[2549:4609396] Using UIWebView
2016-10-18 11:56:35.058 ThaliTest[2549:4609396] [CDVTimer][handleopenurl] 0.319004ms
,2016-10-18 11:56:35.067 ThaliTest[2549:4609396] [CDVTimer][intentandnavigationfilter] 9.006023ms
2016-10-18 11:56:35.068 ThaliTest[2549:4609396] [CDVTimer][gesturehandler] 0.309050ms
2016-10-18 11:56:35.069 ThaliTest[2549:4609396] [CDVTimer][TotalPluginStartup] 11.379004ms
,2016-10-18 11:56:41.985 ThaliTest[2549:4609396] Resetting plugins due to page load.
,2016-10-18 11:56:42.657 ThaliTest[2549:4609396] Finished load of: file:///var/containers/Bundle/Application/0E1C99B3-EEC6-4518-AAAC-DA98E1D8B61E/ThaliTest.app/www/index.html
,2016-10-18 11:56:43.062 ThaliTest[2549:4609396] JXcore Cordova plugin initializing
,2016-10-18 11:56:43.063 ThaliTest[2549:4609600] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 18:56:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 18:56:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 18:56:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 18:56:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 18:56:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 18:57:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.61339598894119
,Failed to execute UT.
,2016-10-18 18:57:18 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
