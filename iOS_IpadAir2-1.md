#### Test 88496963915c2f2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/94EABEC1-B919-43DB-9636-FA585D7C5EEA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/94EABEC1-B919-43DB-9636-FA585D7C5EEA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24251D53-0A61-4D3D-8EB4-B515431B331B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51208"
,(lldb)     command script import "/tmp/94EABEC1-B919-43DB-9636-FA585D7C5EEA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-07 22:07:28.340 ThaliTest[3919:7360390] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E4FEA08-494A-4AD7-AADC-BB7195A197AD/Library/Cookies/Cookies.binarycookies
,2016-10-07 22:07:28.699 ThaliTest[3919:7360390] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-07 22:07:28.700 ThaliTest[3919:7360390] Multi-tasking -> Device: YES, App: YES
,2016-10-07 22:07:28.719 ThaliTest[3919:7360390] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-07 22:07:30.629 ThaliTest[3919:7360390] Using UIWebView
,2016-10-07 22:07:30.637 ThaliTest[3919:7360390] [CDVTimer][handleopenurl] 1.592994ms
,2016-10-07 22:07:30.644 ThaliTest[3919:7360390] [CDVTimer][intentandnavigationfilter] 6.457984ms
,2016-10-07 22:07:30.645 ThaliTest[3919:7360390] [CDVTimer][gesturehandler] 0.295997ms
,2016-10-07 22:07:30.645 ThaliTest[3919:7360390] [CDVTimer][TotalPluginStartup] 10.013998ms
,2016-10-07 22:07:37.271 ThaliTest[3919:7360390] Resetting plugins due to page load.
,2016-10-07 22:07:40.348 ThaliTest[3919:7360390] Finished load of: file:///var/mobile/Containers/Bundle/Application/24251D53-0A61-4D3D-8EB4-B515431B331B/ThaliTest.app/www/index.html
,2016-10-07 22:07:40.564 ThaliTest[3919:7360390] JXcore Cordova plugin initializing
,2016-10-07 22:07:40.565 ThaliTest[3919:7360692] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-07 20:07:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-07 20:07:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-07 20:07:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-07 20:07:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-07 20:07:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x135d48fc0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("F7199999-3563-46C7-B082-D0DDCB863E6C")
,nil
,nil
,Optional("ECAEC3AA-ECA6-442A-A959-2C347ECEF7A0")
,Optional("2BB344DB-F5D5-4A24-909D-AA72E88F7F5B")
,* thread #1: tid = 0x704f86, 0x000000019b578124 libsystem_malloc.dylib`<redacted> + 316, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 7 messages
  * frame #0: 0x000000019b578124 libsystem_malloc.dylib`<redacted> + 316
    frame #1: 0x000000019b576fd8 libsystem_malloc.dylib`<redacted> + 1540
    frame #2: 0x000000019b5755bc libsystem_malloc.dylib`<redacted> + 268
    frame #3: 0x000000019b575468 libsystem_malloc.dylib`malloc_zone_malloc + 116
    frame #4: 0x000000019b5799ec libsystem_malloc.dylib`malloc + 52
    frame #5: 0x0000000100c238c4 libswiftCore.dylib`swift_slowAlloc + 12
    frame #6: 0x0000000100bfaf80 libswiftCore.dylib`allocateBuffer value witness for Swift.ImplicitlyUnwrappedOptional + 48
    frame #7: 0x0000000100a94480 libswiftCore.dylib`Swift._forceBridgeFromObjectiveC <A> (Swift.AnyObject, A.Type) -> A + 80
    frame #8: 0x0000000100af5e64 libswiftCore.dylib`Swift._NativeDictionaryStorageOwner.bridgingObjectForKey (Swift.AnyObject) -> Swift.Optional<Swift.AnyObject> + 108
    frame #9: 0x0000000100af5ddc libswiftCore.dylib`Swift._NativeDictionaryStorageOwner.objectForKey (Swift.AnyObject) -> Swift.Optional<Swift.AnyObject> + 36
    frame #10: 0x0000000100af5ff4 libswiftCore.dylib`@objc Swift._NativeDictionaryStorageOwner.objectForKey (Swift.AnyObject) -> Swift.Optional<Swift.AnyObject> + 44
    frame #11: 0x0000000185ea0d78 CoreFoundation`<redacted> + 232
    frame #12: 0x0000000185e9b090 CoreFoundation`<redacted> + 268
    frame #13: 0x0000000185be7dc0 CoreBluetooth`<redacted> + 464
    frame #14: 0x0000000185bda9dc CoreBluetooth`<redacted> + 732
    frame #15: 0x00000001000c6ac8 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 864
    frame #16: 0x00000001000c3308 ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #17: 0x00000001000cd88c ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 84
    frame #18: 0x000000010097920c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #19: 0x00000001009ab6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #20: 0x0000000100979180 XCTest`-[XCTestCase invokeTest] + 164
    frame #21: 0x000000010097976c XCTest`-[XCTestCase performTest:] + 460
    frame #22: 0x00000001009771d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x00000001009771d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #24: 0x00000001009771d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #25: 0x0000000100883ba8 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #26: 0x0000000100883c2c ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #27: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #28: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #29: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #30: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #31: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #32: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #33: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #34: 0x00000001000b7a24 ThaliTest`main + 76
    frame #35: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
