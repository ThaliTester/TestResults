#### Test 852639023cb0bc0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/19B7AA9C-8F2F-484E-8576-4ED66AFB827F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/19B7AA9C-8F2F-484E-8576-4ED66AFB827F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/96A9662A-30DB-4B89-BED6-EBD8ED4DD934/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50268"
,(lldb)     command script import "/tmp/19B7AA9C-8F2F-484E-8576-4ED66AFB827F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 00:22:42.870 ThaliTest[2376:4466993] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/02ED9C0F-94D4-46CB-85B7-F219D2A2138F/Library/Cookies/Cookies.binarycookies
,2016-09-15 00:22:43.083 ThaliTest[2376:4466993] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 00:22:43.084 ThaliTest[2376:4466993] Multi-tasking -> Device: YES, App: YES
,2016-09-15 00:22:43.096 ThaliTest[2376:4466993] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 00:22:43.910 ThaliTest[2376:4466993] Using UIWebView
,2016-09-15 00:22:43.912 ThaliTest[2376:4466993] [CDVTimer][handleopenurl] 0.118971ms
,2016-09-15 00:22:43.914 ThaliTest[2376:4466993] [CDVTimer][intentandnavigationfilter] 1.840055ms
2016-09-15 00:22:43.915 ThaliTest[2376:4466993] [CDVTimer][gesturehandler] 0.077009ms
2016-09-15 00:22:43.915 ThaliTest[2376:4466993] [CDVTimer][TotalPluginStartup] 2.469003ms
,2016-09-15 00:22:47.027 ThaliTest[2376:4466993] Resetting plugins due to page load.
,2016-09-15 00:22:48.465 ThaliTest[2376:4466993] Finished load of: file:///var/mobile/Containers/Bundle/Application/96A9662A-30DB-4B89-BED6-EBD8ED4DD934/ThaliTest.app/www/index.html
,2016-09-15 00:22:48.605 ThaliTest[2376:4466993] JXcore Cordova plugin initializing
,2016-09-15 00:22:48.606 ThaliTest[2376:4467173] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14046d790>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-15 00:23:13.214 ThaliTest[2376:4466993] BTM: attaching to BTServer
,2016-09-15 00:23:18.554 ThaliTest[2376:4466993] BTM: local device power state changed
2016-09-15 00:23:18.554 ThaliTest[2376:4466993] BTM: power is now off
,* thread #1: tid = 0x442931, 0x000000019b3f5f74 libdispatch.dylib`<redacted> + 148, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 7 messages, stop reason = EXC_BREAKPOINT (code=1, subcode=0x19b3f5f74)
  * frame #0: 0x000000019b3f5f74 libdispatch.dylib`<redacted> + 148
    frame #1: 0x000000019b3f5bbc libdispatch.dylib`<redacted> + 56
    frame #2: 0x000000019b3f1804 libdispatch.dylib`<redacted> + 56
    frame #3: 0x000000010006928c ThaliTest`function signature specialization <Arg[1] = Dead> of ThaliTest.AppContextTests.(changeBluetoothState in _F556606E85F68DC26CEAF18691199363) (to : ThaliTest.BluetoothHardwareState, andWaitUntilChangesWithTimeout : Swift.Double) -> () + 1456
    frame #4: 0x00000001000667c8 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 3324
    frame #5: 0x0000000100066d28 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #6: 0x0000000185f72a70 CoreFoundation`<redacted> + 144
    frame #7: 0x0000000185e704d4 CoreFoundation`<redacted> + 284
    frame #8: 0x0000000100919300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #9: 0x000000010094b6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #10: 0x0000000100919180 XCTest`-[XCTestCase invokeTest] + 164
    frame #11: 0x000000010091976c XCTest`-[XCTestCase performTest:] + 460
    frame #12: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #14: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #15: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #16: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #17: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #18: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #19: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #20: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #21: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #22: 0x0000000100052360 ThaliTest`main + 76
    frame #23: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
