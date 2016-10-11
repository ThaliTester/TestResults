#### Test 884969632a6a9b7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1F986429-420C-4496-B8E8-B75B833FF068/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1F986429-420C-4496-B8E8-B75B833FF068/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969632a6a9b7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3F7B1701-3CDD-4D9D-B40D-865DC337CBC5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55817"
,(lldb)     command script import "/tmp/1F986429-420C-4496-B8E8-B75B833FF068/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-11 02:30:48.767 ThaliTest[4002:8916207] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/416A1613-559D-44A6-B3FF-C3033853788C/Library/Cookies/Cookies.binarycookies
,2016-10-11 02:30:48.879 ThaliTest[4002:8916207] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-11 02:30:48.881 ThaliTest[4002:8916207] Multi-tasking -> Device: YES, App: YES
,2016-10-11 02:30:48.906 ThaliTest[4002:8916207] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-11 02:30:50.222 ThaliTest[4002:8916207] Using UIWebView
,2016-10-11 02:30:50.231 ThaliTest[4002:8916207] [CDVTimer][handleopenurl] 0.597000ms
,2016-10-11 02:30:50.242 ThaliTest[4002:8916207] [CDVTimer][intentandnavigationfilter] 10.397971ms
2016-10-11 02:30:50.243 ThaliTest[4002:8916207] [CDVTimer][gesturehandler] 0.384033ms
2016-10-11 02:30:50.243 ThaliTest[4002:8916207] [CDVTimer][TotalPlugin,Startup] 13.252020ms
,2016-10-11 02:30:56.085 ThaliTest[4002:8916207] Resetting plugins due to page load.
,2016-10-11 02:30:59.774 ThaliTest[4002:8916207] Finished load of: file:///var/mobile/Containers/Bundle/Application/3F7B1701-3CDD-4D9D-B40D-865DC337CBC5/ThaliTest.app/www/index.html
,2016-10-11 02:31:00.092 ThaliTest[4002:8916207] JXcore Cordova plugin initializing
,2016-10-11 02:31:00.093 ThaliTest[4002:8916427] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-11 00:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-11 00:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-11 00:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-11 00:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-11 00:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x15f7ded00>
,Optional("F8AE9A11-7702-451E-A343-D323BB21EDE4")
,nil
,nil
,Optional("070F5FF9-FE3C-4431-A6AE-F844FB9BF0E0")
,Optional("FF3933A5-C3EF-4B82-8A1C-1FFB5D865A93")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-11 00:31:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  60
Number of passed tests:  60
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  15.80378800630569
,2016-10-11 00:31:28 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-11 00:31:29 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-10-11 00:31:29 - WARN testUtils: 'myNameCallback not set!'
2016-10-11 00:31:29 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-11 02:31:29.567 ThaliTest[4002:8916474] *** Assertion failure in void _XCTFailureHandler(XCTestCase * _Nonnull, BOOL, const char * _Nonnull, NSUInteger, NSString * _Nonnull, NSString * _Nullable, ...)(), /Library/Caches/com.apple.xbs/Sources/XCTest_iOS/XCTest-10112/XCTestFramework/OtherSources/XCTestAssertionsImpl.m:41
,2016-10-11 02:31:29.572 ThaliTest[4002:8916474] *** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'Parameter "test" must not be nil.'
*** First throw call stack:
(0x184a74f48 0x199537f80 0x184a74e18 0x185968a88 0x1009a40e0 0x1009a4464 0x1010ca20c 0x1010b51f0 0x1008b787c 0x187cd74e0 0x199d556e8 0x199d556a8 0x199d616ec 0x199d591ac 0x199d635bc 0x199d632dc 0x199f69470 0x199f69020)
,libc++abi.dylib: ,terminating with uncaught exception of type NSException,
,Process 4002 stopped
* thread #22: tid = 0x880dfa, 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
    frame #0: 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x199ea3140 <+8>:  b.lo   0x199ea3158               ; <+32>
    0x199ea3144 <+12>: stp    x29, x30, [sp, #-16]!
    0x199ea3148 <+16>: mov    x29, sp
    0x199ea314c <+20>: bl     0x199e8a140               ; cerror_nocancel
,* thread #22: tid = 0x880dfa, 0x0000000199ea3140 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
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
    frame #11: 0x0000000185968a88 Foundation`<redacted> + 88
    frame #12: 0x00000001009a40e0 XCTest`_XCTFailureHandler + 196
    frame #13: 0x00000001009a4464 XCTest`_XCTPreformattedFailureHandler + 96
    frame #14: 0x00000001010ca20c libswiftXCTest.dylib`function signature specialization <Arg[1] = Owned To Guaranteed and Exploded, Arg[2] = Exploded, Arg[4] = Exploded> of function signature specialization <Arg[2] = [Closure Propagated : XCTest.(XCTFail (Swift.String, file : Swift.StaticString, line : Swift.UInt) -> ()).(implicit closure #1), Argument Types : [Swift.String]> of XCTest._XCTRegisterFailure (Swift.Bool, Swift.String, @autoclosure () -> Swift.String, Swift.StaticString, Swift.UInt) -> () + 600
    frame #15: 0x00000001010b51f0 libswiftXCTest.dylib`XCTest.XCTFail (Swift.String, file : Swift.StaticString, line : Swift.UInt) -> () + 336
    frame #16: 0x00000001008b787c ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChangeState : __C.MCSessionState) -> () + 68
    frame #17: 0x0000000187cd74e0 MultipeerConnectivity`<redacted> + 132
    frame #18: 0x0000000199d556e8 libdispatch.dylib`<redacted> + 24
    frame #19: 0x0000000199d556a8 libdispatch.dylib`<redacted> + 16
    frame #20: 0x0000000199d616ec libdispatch.dylib`<redacted> + 864
    frame #21: 0x0000000199d591ac libdispatch.dylib`<redacted> + 464
    frame #22: 0x0000000199d635bc libdispatch.dylib`<redacted> + 728
    frame #23: 0x0000000199d632dc libdispatch.dylib`<redacted> + 112
    frame #24: 0x0000000199f69470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #25: 0x0000000199f69020 libsystem_pthread.dylib`start_wqthread + 4

```
