#### Test 83268893a5a5a53_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3BAE8DFC-B802-45C9-9AA3-C9AB9C3B921A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3BAE8DFC-B802-45C9-9AA3-C9AB9C3B921A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F766757F-1464-45B2-BC5C-1F978F6D65A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49568"
,(lldb)     command script import "/tmp/3BAE8DFC-B802-45C9-9AA3-C9AB9C3B921A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:43:32.764 ThaliTest[1258:2558170] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4BC6380A-12C0-4A4E-A315-23C1AF40D010/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:43:33.193 ThaliTest[1258:2558170] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:43:33.196 ThaliTest[1258:2558170] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:43:33.221 ThaliTest[1258:2558170] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:43:34.912 ThaliTest[1258:2558170] Using UIWebView
,2016-08-30 15:43:34.920 ThaliTest[1258:2558170] [CDVTimer][handleopenurl] 0.856996ms
,2016-08-30 15:43:34.930 ThaliTest[1258:2558170] [CDVTimer][intentandnavigationfilter] 8.105040ms
2016-08-30 15:43:34.930 ThaliTest[1258:2558170] [CDVTimer][gesturehandler] 0.407994ms
2016-08-30 15:43:34.931 ThaliTest[1258:2558170] [CDVTimer][TotalPluginS,tartup] 11.684000ms
,2016-08-30 15:43:40.582 ThaliTest[1258:2558170] Resetting plugins due to page load.
,2016-08-30 15:43:43.451 ThaliTest[1258:2558170] Finished load of: file:///var/mobile/Containers/Bundle/Application/F766757F-1464-45B2-BC5C-1F978F6D65A8/ThaliTest.app/www/index.html
,2016-08-30 15:43:43.696 ThaliTest[1258:2558170] JXcore Cordova plugin initializing
,2016-08-30 15:43:43.697 ThaliTest[1258:2558393] JXcore instance initializing
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
,Process 1258 stopped
* thread #1: tid = 0x2708da, 0x000d7870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x000d7870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884
ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> ():
->  0xd7870 <+884>: trap   

ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.disconnect (Swift.Array<Swift.AnyObject>) throws -> ():
    0xd7874 <+0>:   push   {r4, r5, r6, r7, lr}
    0xd7878 <+4>:   add    r7, sp, #12
    0xd787c <+8>:   str    r8, [sp, #-0x4]!
,* thread #1: tid = 0x2708da, 0x000d7870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x000d7870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884
    frame #1: 0x000d44e8 ThaliTest`ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 20
    frame #2: 0x000dbb30 ThaliTest`ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 312
    frame #3: 0x000dbd4c ThaliTest`@objc ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 24
    frame #4: 0x252c1234 CoreFoundation`<redacted> + 68
    frame #5: 0x251eb7cc CoreFoundation`<redacted> + 292
    frame #6: 0x008c4640 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 452
    frame #7: 0x008f5700 XCTest`-[XCTestContext performInScope:] + 308
    frame #8: 0x008c4476 XCTest`-[XCTestCase invokeTest] + 180
    frame #9: 0x008c4bcc XCTest`-[XCTestCase performTest:] + 564
    frame #10: 0x008c250c XCTest`-[XCTestSuite performTest:] + 460
    frame #11: 0x008c250c XCTest`-[XCTestSuite performTest:] + 460
    frame #12: 0x008c250c XCTest`-[XCTestSuite performTest:] + 460
    frame #13: 0x260935a6 Foundation`<redacted> + 386
    frame #14: 0x2527f7c6 CoreFoundation`<redacted> + 14
    frame #15: 0x2527f3b6 CoreFoundation`<redacted> + 454
    frame #16: 0x2527d71e CoreFoundation`<redacted> + 806
    frame #17: 0x251d00d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #18: 0x251cfecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #19: 0x2e505af8 GraphicsServices`GSEventRunModal + 160
    frame #20: 0x294592dc UIKit`UIApplicationMain + 144
    frame #21: 0x000ca3d2 ThaliTest`main + 50
    frame #22: 0x37368872 libdyld.dylib`<redacted> + 2

```
