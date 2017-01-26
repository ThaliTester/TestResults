#### Test 103295431c2804f2_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/3E77EFAE-97EA-4AEA-9BD3-0A91A38CFD3B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3E77EFAE-97EA-4AEA-9BD3-0A91A38CFD3B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5C34B28A-34EA-4F86-9D2C-EAB5DEA7B14A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57436"
,(lldb)     command script import "/tmp/3E77EFAE-97EA-4AEA-9BD3-0A91A38CFD3B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-26 13:41:08.450 ThaliTest[2848:7395238] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D9CBF18D-A6C7-4EA3-AC21-9E20AD9F49D9/Library/Cookies/Cookies.binarycookies
,2017-01-26 13:41:08.789 ThaliTest[2848:7395238] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-26 13:41:08.791 ThaliTest[2848:7395238] Multi-tasking -> Device: YES, App: YES
,2017-01-26 13:41:08.810 ThaliTest[2848:7395238] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-26 13:41:10.772 ThaliTest[2848:7395238] Using UIWebView
,2017-01-26 13:41:10.781 ThaliTest[2848:7395238] [CDVTimer][handleopenurl] 0.361025ms
,2017-01-26 13:41:10.788 ThaliTest[2848:7395238] [CDVTimer][intentandnavigationfilter] 6.268024ms
,2017-01-26 13:41:10.789 ThaliTest[2848:7395238] [CDVTimer][gesturehandler] 0.281990ms
,2017-01-26 13:41:10.789 ThaliTest[2848:7395238] [CDVTimer][TotalPluginStartup] 8.478999ms
,2017-01-26 13:41:17.337 ThaliTest[2848:7395238] Resetting plugins due to page load.
,2017-01-26 13:41:20.736 ThaliTest[2848:7395238] Finished load of: file:///var/mobile/Containers/Bundle/Application/5C34B28A-34EA-4F86-9D2C-EAB5DEA7B14A/ThaliTest.app/www/index.html
,2017-01-26 13:41:20.950 ThaliTest[2848:7395238] JXcore Cordova plugin initializing
,2017-01-26 13:41:20.951 ThaliTest[2848:7395453] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-26 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-26 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-26 12:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-26 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-26 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,objc[2848]: Cannot form weak reference to instance (0x1600e36a0) of class ThaliTest.AppContext. It is possible that this object was over-released, or is in the process of deallocation.
,Process 2848 stopped
* thread #1: tid = 0x70d7a6, 0x0000000198943aac libobjc.A.dylib`<redacted>, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=1, subcode=0x198943aac)
    frame #0: 0x0000000198943aac libobjc.A.dylib`<redacted>
libobjc.A.dylib`<redacted>:
->  0x198943aac <+0>: brk    #0x1
    0x198943ab0 <+0>: stp    x29, x30, [sp, #-16]!
    0x198943ab4 <+4>: mov    x29, sp
    0x198943ab8 <+8>: sub    sp, sp, #16               ; =16 
,* thread #1: tid = 0x70d7a6, 0x0000000198943aac libobjc.A.dylib`<redacted>, queue = 'com.apple.main-thread', stop reason = EXC_BREAKPOINT (code=1, subcode=0x198943aac)
  * frame #0: 0x0000000198943aac libobjc.A.dylib`<redacted>
    frame #1: 0x0000000198943b24 libobjc.A.dylib`<redacted> + 88
    frame #2: 0x00000001989558cc libobjc.A.dylib`<redacted> + 316
    frame #3: 0x000000019895c688 libobjc.A.dylib`objc_initWeak + 224
    frame #4: 0x00000001000c1f94 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 276
    frame #5: 0x00000001000be720 ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #6: 0x00000001000c95fc ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 84
    frame #7: 0x0000000100a3d20c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #8: 0x0000000100a6f6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #9: 0x0000000100a3d180 XCTest`-[XCTestCase invokeTest] + 164
    frame #10: 0x0000000100a3d76c XCTest`-[XCTestCase performTest:] + 460
    frame #11: 0x0000000100a3b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #12: 0x0000000100a3b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x0000000100a3b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #14: 0x000000010088deac ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #15: 0x000000010088df30 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #16: 0x0000000184c13e60 Foundation`<redacted> + 340
    frame #17: 0x0000000183c88544 CoreFoundation`<redacted> + 24
    frame #18: 0x0000000183c87fd8 CoreFoundation`<redacted> + 540
    frame #19: 0x0000000183c85cd8 CoreFoundation`<redacted> + 724
    frame #20: 0x0000000183bb4ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #21: 0x000000018ec34088 GraphicsServices`GSEventRunModal + 180
    frame #22: 0x00000001892ccffc UIKit`UIApplicationMain + 204
    frame #23: 0x00000001000b3200 ThaliTest`main + 76
    frame #24: 0x00000001991868b8 libdyld.dylib`<redacted> + 4

```
