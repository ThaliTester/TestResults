#### Test 868913053534d83_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5E586805-1C3E-4B24-87E4-3BE9EA86E95E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5E586805-1C3E-4B24-87E4-3BE9EA86E95E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/27C0F3D6-5ECC-4E1E-B7B7-99AF51AB655A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55016"
,(lldb)     command script import "/tmp/5E586805-1C3E-4B24-87E4-3BE9EA86E95E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:45:13.933 ThaliTest[3436:6082189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/62CAC113-1332-451D-BC8B-FC6DC6E3F85C/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:45:14.296 ThaliTest[3436:6082189] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:45:14.297 ThaliTest[3436:6082189] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:45:14.317 ThaliTest[3436:6082189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:45:16.309 ThaliTest[3436:6082189] Using UIWebView
,2016-09-27 12:45:16.315 ThaliTest[3436:6082189] [CDVTimer][handleopenurl] 0.465989ms
,2016-09-27 12:45:16.322 ThaliTest[3436:6082189] [CDVTimer][intentandnavigationfilter] 6.489992ms
,2016-09-27 12:45:16.323 ThaliTest[3436:6082189] [CDVTimer][gesturehandler] 0.301003ms
,2016-09-27 12:45:16.323 ThaliTest[3436:6082189] [CDVTimer][TotalPluginStartup] 8.916974ms
,2016-09-27 12:45:22.988 ThaliTest[3436:6082189] Resetting plugins due to page load.
,2016-09-27 12:45:26.034 ThaliTest[3436:6082189] Finished load of: file:///var/mobile/Containers/Bundle/Application/27C0F3D6-5ECC-4E1E-B7B7-99AF51AB655A/ThaliTest.app/www/index.html
,2016-09-27 12:45:26.316 ThaliTest[3436:6082189] JXcore Cordova plugin initializing
,2016-09-27 12:45:26.318 ThaliTest[3436:6082441] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x128227db0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found advertiser's peer". in file: Optional("<unknown>"), line: 0
,failed - peer identifier should be not nil in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 45
,XCTAssertEqual failed: ("Optional(0)") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 224
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("11EE2136-AAC7-4791-B208-22157C04E276")
,nil
,nil
,Optional("D65311CF-E521-495F-BB97-048430C2EEAD")
,Optional("E477D8C6-0115-45B8-9B28-B92B05194069")
,* thread #1: tid = 0x5cce8d, 0x000000019b530a40 libsystem_kernel.dylib`mach_msg_trap + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x000000019b530a40 libsystem_kernel.dylib`mach_msg_trap + 8
    frame #1: 0x000000019b5308bc libsystem_kernel.dylib`mach_msg + 72
    frame #2: 0x0000000185e4fc48 CoreFoundation`CFRunLoopWakeUp + 192
    frame #3: 0x0000000198a67b2c WebCore`<redacted> + 448
    frame #4: 0x0000000185f1260c CoreFoundation`<redacted> + 20
    frame #5: 0x0000000185f11e2c CoreFoundation`<redacted> + 396
    frame #6: 0x0000000185f11bac CoreFoundation`<redacted> + 60
    frame #7: 0x0000000185f77424 CoreFoundation`<redacted> + 1532
    frame #8: 0x0000000185e52714 CoreFoundation`_CFXNotificationPost + 368
    frame #9: 0x0000000186dc2dcc Foundation`<redacted> + 68
    frame #10: 0x00000001000f78dc ThaliTest`ThaliTest.AppContextTests.testDidEnterForeground () -> () + 384
    frame #11: 0x00000001000f7980 ThaliTest`@objc ThaliTest.AppContextTests.testDidEnterForeground () -> () + 28
    frame #12: 0x0000000185f72a70 CoreFoundation`<redacted> + 144
    frame #13: 0x0000000185e704d4 CoreFoundation`<redacted> + 284
    frame #14: 0x0000000100991300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #15: 0x00000001009c36ec XCTest`-[XCTestContext performInScope:] + 208
    frame #16: 0x0000000100991180 XCTest`-[XCTestCase invokeTest] + 164
    frame #17: 0x000000010099176c XCTest`-[XCTestCase performTest:] + 460
    frame #18: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #19: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #20: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #21: 0x000000010089cac0 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #22: 0x000000010089cb44 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #23: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #24: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #25: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #26: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #27: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #28: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #29: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #30: 0x00000001000e1d54 ThaliTest`main + 76
    frame #31: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
