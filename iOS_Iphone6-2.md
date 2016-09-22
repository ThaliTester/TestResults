#### Test 8617437951c5913_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4990D36D-6EED-4D24-8254-7F24D7FF5EC2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4990D36D-6EED-4D24-8254-7F24D7FF5EC2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5823B009-7D05-4A01-9845-88CB74331C6E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60357"
,(lldb)     command script import "/tmp/4990D36D-6EED-4D24-8254-7F24D7FF5EC2/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-22 07:52:37.921 ThaliTest[1369:1680994] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF62B1FF-B262-4807-841F-CE01266E6A08/Library/Cookies/Cookies.binarycookies
2016-09-22 07:52:,37.956 ThaliTest[1369:1680994] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 07:52:37.957 ThaliTest[1369:1680994] Multi-tasking -> Device: YES, App: YES
,2016-09-22 07:52:37.970 ThaliTest[1369:1680994] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 07:52:38.324 ThaliTest[1369:1680994] Using UIWebView
,2016-09-22 07:52:38.328 ThaliTest[1369:1680994] [CDVTimer][handleopenurl] 0.307977ms
,2016-09-22 07:52:38.333 ThaliTest[1369:1680994] [CDVTimer][intentandnavigationfilter] 4.647017ms
2016-09-22 07:52:38.334 ThaliTest[1369:1680994] [CDVTimer][gesturehandler] 0.207007ms
2016-09-22 07:52:38.334 ThaliTest[1369:1680994] [CDVTimer][TotalPluginS,tartup] 6.236017ms
,2016-09-22 07:52:43.934 ThaliTest[1369:1680994] Resetting plugins due to page load.
,2016-09-22 07:52:44.349 ThaliTest[1369:1680994] Finished load of: file:///var/containers/Bundle/Application/5823B009-7D05-4A01-9845-88CB74331C6E/ThaliTest.app/www/index.html
,2016-09-22 07:52:44.679 ThaliTest[1369:1680994] JXcore Cordova plugin initializing
,2016-09-22 07:52:44.680 ThaliTest[1369:1681164] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1596cf460>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("9AF082CF-3B20-44F8-853B-6ADC958B791B")
nil
,nil
,Optional("42C86DF0-DE24-4907-A3E5-C5CBBBC7D4BE")
,Optional("C2103239-3575-47BE-AF2A-8734B7FD6509")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 07:53:05.579 ThaliTest[1369:1680994] BTM: attaching to BTServer
,2016-09-22 07:53:06.346 ThaliTest[1369:1680994] BTM: local device power state changed
2016-09-22 07:53:06.364 ThaliTest[1369:1680994] BTM: power is now on
,2016-09-22 07:53:11.050 ThaliTest[1369:1680994] BTM: local device power state changed
2016-09-22 07:53:11.050 ThaliTest[1369:1680994] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  19.1343480348587
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
