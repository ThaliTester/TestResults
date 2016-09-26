#### Test 8652210239a4b7e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9B0EE081-651D-4D49-8CDC-023F10697345/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9B0EE081-651D-4D49-8CDC-023F10697345/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/314E119A-E0F2-4442-983E-288BB808F595/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57704"
,(lldb)     command script import "/tmp/9B0EE081-651D-4D49-8CDC-023F10697345/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:19:09.014 ThaliTest[3352:5968125] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5BA26BBA-3A95-4225-8EE9-0AF7E342E025/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:19:09.371 ThaliTest[3352:5968125] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:19:09.373 ThaliTest[3352:5968125] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:19:09.391 ThaliTest[3352:5968125] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:19:11.366 ThaliTest[3352:5968125] Using UIWebView
,2016-09-26 16:19:11.373 ThaliTest[3352:5968125] [CDVTimer][handleopenurl] 0.329971ms
,2016-09-26 16:19:11.380 ThaliTest[3352:5968125] [CDVTimer][intentandnavigationfilter] 6.320000ms
,2016-09-26 16:19:11.380 ThaliTest[3352:5968125] [CDVTimer][gesturehandler] 0.297964ms
,2016-09-26 16:19:11.381 ThaliTest[3352:5968125] [CDVTimer][TotalPluginStartup] 8.433044ms
,2016-09-26 16:19:17.792 ThaliTest[3352:5968125] Resetting plugins due to page load.
,2016-09-26 16:19:20.745 ThaliTest[3352:5968125] Finished load of: file:///var/mobile/Containers/Bundle/Application/314E119A-E0F2-4442-983E-288BB808F595/ThaliTest.app/www/index.html
,2016-09-26 16:19:21.021 ThaliTest[3352:5968125] JXcore Cordova plugin initializing
,2016-09-26 16:19:21.022 ThaliTest[3352:5968399] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1302ef390>
,Optional("9D8F1CF8-CBAF-4550-B463-06B2641D3518")
,nil
,nil
,Optional("33C9EB80-74DC-4FD7-A0C0-2BC6711DB42C")
,Optional("23AA0109-1105-426A-87BF-B48B1F71BBBC")
,Process 3352 stopped
* thread #1: tid = 0x5b10fd, 0x000000019b44dd88 libsystem_blocks.dylib`_Block_object_dispose + 92, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 7 messages, stop reason = EXC_BAD_ACCESS (code=1, address=0x9000000000000010)
    frame #0: 0x000000019b44dd88 libsystem_blocks.dylib`_Block_object_dispose + 92
libsystem_blocks.dylib`_Block_object_dispose:
->  0x19b44dd88 <+92>:  ldr    w9, [x8, #16]!
    0x19b44dd8c <+96>:  tbz    w9, #24, 0x19b44de30      ; <+260>
    0x19b44dd90 <+100>: ldr    w9, [x8]
    0x19b44dd94 <+104>: and    w9, w9, #0xfffe
,* thread #1: tid = 0x5b10fd, 0x000000019b44dd88 libsystem_blocks.dylib`_Block_object_dispose + 92, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 7 messages, stop reason = EXC_BAD_ACCESS (code=1, address=0x9000000000000010)
  * frame #0: 0x000000019b44dd88 libsystem_blocks.dylib`_Block_object_dispose + 92
    frame #1: 0x000000019b44d8e8 libsystem_blocks.dylib`_Block_release + 156
    frame #2: 0x0000000185edf65c CoreFoundation`<redacted> + 48
    frame #3: 0x0000000185f77e70 CoreFoundation`<redacted> + 2152
    frame #4: 0x0000000185e74eb4 CoreFoundation`_CFXNotificationRemoveObservers + 164
    frame #5: 0x0000000186dc35b0 Foundation`<redacted> + 236
    frame #6: 0x000000010080c218 ThaliCore`@objc ThaliCore.ApplicationStateNotificationsManager.__deallocating_deinit + 96
    frame #7: 0x0000000100053220 ThaliTest`@objc ThaliTest.AppContext.__ivar_destroyer + 32
    frame #8: 0x000000019abdeb54 libobjc.A.dylib`<redacted> + 148
    frame #9: 0x000000019abea080 libobjc.A.dylib`objc_destructInstance + 92
    frame #10: 0x000000019abea0e0 libobjc.A.dylib`object_dispose + 28
    frame #11: 0x000000010005bbe0 ThaliTest`@objc ThaliTest.AppContextTests.tearDown () -> () + 116
    frame #12: 0x00000001008f94c4 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 816
    frame #13: 0x000000010092b6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #14: 0x00000001008f9180 XCTest`-[XCTestCase invokeTest] + 164
    frame #15: 0x00000001008f976c XCTest`-[XCTestCase performTest:] + 460
    frame #16: 0x00000001008f71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #17: 0x00000001008f71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #18: 0x00000001008f71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #19: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #20: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #21: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #22: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #23: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #24: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #25: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #26: 0x0000000100047110 ThaliTest`main + 76
    frame #27: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
