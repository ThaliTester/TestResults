#### Test 89808901b248d65_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/86B92555-D4F9-44CA-BA46-695998E41AE1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/86B92555-D4F9-44CA-BA46-695998E41AE1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D09ACE8B-4A04-40FF-B3ED-6577BC1A7B8F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65209"
,(lldb)     command script import "/tmp/86B92555-D4F9-44CA-BA46-695998E41AE1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 07:04:50.217 ThaliTest[2533:4584278] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46EF793C-3A6C-411B-8B58-4C6C32D3DDED/Library/Cookies/Cookies.binarycookies
,2016-10-18 07:04:50.255 ThaliTest[2533:4584278] Apache Cordova native platform version 4.2.1 is starting.
2016-10-18 07:04:50.256 ThaliTest[2533:4584278] Multi-tasking -> Device: YES, App: YES
,2016-10-18 07:04:50.271 ThaliTest[2533:4584278] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 07:04:50.654 ThaliTest[2533:4584278] Using UIWebView
2016-10-18 07:04:50.658 ThaliTest[2533:4584278] [CDVTimer][handleopenurl] 0.229001ms
2016-10-18 07:04:50.664 ThaliTest[2533:4584278] [CDVTimer][intentandnavigationfilter] 5.807996ms
,2016-10-18 07:04:50.666 ThaliTest[2533:4584278] [CDVTimer][gesturehandler] 1.257002ms
2016-10-18 07:04:50.667 ThaliTest[2533:4584278] [CDVTimer][TotalPluginStartup] 9.033978ms
,2016-10-18 07:04:57.486 ThaliTest[2533:4584278] Resetting plugins due to page load.
,2016-10-18 07:04:57.878 ThaliTest[2533:4584278] Finished load of: file:///var/containers/Bundle/Application/D09ACE8B-4A04-40FF-B3ED-6577BC1A7B8F/ThaliTest.app/www/index.html
,2016-10-18 07:04:58.219 ThaliTest[2533:4584278] JXcore Cordova plugin initializing
,2016-10-18 07:04:58.220 ThaliTest[2533:4584469] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:05:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:05:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:05:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 14:05:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:05:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 14:05:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  23.65787601470947
,Failed to execute UT.
,2016-10-18 14:05:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
