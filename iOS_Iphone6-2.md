#### Test 86174379d95f7ab_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2144F62A-C5C5-446E-AF59-C89B9FA4D2A6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/2144F62A-C5C5-446E-AF59-C89B9FA4D2A6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3367255D-52FE-4854-9222-BD5062E3B9B9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61828"
,(lldb)     command script import "/tmp/2144F62A-C5C5-446E-AF59-C89B9FA4D2A6/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 08:08:38.170 ThaliTest[1376:1683075] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B43D708C-8BD9-4896-946A-0C94424E1FD5/Library/Cookies/Cookies.binarycookies
,2016-09-22 08:08:38.230 ThaliTest[1376:1683075] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 08:08:38.231 ThaliTest[1376:1683075] Multi-tasking -> Device: YES, App: YES
,2016-09-22 08:08:38.243 ThaliTest[1376:1683075] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 08:08:38.577 ThaliTest[1376:1683075] Using UIWebView
,2016-09-22 08:08:38.582 ThaliTest[1376:1683075] [CDVTimer][handleopenurl] 0.161946ms
,2016-09-22 08:08:38.585 ThaliTest[1376:1683075] [CDVTimer][intentandnavigationfilter] 3.403962ms
2016-09-22 08:08:38.586 ThaliTest[1376:1683075] [CDVTimer][gesturehandler] 0.153005ms
2016-09-22 08:08:38.586 ThaliTest[1376:1683075] [CDVTimer][TotalPluginStartup] 4.568994ms
,2016-09-22 08:08:45.232 ThaliTest[1376:1683075] Resetting plugins due to page load.
,2016-09-22 08:08:45.711 ThaliTest[1376:1683075] Finished load of: file:///var/containers/Bundle/Application/3367255D-52FE-4854-9222-BD5062E3B9B9/ThaliTest.app/www/index.html
,2016-09-22 08:08:46.079 ThaliTest[1376:1683075] JXcore Cordova plugin initializing
,2016-09-22 08:08:46.080 ThaliTest[1376:1683270] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12e6b5fb0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("68BC1473-9E4E-48B6-A402-5F5B4D33F1DB")
,nil
,nil
,Optional("1BF6B3E2-6D19-42C7-81BA-9AAC8B83EE4F")
,Optional("54FBE66D-E291-4744-B3DC-755B77EAAD22")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 08:09:08.493 ThaliTest[1376:1683075] BTM: attaching to BTServer
,2016-09-22 08:09:09.294 ThaliTest[1376:1683075] BTM: local device power state changed
2016-09-22 08:09:09.298 ThaliTest[1376:1683075] BTM: power is now on
,2016-09-22 08:09:13.981 ThaliTest[1376:1683075] BTM: local device power state changed
,2016-09-22 08:09:13.989 ThaliTest[1376:1683075] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  20.73275297880173
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
