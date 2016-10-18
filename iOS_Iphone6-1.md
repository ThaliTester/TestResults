#### Test 89808901b248d65_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/136DDBA9-2A3D-4164-8CBD-3645A17F62E5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/136DDBA9-2A3D-4164-8CBD-3645A17F62E5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89808901b248d65/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0A80B605-8D24-4682-AE24-108658EE266F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65205"
,(lldb)     command script import "/tmp/136DDBA9-2A3D-4164-8CBD-3645A17F62E5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 16:04:30.102 ThaliTest[2421:5086801] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1E20BE9B-02A3-48A9-8AD0-118F554CCC49/Library/Cookies/Cookies.binarycookies
,2016-10-18 16:04:30.176 ThaliTest[2421:5086801] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 16:04:30.178 ThaliTest[2421:5086801] Multi-tasking -> Device: YES, App: YES
,2016-10-18 16:04:30.197 ThaliTest[2421:5086801] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 16:04:30.691 ThaliTest[2421:5086801] Using UIWebView
,2016-10-18 16:04:30.701 ThaliTest[2421:5086801] [CDVTimer][handleopenurl] 0.430048ms
,2016-10-18 16:04:30.711 ThaliTest[2421:5086801] [CDVTimer][intentandnavigationfilter] 9.322047ms
2016-10-18 16:04:30.712 ThaliTest[2421:5086801] [CDVTimer][gesturehandler] 0.335038ms
2016-10-18 16:04:30.712 ThaliTest[2421:5086801] [CDVTimer][TotalPluginStartup] 11.914015ms
,2016-10-18 16:04:36.100 ThaliTest[2421:5086801] Resetting plugins due to page load.
,2016-10-18 16:04:36.460 ThaliTest[2421:5086801] Finished load of: file:///var/containers/Bundle/Application/0A80B605-8D24-4682-AE24-108658EE266F/ThaliTest.app/www/index.html
,2016-10-18 16:04:36.790 ThaliTest[2421:5086801] JXcore Cordova plugin initializing
,2016-10-18 16:04:36.792 ThaliTest[2421:5086966] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:04:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:04:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:04:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 14:04:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:04:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 14:05:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.66813999414444
Failed to execute UT.
,2016-10-18 14:05:12 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
