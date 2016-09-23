#### Test 861743796628be0_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68954918-F032-4FC3-8D96-567DE149525D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
Executing commands in '/tmp/68954918-F032-4FC3-8D96-567DE149525D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BD56EA18-68CB-4786-B844-81A9CC9F8C0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58175"
,(lldb)     command script import "/tmp/68954918-F032-4FC3-8D96-567DE149525D/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 03:39:30.597 ThaliTest[1464:1778162] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/521E0AD3-68E1-4800-B523-EF022FF3856E/Library/Cookies/Cookies.binarycookies
,2016-09-23 03:39:30.677 ThaliTest[1464:1778162] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 03:39:30.679 ThaliTest[1464:1778162] Multi-tasking -> Device: YES, App: YES
,2016-09-23 03:39:30.697 ThaliTest[1464:1778162] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 03:39:31.132 ThaliTest[1464:1778162] Using UIWebView
,2016-09-23 03:39:31.139 ThaliTest[1464:1778162] [CDVTimer][handleopenurl] 0.342011ms
,2016-09-23 03:39:31.146 ThaliTest[1464:1778162] [CDVTimer][intentandnavigationfilter] 6.968975ms
2016-09-23 03:39:31.147 ThaliTest[1464:1778162] [CDVTimer][gesturehandler] 0.329018ms
2016-09-23 03:39:31.147 ThaliTest[1464:1778162] [CDVTimer][TotalPluginStartup] 9.285033ms
,2016-09-23 03:39:36.703 ThaliTest[1464:1778162] Resetting plugins due to page load.
,2016-09-23 03:39:37.135 ThaliTest[1464:1778162] Finished load of: file:///var/containers/Bundle/Application/BD56EA18-68CB-4786-B844-81A9CC9F8C0B/ThaliTest.app/www/index.html
,2016-09-23 03:39:37.466 ThaliTest[1464:1778162] JXcore Cordova plugin initializing
,2016-09-23 03:39:37.467 ThaliTest[1464:1778349] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1284830d0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("9310C5F1-5738-48FD-8BC8-C1282AEA2D1F")
nil
,nil
,Optional("D208F221-8D17-4C7C-9676-6F5B4D0258FE")
,Optional("A611CCB1-DEE2-45BB-ACBC-03CE1A202393")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 03:40:00.061 ThaliTest[1464:1778162] BTM: attaching to BTServer
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn on Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned on". - <unknown> - 0
,XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetooth state.Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 265
,XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetoothLowEnergyState state. Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 273
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn off Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
Asynchronous wait failed,: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned off". - <unknown> - 0
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  47
,Number of failed tests:  9
,Number of ignored tests:  0
,Total duration:  35.7800840139389
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
