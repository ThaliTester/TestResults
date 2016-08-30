#### Test 83268893a5a5a53_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C6350845-0F04-405C-97F2-CC50FA8771C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C6350845-0F04-405C-97F2-CC50FA8771C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893a5a5a53/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/70AF70AF-1E19-4485-B31F-FFB649AD4E83/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49564"
,(lldb)     command script import "/tmp/C6350845-0F04-405C-97F2-CC50FA8771C0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-30 15:43:35.510 ThaliTest[1364:2507814] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68562332-808A-4D5A-A104-A507C0A9AA21/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:43:35.901 ThaliTest[1364:2507814] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:43:35.903 ThaliTest[1364:2507814] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:43:35.923 ThaliTest[1364:2507814] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:43:37.841 ThaliTest[1364:2507814] Using UIWebView
,2016-08-30 15:43:37.850 ThaliTest[1364:2507814] [CDVTimer][handleopenurl] 0.380993ms
,2016-08-30 15:43:37.857 ThaliTest[1364:2507814] [CDVTimer][intentandnavigationfilter] 6.635964ms
,2016-08-30 15:43:37.858 ThaliTest[1364:2507814] [CDVTimer][gesturehandler] 0.312984ms
,2016-08-30 15:43:37.859 ThaliTest[1364:2507814] [CDVTimer][TotalPluginStartup] 9.110987ms
,2016-08-30 15:43:44.029 ThaliTest[1364:2507814] Resetting plugins due to page load.
,2016-08-30 15:43:47.423 ThaliTest[1364:2507814] Finished load of: file:///var/mobile/Containers/Bundle/Application/70AF70AF-1E19-4485-B31F-FFB649AD4E83/ThaliTest.app/www/index.html
,2016-08-30 15:43:47.699 ThaliTest[1364:2507814] JXcore Cordova plugin initializing
,2016-08-30 15:43:47.700 ThaliTest[1364:2508053] JXcore instance initializing
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
,* thread #1: tid = 0x264426, 0x000ff870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x000ff870 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 884
    frame #1: 0x000fc4e8 ThaliTest`ThaliTest.AppContext.multiConnectToPeer (Swift.Array<Swift.AnyObject>) throws -> () + 20
    frame #2: 0x00103b30 ThaliTest`ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 312
    frame #3: 0x00103d4c ThaliTest`@objc ThaliTest.AppContextTests.testMultiConnectErrors () -> () + 24
    frame #4: 0x2214e234 CoreFoundation`<redacted> + 68
    frame #5: 0x220787cc CoreFoundation`<redacted> + 292
    frame #6: 0x008ec640 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 452
    frame #7: 0x0091d700 XCTest`-[XCTestContext performInScope:] + 308
    frame #8: 0x008ec476 XCTest`-[XCTestCase invokeTest] + 180
    frame #9: 0x008ecbcc XCTest`-[XCTestCase performTest:] + 564
    frame #10: 0x008ea50c XCTest`-[XCTestSuite performTest:] + 460
    frame #11: 0x008ea50c XCTest`-[XCTestSuite performTest:] + 460
    frame #12: 0x008ea50c XCTest`-[XCTestSuite performTest:] + 460
    frame #13: 0x22f205a6 Foundation`<redacted> + 386
    frame #14: 0x2210c7c6 CoreFoundation`<redacted> + 14
    frame #15: 0x2210c3b6 CoreFoundation`<redacted> + 454
    frame #16: 0x2210a71e CoreFoundation`<redacted> + 806
    frame #17: 0x2205d0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #18: 0x2205cecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #19: 0x2b204af8 GraphicsServices`GSEventRunModal + 160
    frame #20: 0x262e62dc UIKit`UIApplicationMain + 144
    frame #21: 0x000f23d2 ThaliTest`main + 50
    frame #22: 0x34394872 libdyld.dylib`<redacted> + 2

```
