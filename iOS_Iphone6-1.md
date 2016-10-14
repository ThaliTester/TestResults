#### Test 890133743ddb6d0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/890133743ddb6d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/58907CB7-2D4A-4AAF-9385-B6625E5FFA5D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/58907CB7-2D4A-4AAF-9385-B6625E5FFA5D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/890133743ddb6d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/890133743ddb6d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/363DDC55-79BF-4A5F-8678-2A0BCB418CA3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62066"
,(lldb)     command script import "/tmp/58907CB7-2D4A-4AAF-9385-B6625E5FFA5D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-14 16:30:07.886 ThaliTest[2233:4567542] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35B6E93E-89CC-46C8-A206-0225C47F3761/Library/Cookies/Cookies.binarycookies
,2016-10-14 16:30:07.962 ThaliTest[2233:4567542] Apache Cordova native platform version 4.2.1 is starting.
2016-10-14 16:30:07.964 ThaliTest[2233:4567542] Multi-tasking -> Device: YES, App: YES
,2016-10-14 16:30:07.985 ThaliTest[2233:4567542] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-14 16:30:08.465 ThaliTest[2233:4567542] Using UIWebView
,2016-10-14 16:30:08.476 ThaliTest[2233:4567542] [CDVTimer][handleopenurl] 0.337005ms
,2016-10-14 16:30:08.485 ThaliTest[2233:4567542] [CDVTimer][intentandnavigationfilter] 7.963002ms
2016-10-14 16:30:08.485 ThaliTest[2233:4567542] [CDVTimer][gesturehandler] 0.288963ms
2016-10-14 16:30:08.486 ThaliTest[2233:4567542] [CDVTimer][TotalPluginS,tartup] 10.237992ms
,2016-10-14 16:30:13.970 ThaliTest[2233:4567542] Resetting plugins due to page load.
,2016-10-14 16:30:14.345 ThaliTest[2233:4567542] Finished load of: file:///var/containers/Bundle/Application/363DDC55-79BF-4A5F-8678-2A0BCB418CA3/ThaliTest.app/www/index.html
,2016-10-14 16:30:14.676 ThaliTest[2233:4567542] JXcore Cordova plugin initializing
,2016-10-14 16:30:14.677 ThaliTest[2233:4567709] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-14 14:30:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-14 14:30:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-14 14:30:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-14 14:30:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-14 14:30:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,2016-10-14 16:30:42.814 ThaliTest[2233:4567877] *** Assertion failure in void _XCTFailureHandler(XCTestCase * _Nonnull, BOOL, const char * _Nonnull, NSUInteger, NSString * _Nonnull, NSString * _Nullable, ...)(), /Library/Caches/com.apple.xbs/Sources/XCTest,_iOS/XCTest-10112/XCTestFramework/OtherSources/XCTestAssertionsImpl.m:41
2016-10-14 16:30:42.815 ThaliTest[2233:4567877] *** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'Parameter "test" must not be nil.'
*** First throw call stack:
(0x183c3adb0 0x18329ff80 0x183c3ac80 0x1845c01c0 0x100a640e0 0x100a64464 0x10114220c 0x10112d1f0 0x100919cec 0x10090b268 0x1008bb698 0x1836854bc 0x18368547c 0x18368fd50 0x18368547c 0x183693914 0x1836930b0 0x18389d470 0x18389d020)
lib,c++abi.dylib: terminating with uncaught exception of type NSException
,Process 2233 stopped
* thread #16: tid = 0x45b345, 0x00000001837d411c libsystem_kernel.dylib`__pthread_kill + 8, queue = 'org.thaliproject.GCDAsyncSocket.delegateQueue', stop reason = signal SIGABRT
    frame #0: 0x00000001837d411c libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x1837d411c <+8>:  b.lo   0x1837d4134               ; <+32>
    0x1837d4120 <+12>: stp    x29, x30, [sp, #-16]!
    0x1837d4124 <+16>: mov    x29, sp
    0x1837d4128 <+20>: bl     0x1837ba6d8               ; cerror_nocancel
,* thread #16: tid = 0x45b345, 0x00000001837d411c libsystem_kernel.dylib`__pthread_kill + 8, queue = 'org.thaliproject.GCDAsyncSocket.delegateQueue', stop reason = signal SIGABRT
  * frame #0: 0x00000001837d411c libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x00000001838a0ef8 libsystem_pthread.dylib`pthread_kill + 112
    frame #2: 0x0000000183745dc8 libsystem_c.dylib`abort + 140
    frame #3: 0x00000001832793f4 libc++abi.dylib`<redacted> + 132
    frame #4: 0x0000000183295e98 libc++abi.dylib`<redacted> + 304
    frame #5: 0x00000001832a0248 libobjc.A.dylib`<redacted> + 124
    frame #6: 0x00000001832a0248 libobjc.A.dylib`<redacted> + 124
    frame #7: 0x0000000183292f44 libc++abi.dylib`<redacted> + 16
    frame #8: 0x000000018329285c libc++abi.dylib`__cxa_throw + 136
    frame #9: 0x00000001832a0094 libobjc.A.dylib`objc_exception_throw + 332
    frame #10: 0x0000000183c3ac80 CoreFoundation`<redacted> + 108
    frame #11: 0x00000001845c01c0 Foundation`<redacted> + 88
    frame #12: 0x0000000100a640e0 XCTest`_XCTFailureHandler + 196
    frame #13: 0x0000000100a64464 XCTest`_XCTPreformattedFailureHandler + 96
    frame #14: 0x000000010114220c libswiftXCTest.dylib`function signature specialization <Arg[1] = Owned To Guaranteed and Exploded, Arg[2] = Exploded, Arg[4] = Exploded> of function signature specialization <Arg[2] = [Closure Propagated : XCTest.(XCTFail (Swift.String, file : Swift.StaticString, line : Swift.UInt) -> ()).(implicit closure #1), Argument Types : [Swift.String]> of XCTest._XCTRegisterFailure (Swift.Bool, Swift.String, @autoclosure () -> Swift.String, Swift.StaticString, Swift.UInt) -> () + 600
    frame #15: 0x000000010112d1f0 libswiftXCTest.dylib`XCTest.XCTFail (Swift.String, file : Swift.StaticString, line : Swift.UInt) -> () + 336
    frame #16: 0x0000000100919cec ThaliCore`ThaliCore.unexpectedSocketDisconnectHandler (__ObjC.GCDAsyncSocket) -> () + 448
    frame #17: 0x000000010090b268 ThaliCore`@objc ThaliCore.TCPListener.socketDidDisconnect (__ObjC.GCDAsyncSocket, withError : Swift.Optional<__ObjC.NSError>) -> () + 64
    frame #18: 0x00000001008bb698 ThaliCore`__33-[GCDAsyncSocket closeWithError:]_block_invoke + 44
    frame #19: 0x00000001836854bc libdispatch.dylib`<redacted> + 24
    frame #20: 0x000000018368547c libdispatch.dylib`<redacted> + 16
    frame #21: 0x000000018368fd50 libdispatch.dylib`<redacted> + 1920
    frame #22: 0x000000018368547c libdispatch.dylib`<redacted> + 16
    frame #23: 0x0000000183693914 libdispatch.dylib`<redacted> + 2140
    frame #24: 0x00000001836930b0 libdispatch.dylib`<redacted> + 112
    frame #25: 0x000000018389d470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #26: 0x000000018389d020 libsystem_pthread.dylib`start_wqthread + 4

```
