#### Test 935721672bafbe2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/31A0B312-C0BA-4DF7-BEF3-596862B9BB14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/31A0B312-C0BA-4DF7-BEF3-596862B9BB14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9B026582-661D-4A70-B12B-45BB0310F28F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58173"
,(lldb)     command script import "/tmp/31A0B312-C0BA-4DF7-BEF3-596862B9BB14/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-21 16:48:23.615 ThaliTest[331:351345] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F0B74F2-13B6-41AE-B0D9-26B9A7CE5197/Library/Cookies/Cookies.binarycookies
,2016-11-21 16:48:23.978 ThaliTest[331:351345] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 16:48:23.980 ThaliTest[331:351345] Multi-tasking -> Device: YES, App: YES
,2016-11-21 16:48:23.997 ThaliTest[331:351345] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 16:48:25.963 ThaliTest[331:351345] Using UIWebView
,2016-11-21 16:48:25.970 ThaliTest[331:351345] [CDVTimer][handleopenurl] 0.411987ms
,2016-11-21 16:48:25.977 ThaliTest[331:351345] [CDVTimer][intentandnavigationfilter] 6.317973ms
,2016-11-21 16:48:25.977 ThaliTest[331:351345] [CDVTimer][gesturehandler] 0.278056ms
,2016-11-21 16:48:25.978 ThaliTest[331:351345] [CDVTimer][TotalPluginStartup] 8.758962ms
,2016-11-21 16:48:32.246 ThaliTest[331:351345] Resetting plugins due to page load.
,2016-11-21 16:48:35.334 ThaliTest[331:351345] Finished load of: file:///var/mobile/Containers/Bundle/Application/9B026582-661D-4A70-B12B-45BB0310F28F/ThaliTest.app/www/index.html
,2016-11-21 16:48:35.551 ThaliTest[331:351345] JXcore Cordova plugin initializing
,2016-11-21 16:48:35.552 ThaliTest[331:351564] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 15:48:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 15:48:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 15:48:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-21 15:48:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 15:48:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0x55c71, 0x0000000100460058 ThaliTest`memcpy + 4, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 2 messages
  * frame #0: 0x0000000100460058 ThaliTest`memcpy + 4
    frame #1: 0x00000001000b4840 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[1] = Dead> of Swift.Character.init (Swift.String) -> Swift.Character + 200
    frame #2: 0x00000001000b05a8 ThaliTest`function signature specialization <Arg[1] = Dead> of static (extension in ThaliTest):Swift.String.random (length : Swift.Int) -> Swift.String + 328
    frame #3: 0x00000001000ad7f0 ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 36
    frame #4: 0x0000000100a3120c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #5: 0x0000000100a636ec XCTest`-[XCTestContext performInScope:] + 208
    frame #6: 0x0000000100a31180 XCTest`-[XCTestCase invokeTest] + 164
    frame #7: 0x0000000100a3176c XCTest`-[XCTestCase performTest:] + 460
    frame #8: 0x0000000100a2f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x0000000100a2f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #10: 0x0000000100a2f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #11: 0x000000010087de44 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #12: 0x000000010087dec8 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #13: 0x0000000185133e60 Foundation`<redacted> + 340
    frame #14: 0x00000001841a8544 CoreFoundation`<redacted> + 24
    frame #15: 0x00000001841a7fd8 CoreFoundation`<redacted> + 540
    frame #16: 0x00000001841a5cd8 CoreFoundation`<redacted> + 724
    frame #17: 0x00000001840d4ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #18: 0x000000018f154088 GraphicsServices`GSEventRunModal + 180
    frame #19: 0x00000001897ecffc UIKit`UIApplicationMain + 204
    frame #20: 0x00000001000973cc ThaliTest`main + 76
    frame #21: 0x00000001996a68b8 libdyld.dylib`<redacted> + 4

```
