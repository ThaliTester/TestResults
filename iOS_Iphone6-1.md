#### Test 868913053534d83_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5382D8DE-6474-47A3-B865-C88A892D7945/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5382D8DE-6474-47A3-B865-C88A892D7945/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0C429C90-A419-4EA2-A561-60091495E6EC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55018"
,(lldb)     command script import "/tmp/5382D8DE-6474-47A3-B865-C88A892D7945/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:45:15.198 ThaliTest[1519:2374422] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6ECFD9DE-6F9A-4E99-9570-A1BC2FC02898/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:45:15.240 ThaliTest[1519:2374422] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:45:15.241 ThaliTest[1519:2374422] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:45:15.253 ThaliTest[1519:2374422] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:45:15.546 ThaliTest[1519:2374422] Using UIWebView
,2016-09-27 12:45:15.550 ThaliTest[1519:2374422] [CDVTimer][handleopenurl] 0.195980ms
,2016-09-27 12:45:15.554 ThaliTest[1519:2374422] [CDVTimer][intentandnavigationfilter] 3.558993ms
2016-09-27 12:45:15.554 ThaliTest[1519:2374422] [CDVTimer][gesturehandler] 0.141025ms
2016-09-27 12:45:15.554 ThaliTest[1519:2374422] [CDVTimer][TotalPluginStartup] 4.738986ms
,2016-09-27 12:45:20.996 ThaliTest[1519:2374422] Resetting plugins due to page load.
,2016-09-27 12:45:21.385 ThaliTest[1519:2374422] Finished load of: file:///var/containers/Bundle/Application/0C429C90-A419-4EA2-A561-60091495E6EC/ThaliTest.app/www/index.html
,2016-09-27 12:45:21.718 ThaliTest[1519:2374422] JXcore Cordova plugin initializing
,2016-09-27 12:45:21.718 ThaliTest[1519:2374590] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x14647edb0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found advertiser's peer". in file: Optional("<unknown>"), line: 0
,failed - peer identifier should be not nil in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 45
XCTAssertEqual failed: ("Optional(0),") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 237
XCTAssertEqual failed: ("Optional(0)") i,s not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 239
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found 2 advertisers". in file: Optional("<unknown>"), line: 0
XCTAssertEqual failed: ("nil") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github,/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 218
,Optional("1A4A0C9B-7C5E-460F-B7B7-6CB6D1C3DEE0")
nil
,nil
,Optional("8E620E51-3D60-42D0-8CC4-04D1942D0C0F")
,Optional("72821C67-47D0-466C-AC72-79AE4E339505")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  50
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  15.40867298841476
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
