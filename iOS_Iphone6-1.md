#### Test 861743796628be0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/041B802B-81FF-42CF-8396-3847D7391724/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/041B802B-81FF-42CF-8396-3847D7391724/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E9515577-F247-4FB1-A984-1388321BC5B7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58153"
,(lldb)     command script import "/tmp/041B802B-81FF-42CF-8396-3847D7391724/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-23 12:39:28.009 ThaliTest[1300:1872431] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/977FB9C3-F7D0-4F03-B03C-0AC543062741/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:39:28.048 ThaliTest[1300:1872431] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:39:28.049 ThaliTest[1300:1872431] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:39:28.060 ThaliTest[1300:1872431] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:39:28.427 ThaliTest[1300:1872431] Using UIWebView
,2016-09-23 12:39:28.433 ThaliTest[1300:1872431] [CDVTimer][handleopenurl] 0.220001ms
,2016-09-23 12:39:28.438 ThaliTest[1300:1872431] [CDVTimer][intentandnavigationfilter] 4.655004ms
2016-09-23 12:39:28.439 ThaliTest[1300:1872431] [CDVTimer][gesturehandler] 0.186980ms
2016-09-23 12:39:28.439 ThaliTest[1300:1872431] [CDVTimer][TotalPluginStartup] 6.166995ms
,2016-09-23 12:39:34.026 ThaliTest[1300:1872431] Resetting plugins due to page load.
,2016-09-23 12:39:34.412 ThaliTest[1300:1872431] Finished load of: file:///var/containers/Bundle/Application/E9515577-F247-4FB1-A984-1388321BC5B7/ThaliTest.app/www/index.html
,2016-09-23 12:39:34.743 ThaliTest[1300:1872431] JXcore Cordova plugin initializing
,2016-09-23 12:39:34.744 ThaliTest[1300:1872607] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1506edf70>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("84AE8AAF-C5B9-4B8B-9EB0-21C7F6F52A4C")
,nil
,nil
,Optional("07F4D3C0-48DF-4DD3-A14A-ED9E1A6C77CA")
,Optional("40B49195-B35B-43FD-865B-AE4BF8CA3EBC")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:39:56.311 ThaliTest[1300:1872431] BTM: attaching to BTServer
,2016-09-23 12:39:57.070 ThaliTest[1300:1872431] BTM: local device power state changed
2016-09-23 12:39:57.071 ThaliTest[1300:1872431] BTM: power is now on
,2016-09-23 12:40:01.783 ThaliTest[1300:1872431] BTM: local device power state changed
2016-09-23 12:40:01.784 ThaliTest[1300:1872431] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  19.74112701416016
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
