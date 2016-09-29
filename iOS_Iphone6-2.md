#### Test 87116923b621cb4_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/35E1311D-2668-4359-B6B1-E5118E5DD48B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/35E1311D-2668-4359-B6B1-E5118E5DD48B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923b621cb4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/054BBD32-EB0A-43C6-995D-9D13A441AC2A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49309"
,(lldb)     command script import "/tmp/35E1311D-2668-4359-B6B1-E5118E5DD48B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 01:19:06.269 ThaliTest[1853:2437957] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5DEB82A-8658-4EAD-9889-BA8F8F21F72F/Library/Cookies/Cookies.binarycookies
,2016-09-29 01:19:06.310 ThaliTest[1853:2437957] Apache Cordova native platform version 4.2.1 is starting.
2016-09-29 01:19:06.311 ThaliTest[1853:2437957] Multi-tasking -> Device: YES, App: YES
,2016-09-29 01:19:06.323 ThaliTest[1853:2437957] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 01:19:06.641 ThaliTest[1853:2437957] Using UIWebView
,2016-09-29 01:19:06.645 ThaliTest[1853:2437957] [CDVTimer][handleopenurl] 0.280976ms
,2016-09-29 01:19:06.649 ThaliTest[1853:2437957] [CDVTimer][intentandnavigationfilter] 3.475010ms
2016-09-29 01:19:06.649 ThaliTest[1853:2437957] [CDVTimer][gesturehandler] 0.136018ms
2016-09-29 01:19:06.649 ThaliTest[1853:2437957] [CDVTimer][TotalPluginStartup] 4.670978ms
,2016-09-29 01:19:13.051 ThaliTest[1853:2437957] Resetting plugins due to page load.
,2016-09-29 01:19:13.747 ThaliTest[1853:2437957] Finished load of: file:///var/containers/Bundle/Application/054BBD32-EB0A-43C6-995D-9D13A441AC2A/ThaliTest.app/www/index.html
,2016-09-29 01:19:14.120 ThaliTest[1853:2437957] JXcore Cordova plugin initializing
,2016-09-29 01:19:14.122 ThaliTest[1853:2438127] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-29 01:19:29.954 ThaliTest[1853:2438010] *** Assertion failure in -[XCTestExpectation fulfill], /Library/Caches/com.apple.xbs/Sources/XCTest_iOS/XCTest-10112/XCTestFramework/Classes/XCTestCase+AsynchronousTesting.m:450
,2016-09-29 01:19:29.957 ThaliTest[1853:2438010] *** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'API violation - multiple calls made to -[XCTestExpectation fulfill] for connectToPeer method returns callback on disc,onnect..'
*** First throw call stack:
(0x18139adb0 0x1809fff80 0x18139ac80 0x181d20154 0x100977de0 0x10083aff8 0x10082c368 0x10082b934 0x100830a6c 0x193c161a4 0x180de54bc 0x180de547c 0x180df14c0 0x180de8f80 0x180df3390 0x180df30b0 0x180ffd470 0x180ffd020)
,XCTAssertEqual failed: ("Optional(0)") is not equal to ("Optional(1)") - BrowserManager still has active Relay instances. in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 310
,libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1853 stopped
* thread #5: tid = 0x25337a, 0x0000000180f3411c libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
    frame #0: 0x0000000180f3411c libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x180f3411c <+8>:  b.lo   0x180f34134               ; <+32>
    0x180f34120 <+12>: stp    x29, x30, [sp, #-16]!
    0x180f34124 <+16>: mov    x29, sp
    0x180f34128 <+20>: bl     0x180f1a6d8               ; cerror_nocancel
,* thread #5: tid = 0x25337a, 0x0000000180f3411c libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
  * frame #0: 0x0000000180f3411c libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x0000000181000ef8 libsystem_pthread.dylib`pthread_kill + 112
    frame #2: 0x0000000180ea5dc8 libsystem_c.dylib`abort + 140
    frame #3: 0x00000001809d93f4 libc++abi.dylib`<redacted> + 132
    frame #4: 0x00000001809f5e98 libc++abi.dylib`<redacted> + 304
    frame #5: 0x0000000180a00248 libobjc.A.dylib`<redacted> + 124
    frame #6: 0x0000000180a00248 libobjc.A.dylib`<redacted> + 124
    frame #7: 0x00000001809f2f44 libc++abi.dylib`<redacted> + 16
    frame #8: 0x00000001809f285c libc++abi.dylib`__cxa_throw + 136
    frame #9: 0x0000000180a00094 libobjc.A.dylib`objc_exception_throw + 332
    frame #10: 0x000000018139ac80 CoreFoundation`<redacted> + 108
    frame #11: 0x0000000181d20154 Foundation`<redacted> + 112
    frame #12: 0x0000000100977de0 XCTest`-[XCTestExpectation fulfill] + 168
    frame #13: 0x000000010083aff8 ThaliCore`partial apply forwarder for ThaliCore.BrowserManagerTests.(testDisconnectDecrementsActiveRelays () -> ()).(closure #3) + 100
    frame #14: 0x000000010082c368 ThaliCore`ThaliCore.BrowserManager.(connectToPeer (ThaliCore.PeerIdentifier, syncValue : Swift.String, completion : (syncValue : Swift.String, error : Swift.Optional<Swift.ErrorType>, port : Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #2) + 316
    frame #15: 0x000000010082b934 ThaliCore`partial apply forwarder for ThaliCore.BrowserManager.(connectToPeer (ThaliCore.PeerIdentifier, syncValue : Swift.String, completion : (syncValue : Swift.String, error : Swift.Optional<Swift.ErrorType>, port : Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #2) + 132
    frame #16: 0x0000000100830a6c ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChangeState : __C.MCSessionState) -> () + 68
    frame #17: 0x0000000193c161a4 MultipeerConnectivity`<redacted> + 124
    frame #18: 0x0000000180de54bc libdispatch.dylib`<redacted> + 24
    frame #19: 0x0000000180de547c libdispatch.dylib`<redacted> + 16
    frame #20: 0x0000000180df14c0 libdispatch.dylib`<redacted> + 864
    frame #21: 0x0000000180de8f80 libdispatch.dylib`<redacted> + 464
    frame #22: 0x0000000180df3390 libdispatch.dylib`<redacted> + 728
    frame #23: 0x0000000180df30b0 libdispatch.dylib`<redacted> + 112
    frame #24: 0x0000000180ffd470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #25: 0x0000000180ffd020 libsystem_pthread.dylib`start_wqthread + 4

```
