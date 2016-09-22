#### Test 86174379d95f7ab_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/740E8487-0429-4508-9FA1-F3A2F8802DCC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/740E8487-0429-4508-9FA1-F3A2F8802DCC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B469D4A6-2BE1-45E2-978F-482171243677/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61830"
,(lldb)     command script import "/tmp/740E8487-0429-4508-9FA1-F3A2F8802DCC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 17:08:34.468 ThaliTest[1216:1763964] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F3060B8-CF33-4E57-A554-A892003AF931/Library/Cookies/Cookies.binarycookies
,2016-09-22 17:08:34.555 ThaliTest[1216:1763964] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 17:08:34.557 ThaliTest[1216:1763964] Multi-tasking -> Device: YES, App: YES
,2016-09-22 17:08:34.574 ThaliTest[1216:1763964] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 17:08:35.030 ThaliTest[1216:1763964] Using UIWebView
,2016-09-22 17:08:35.039 ThaliTest[1216:1763964] [CDVTimer][handleopenurl] 0.344992ms
,2016-09-22 17:08:35.047 ThaliTest[1216:1763964] [CDVTimer][intentandnavigationfilter] 7.115006ms
2016-09-22 17:08:35.048 ThaliTest[1216:1763964] [CDVTimer][gesturehandler] 0.290990ms
2016-09-22 17:08:35.048 ThaliTest[1216:1763964] [CDVTimer][TotalPluginStartup] 9.549022ms
,2016-09-22 17:08:40.619 ThaliTest[1216:1763964] Resetting plugins due to page load.
,2016-09-22 17:08:41.064 ThaliTest[1216:1763964] Finished load of: file:///var/containers/Bundle/Application/B469D4A6-2BE1-45E2-978F-482171243677/ThaliTest.app/www/index.html
,2016-09-22 17:08:41.439 ThaliTest[1216:1763964] JXcore Cordova plugin initializing
,2016-09-22 17:08:41.440 ThaliTest[1216:1764141] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x145a4b2f0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("091D1C00-578E-4BDC-8B0D-4B1244249517")
nil
,nil
,Optional("D2F542CD-86BA-4807-B10C-F37C0C458BC3")
,Optional("B4326EC8-2FD6-4F0D-828A-3664BAA8DEFB")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 17:09:03.350 ThaliTest[1216:1763964] BTM: attaching to BTServer
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn on Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned on". - <unknown> - 0
,XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetooth state.Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 265
,XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetoothLowEnergyState state. Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 273
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn off Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
Asynchronous wait failed,: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned off". - <unknown> - 0
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  47
Number of failed tests:  9
Number of ignored tests:  0
,Total duration:  34.59215998649597
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't 
```
