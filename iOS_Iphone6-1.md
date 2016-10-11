#### Test 884969632a6a9b7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/58B20878-EBC4-4A90-849F-5D7D3ABFD7CF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/58B20878-EBC4-4A90-849F-5D7D3ABFD7CF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/88741D05-5786-4CFA-AE58-0B4223AB9F62/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55819"
,(lldb)     command script import "/tmp/58B20878-EBC4-4A90-849F-5D7D3ABFD7CF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-11 02:30:48.906 ThaliTest[2068:4100412] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2899FCE5-1D1B-4967-AB56-1290021AA1F9/Library/Cookies/Cookies.binarycookies
,2016-10-11 02:30:48.991 ThaliTest[2068:4100412] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-11 02:30:48.993 ThaliTest[2068:4100412] Multi-tasking -> Device: YES, App: YES
,2016-10-11 02:30:49.010 ThaliTest[2068:4100412] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-11 02:30:49.445 ThaliTest[2068:4100412] Using UIWebView
,2016-10-11 02:30:49.452 ThaliTest[2068:4100412] [CDVTimer][handleopenurl] 0.476003ms
,2016-10-11 02:30:49.460 ThaliTest[2068:4100412] [CDVTimer][intentandnavigationfilter] 8.191943ms
2016-10-11 02:30:49.461 ThaliTest[2068:4100412] [CDVTimer][gesturehandler] 0.283957ms
2016-10-11 02:30:49.461 ThaliTest[2068:4100412] [CDVTimer][TotalPluginStartup] 10.555029ms
,2016-10-11 02:30:54.992 ThaliTest[2068:4100412] Resetting plugins due to page load.
,2016-10-11 02:30:55.367 ThaliTest[2068:4100412] Finished load of: file:///var/containers/Bundle/Application/88741D05-5786-4CFA-AE58-0B4223AB9F62/ThaliTest.app/www/index.html
,2016-10-11 02:30:55.698 ThaliTest[2068:4100412] JXcore Cordova plugin initializing
,2016-10-11 02:30:55.699 ThaliTest[2068:4100581] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-11 00:31:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-11 00:31:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-11 00:31:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-11 00:31:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-11 00:31:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,* thread #1: tid = 0x3e913c, 0x0000000183b1d1a4 CoreFoundation`<redacted> + 52, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000183b1d1a4 CoreFoundation`<redacted> + 52
    frame #1: 0x0000000183b338a0 CoreFoundation`<redacted> + 36
    frame #2: 0x00000001009712d8 XCTest`-[XCTestObservationCenter _testCaseDidStop:] + 320
    frame #3: 0x00000001009607a0 XCTest`-[XCTestCaseRun stop] + 84
    frame #4: 0x0000000100965848 XCTest`-[XCTestCase performTest:] + 680
    frame #5: 0x00000001009631d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #6: 0x00000001009631d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #7: 0x00000001009631d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #8: 0x000000010087bba8 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #9: 0x000000010087bc2c ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #10: 0x000000018461002c Foundation`<redacted> + 340
    frame #11: 0x0000000183bf109c CoreFoundation`<redacted> + 24
    frame #12: 0x0000000183bf0b30 CoreFoundation`<redacted> + 540
    frame #13: 0x0000000183bee830 CoreFoundation`<redacted> + 724
    frame #14: 0x0000000183b18c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #15: 0x0000000185400088 GraphicsServices`GSEventRunModal + 180
    frame #16: 0x0000000188e06088 UIKit`UIApplicationMain + 204
    frame #17: 0x00000001000b7a24 ThaliTest`main + 76
    frame #18: 0x00000001836b68b8 libdyld.dylib`<redacted> + 4

```
