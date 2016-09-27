#### Test 868913053534d83_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4E5BFC5F-6B8A-4D5C-8594-84B2755CDFF2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4E5BFC5F-6B8A-4D5C-8594-84B2755CDFF2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/868913053534d83/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F371F76B-E97B-41EF-9BDE-6F2EAD679A06/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55022"
,(lldb)     command script import "/tmp/4E5BFC5F-6B8A-4D5C-8594-84B2755CDFF2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:45:19.876 ThaliTest[3342:6781193] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/38D9424E-3F9B-468C-BF0A-DCBB91FABB6F/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:45:19.993 ThaliTest[3342:6781193] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:45:19.995 ThaliTest[3342:6781193] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:45:20.016 ThaliTest[3342:6781193] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:45:21.444 ThaliTest[3342:6781193] Using UIWebView
,2016-09-27 12:45:21.453 ThaliTest[3342:6781193] [CDVTimer][handleopenurl] 0.642002ms
,2016-09-27 12:45:21.462 ThaliTest[3342:6781193] [CDVTimer][intentandnavigationfilter] 8.270979ms
2016-09-27 12:45:21.462 ThaliTest[3342:6781193] [CDVTimer][gesturehandler] 0.366986ms
2016-09-27 12:45:21.463 ThaliTest[3342:6781193] [CDVTimer][TotalPluginS,tartup] 11.129022ms
,2016-09-27 12:45:27.289 ThaliTest[3342:6781193] Resetting plugins due to page load.
,2016-09-27 12:45:30.794 ThaliTest[3342:6781193] Finished load of: file:///var/mobile/Containers/Bundle/Application/F371F76B-E97B-41EF-9BDE-6F2EAD679A06/ThaliTest.app/www/index.html
,2016-09-27 12:45:31.094 ThaliTest[3342:6781193] JXcore Cordova plugin initializing
,2016-09-27 12:45:31.095 ThaliTest[3342:6781409] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x129982170>
,Asynchronous wait failed: Exceeded timeout of 1 seconds, with unfulfilled expectations: "get timeout error on create socket". in file: Optional("<unknown>"), line: 0
,2016-09-27 12:45:53.499 ThaliTest[3342:6781193] *** Assertion failure in -[XCTestExpectation fulfill], /Library/Caches/com.apple.xbs/Sources/XCTest_iOS/XCTest-10112/XCTestFramework/Classes/XCTestCase+AsynchronousTesting.m:451
,2016-09-27 12:45:53.502 ThaliTest[3342:6781193] *** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'API violation - called -[XCTestExpectation fulfill] after the wait context has ended for get timeout error on create ,socket.'
*** First throw call stack:
(0x184a74f48 0x199537f80 0x184a74e18 0x185968a1c 0x10091be68 0x10080e688 0x1007f6984 0x1007f9230 0x1007f687c 0x199d556e8 0x199d556a8 0x199d60f34 0x199d556a8 0x199d6c2bc 0x199d57b9c 0x199d5a868 0x184a2c1f8 0x184a2a060 ,0x184958ca0 0x1858d12bc 0x10091b3ac 0x10080d35c 0x10080d5d4 0x184a7aa70 0x1849784d4 0x1008d5300 0x1009076ec 0x1008d5180 0x1008d576c 0x1008d31d0 0x1008d31d0 0x1008d31d0 0x1007e0ac0 0x1007e0b44 0x1859b7e60 0x184a2c544 0x184a2bfd8 0x184a29cd8 0x184958ca0 0x18,fb94088 0x18a070ffc 0x100011d54 0x199d868b8)
,libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 3342 stopped
* thread #1: tid = 0x677909, 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x199ea3140 <+8>:  b.lo   0x199ea3158               ; <+32>
    0x199ea3144 <+12>: stp    x29, x30, [sp, #-16]!
    0x199ea3148 <+16>: mov    x29, sp
    0x199ea314c <+20>: bl     0x199e8a140               ; cerror_nocancel
,* thread #1: tid = 0x677909, 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x0000000199f6cef8 libsystem_pthread.dylib`pthread_kill + 112
    frame #2: 0x0000000199e16b78 libsystem_c.dylib`abort + 140
    frame #3: 0x0000000198bc13f4 libc++abi.dylib`<redacted> + 132
    frame #4: 0x0000000198bdde98 libc++abi.dylib`<redacted> + 304
    frame #5: 0x0000000199538248 libobjc.A.dylib`<redacted> + 124
    frame #6: 0x0000000199538248 libobjc.A.dylib`<redacted> + 124
    frame #7: 0x0000000198bdaf44 libc++abi.dylib`<redacted> + 16
    frame #8: 0x0000000198bda85c libc++abi.dylib`__cxa_throw + 136
    frame #9: 0x0000000199538094 libobjc.A.dylib`objc_exception_throw + 332
    frame #10: 0x0000000184a74e18 CoreFoundation`<redacted> + 108
    frame #11: 0x0000000185968a1c Foundation`<redacted> + 112
    frame #12: 0x000000010091be68 XCTest`-[XCTestExpectation fulfill] + 304
    frame #13: 0x000000010080e688 ThaliCore`ThaliCore.SocketRelayTests.(testGetTimeoutErrorOnCreateSocket () -> ()).(closure #1) + 160
    frame #14: 0x00000001007f6984 ThaliCore`ThaliCore.SocketRelay.((addToDiscardQueue in _84A54C3FA7F9516F235E0B1B96E1B169) (A, for : ThaliCore.Session, completion : () -> ()) -> ()).(closure #1).(closure #1) + 188
    frame #15: 0x00000001007f9230 ThaliCore`ThaliCore.Atomic.withValue <A> ((A) throws -> A1) throws -> A1 + 136
    frame #16: 0x00000001007f687c ThaliCore`ThaliCore.SocketRelay.((addToDiscardQueue in _84A54C3FA7F9516F235E0B1B96E1B169) (A, for : ThaliCore.Session, completion : () -> ()) -> ()).(closure #1) + 392
    frame #17: 0x0000000199d556e8 libdispatch.dylib`<redacted> + 24
    frame #18: 0x0000000199d556a8 libdispatch.dylib`<redacted> + 16
    frame #19: 0x0000000199d60f34 libdispatch.dylib`<redacted> + 92
    frame #20: 0x0000000199d556a8 libdispatch.dylib`<redacted> + 16
    frame #21: 0x0000000199d6c2bc libdispatch.dylib`<redacted> + 2556
    frame #22: 0x0000000199d57b9c libdispatch.dylib`<redacted> + 808
    frame #23: 0x0000000199d5a868 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 492
    frame #24: 0x0000000184a2c1f8 CoreFoundation`<redacted> + 12
    frame #25: 0x0000000184a2a060 CoreFoundation`<redacted> + 1628
    frame #26: 0x0000000184958ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #27: 0x00000001858d12bc Foundation`<redacted> + 308
    frame #28: 0x000000010091b3ac XCTest`-[XCTestCase(AsynchronousTesting) waitForExpectationsWithTimeout:handler:] + 988
    frame #29: 0x000000010080d35c ThaliCore`ThaliCore.SocketRelayTests.testGetTimeoutErrorOnCreateSocket () -> () + 596
    frame #30: 0x000000010080d5d4 ThaliCore`@objc ThaliCore.SocketRelayTests.testGetTimeoutErrorOnCreateSocket () -> () + 28
    frame #31: 0x0000000184a7aa70 CoreFoundation`<redacted> + 144
    frame #32: 0x00000001849784d4 CoreFoundation`<redacted> + 284
    frame #33: 0x00000001008d5300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #34: 0x00000001009076ec XCTest`-[XCTestContext performInScope:] + 208
    frame #35: 0x00000001008d5180 XCTest`-[XCTestCase invokeTest] + 164
    frame #36: 0x00000001008d576c XCTest`-[XCTestCase performTest:] + 460
    frame #37: 0x00000001008d31d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #38: 0x00000001008d31d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #39: 0x00000001008d31d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #40: 0x00000001007e0ac0 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #41: 0x00000001007e0b44 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #42: 0x00000001859b7e60 Foundation`<redacted> + 340
    frame #43: 0x0000000184a2c544 CoreFoundation`<redacted> + 24
    frame #44: 0x0000000184a2bfd8 CoreFoundation`<redacted> + 540
    frame #45: 0x0000000184a29cd8 CoreFoundation`<redacted> + 724
    frame #46: 0x0000000184958ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #47: 0x000000018fb94088 GraphicsServices`GSEventRunModal + 180
    frame #48: 0x000000018a070ffc UIKit`UIApplicationMain + 204
    frame #49: 0x0000000100011d54 ThaliTest`main + 76
    frame #50: 0x0000000199d868b8 libdyld.dylib`<redacted> + 4

```
