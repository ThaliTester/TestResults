#### Test 107380351668086c_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/107380351668086c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,(lldb) command source -s 0 '/tmp/70669A1A-C564-4A88-873D-8D71945A4BA1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/70669A1A-C564-4A88-873D-8D71945A4BA1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/107380351668086c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/107380351668086c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2046EA26-EEB6-4751-A17C-2C0C4874A3A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51520"
,(lldb)     command script import "/tmp/70669A1A-C564-4A88-873D-8D71945A4BA1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-23 14:52:57.406 ThaliTest[12261:4733551] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF577964-65D7-4018-A149-A1E85E2ED407/Library/Cookies/Cookies.binarycookies
,2017-02-23 14:52:57.495 ThaliTest[12261:4733551] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-23 14:52:57.496 ThaliTest[12261:4733551] Multi-tasking -> Device: YES, App: YES
,2017-02-23 14:52:57.517 ThaliTest[12261:4733551] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-23 14:52:57.937 ThaliTest[12261:4733551] Using UIWebView
,2017-02-23 14:52:57.948 ThaliTest[12261:4733551] [CDVTimer][handleopenurl] 0.396967ms
,2017-02-23 14:52:57.955 ThaliTest[12261:4733551] [CDVTimer][intentandnavigationfilter] 6.859958ms
2017-02-23 14:52:57.956 ThaliTest[12261:4733551] [CDVTimer][gesturehandler] 0.286043ms
2017-02-23 14:52:57.956 ThaliTest[12261:4733551] [CDVTimer][TotalPlug,inStartup] 9.205997ms
,2017-02-23 14:53:04.260 ThaliTest[12261:4733551] Resetting plugins due to page load.
,2017-02-23 14:53:04.596 ThaliTest[12261:4733551] Finished load of: file:///var/containers/Bundle/Application/2046EA26-EEB6-4751-A17C-2C0C4874A3A4/ThaliTest.app/www/index.html
,2017-02-23 14:53:04.943 ThaliTest[12261:4733551] JXcore Cordova plugin initializing
,2017-02-23 14:53:04.944 ThaliTest[12261:4733744] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-23 13:53:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,* thread #1: tid = 0x483a6f, 0x0000000181ad10d4 libsystem_kernel.dylib`syscall_thread_switch + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000181ad10d4 libsystem_kernel.dylib`syscall_thread_switch + 8
    frame #1: 0x0000000181bb1534 libsystem_platform.dylib`<redacted> + 120
    frame #2: 0x0000000181b15514 libsystem_malloc.dylib`<redacted> + 116
    frame #3: 0x0000000181b15458 libsystem_malloc.dylib`malloc_zone_malloc + 116
    frame #4: 0x0000000181b199dc libsystem_malloc.dylib`malloc + 52
    frame #5: 0x0000000100cfb8c4 libswiftCore.dylib`swift_slowAlloc + 12
    frame #6: 0x0000000100cfb914 libswiftCore.dylib`_swift_allocObject_(swift::HeapMetadata const*, unsigned long, unsigned long) + 28
    frame #7: 0x0000000100c6b4ec libswiftCore.dylib`function signature specialization <Arg[3] = Dead> of Swift._StringBuffer.init (capacity : Swift.Int, initialSize : Swift.Int, elementWidth : Swift.Int) -> Swift._StringBuffer + 148
    frame #8: 0x0000000100c348d0 libswiftCore.dylib`Swift._StringCore._copyInPlace (newSize : Swift.Int, newCapacity : Swift.Int, minElementWidth : Swift.Int) -> () + 96
    frame #9: 0x00000001000d2798 ThaliTest`generic specialization <Swift.Character._SmallUTF16 with Swift.Character._SmallUTF16 : Swift.SequenceType in Swift, Swift.IndexingGenerator<Swift.Character._SmallUTF16> with Swift.IndexingGenerator<Swift.Character._SmallUTF16> : Swift.GeneratorType in Swift, Swift.Slice<Swift.Character._SmallUTF16>> of Swift._StringCore.appendContentsOf <A where A: Swift.SequenceType, A.Generator.Element == Swift.UInt16> (A) -> () + 560
    frame #10: 0x00000001000ce47c ThaliTest`function signature specialization <Arg[1] = Dead> of static (extension in ThaliTest):Swift.String.random (length : Swift.Int) -> Swift.String + 640
    frame #11: 0x00000001000cb5d8 ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 36
    frame #12: 0x0000000100a4520c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #13: 0x0000000100a776ec XCTest`-[XCTestContext performInScope:] + 208
    frame #14: 0x0000000100a45180 XCTest`-[XCTestCase invokeTest] + 164
    frame #15: 0x0000000100a4576c XCTest`-[XCTestCase performTest:] + 460
    frame #16: 0x0000000100a431d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #17: 0x0000000100a431d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #18: 0x0000000100a431d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #19: 0x0000000100884fe4 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #20: 0x0000000100885068 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #21: 0x000000018292802c Foundation`<redacted> + 340
    frame #22: 0x0000000181f0909c CoreFoundation`<redacted> + 24
    frame #23: 0x0000000181f08b30 CoreFoundation`<redacted> + 540
    frame #24: 0x0000000181f06830 CoreFoundation`<redacted> + 724
    frame #25: 0x0000000181e30c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #26: 0x0000000183718088 GraphicsServices`GSEventRunModal + 180
    frame #27: 0x000000018711e088 UIKit`UIApplicationMain + 204
    frame #28: 0x00000001000b520c ThaliTest`main + 76
    frame #29: 0x00000001819ce8b8 libdyld.dylib`<redacted> + 4

```
