#### Test 86174379d95f7ab_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/187ACA73-8871-402C-AEC9-9F3B3FDE028D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/187ACA73-8871-402C-AEC9-9F3B3FDE028D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/82C0D3C4-B75E-4C3C-9CF6-2D145048BD2B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61834"
,(lldb)     command script import "/tmp/187ACA73-8871-402C-AEC9-9F3B3FDE028D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 17:08:36.534 ThaliTest[2962:6004775] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7730BF47-971C-46D2-9A8D-A2C83A6CA765/Library/Cookies/Cookies.binarycookies
,2016-09-22 17:08:36.655 ThaliTest[2962:6004775] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 17:08:36.657 ThaliTest[2962:6004775] Multi-tasking -> Device: YES, App: YES
,2016-09-22 17:08:36.683 ThaliTest[2962:6004775] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 17:08:38.271 ThaliTest[2962:6004775] Using UIWebView
,2016-09-22 17:08:38.280 ThaliTest[2962:6004775] [CDVTimer][handleopenurl] 0.414014ms
,2016-09-22 17:08:38.289 ThaliTest[2962:6004775] [CDVTimer][intentandnavigationfilter] 8.581996ms
2016-09-22 17:08:38.290 ThaliTest[2962:6004775] [CDVTimer][gesturehandler] 0.384986ms
2016-09-22 17:08:38.290 ThaliTest[2962:6004775] [CDVTimer][TotalPluginStartup] 11.305034ms
,2016-09-22 17:08:44.205 ThaliTest[2962:6004775] Resetting plugins due to page load.
,2016-09-22 17:08:47.779 ThaliTest[2962:6004775] Finished load of: file:///var/mobile/Containers/Bundle/Application/82C0D3C4-B75E-4C3C-9CF6-2D145048BD2B/ThaliTest.app/www/index.html
,2016-09-22 17:08:48.098 ThaliTest[2962:6004775] JXcore Cordova plugin initializing
,2016-09-22 17:08:48.100 ThaliTest[2962:6005023] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15840d730>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("ED57D5BB-E7FF-4C1F-866A-C88BB36FC90D")
,nil
,nil
,Optional("DE20A087-0623-47CD-993E-3D445008D482")
,Optional("8853D1E1-DA9A-4079-97D9-FE7FE6FE568F")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 17:09:12.436 ThaliTest[2962:6004775] BTM: attaching to BTServer
,2016-09-22 17:09:13.147 ThaliTest[2962:6004775] BTM: local device power state changed
,2016-09-22 17:09:13.167 ThaliTest[2962:6004775] BTM: power is now on
,2016-09-22 17:09:17.863 ThaliTest[2962:6004775] BTM: local device power state changed
2016-09-22 17:09:17.869 ThaliTest[2962:6004775] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  53
Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  20.97503697872162
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
