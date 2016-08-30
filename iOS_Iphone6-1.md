#### Test 83268893a5a5a53_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/089701E2-D50C-4A27-9D30-BB8BCB3AE1A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/089701E2-D50C-4A27-9D30-BB8BCB3AE1A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/27D7CA91-8F2E-4869-B010-25B09473AD96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49565"
,(lldb)     command script import "/tmp/089701E2-D50C-4A27-9D30-BB8BCB3AE1A0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:43:31.497 ThaliTest[839:1147459] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7CA6776B-1CD7-4975-AAEF-475B7BD3DE22/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:43:31.949 ThaliTest[839:1147459] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:43:31.951 ThaliTest[839:1147459] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:43:31.973 ThaliTest[839:1147459] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:43:33.789 ThaliTest[839:1147459] Using UIWebView
,2016-08-30 15:43:33.800 ThaliTest[839:1147459] [CDVTimer][handleopenurl] 0.563979ms
,2016-08-30 15:43:33.808 ThaliTest[839:1147459] [CDVTimer][intentandnavigationfilter] 7.205009ms
2016-08-30 15:43:33.809 ThaliTest[839:1147459] [CDVTimer][gesturehandler] 0.362992ms
2016-08-30 15:43:33.809 ThaliTest[839:1147459] [CDVTimer][TotalPluginStartup] 10.011971ms
,2016-08-30 15:43:39.526 ThaliTest[839:1147459] Resetting plugins due to page load.
,2016-08-30 15:43:42.474 ThaliTest[839:1147459] Finished load of: file:///var/mobile/Containers/Bundle/Application/27D7CA91-8F2E-4869-B010-25B09473AD96/ThaliTest.app/www/index.html
,2016-08-30 15:43:42.715 ThaliTest[839:1147459] JXcore Cordova plugin initializing
2016-08-30 15:43:42.716 ThaliTest[839:1147709] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,* thread #1: tid = 0x118243, 0x0008f870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x0008f870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884
    frame #1: 0x0008c4e8 ThaliTest`ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 20
    frame #2: 0x00093b30 ThaliTest`ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 312
    frame #3: 0x00093d4c ThaliTest`@objc ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 24
    frame #4: 0x25459234 CoreFoundation`<redacted> + 68
    frame #5: 0x253837cc CoreFoundation`<redacted> + 292
    frame #6: 0x0087c640 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 452
    frame #7: 0x008ad700 XCTest`-[XCTestContext performInScope:] + 308
    frame #8: 0x0087c476 XCTest`-[XCTestCase invokeTest] + 180
    frame #9: 0x0087cbcc XCTest`-[XCTestCase performTest:] + 564
    frame #10: 0x0087a50c XCTest`-[XCTestSuite performTest:] + 460
    frame #11: 0x0087a50c XCTest`-[XCTestSuite performTest:] + 460
    frame #12: 0x0087a50c XCTest`-[XCTestSuite performTest:] + 460
    frame #13: 0x2622b5a6 Foundation`<redacted> + 386
    frame #14: 0x254177c6 CoreFoundation`<redacted> + 14
    frame #15: 0x254173b6 CoreFoundation`<redacted> + 454
    frame #16: 0x2541571e CoreFoundation`<redacted> + 806
    frame #17: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #18: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #19: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #20: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #21: 0x000823d2 ThaliTest`main + 50
    frame #22: 0x375d0872 libdyld.dylib`<redacted> + 2

```
