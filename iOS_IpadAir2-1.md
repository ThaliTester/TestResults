#### Test 864728855eac790_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C2F594F9-C381-497D-893E-D049EE3A543F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C2F594F9-C381-497D-893E-D049EE3A543F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/962B347A-1545-4C1B-BB46-6F833AF32855/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52087"
,(lldb)     command script import "/tmp/C2F594F9-C381-497D-893E-D049EE3A543F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 10:50:54.037 ThaliTest[3141:5563012] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28D5F38F-D683-476E-A589-FF9903860691/Library/Cookies/Cookies.binarycookies
,2016-09-23 10:50:54.394 ThaliTest[3141:5563012] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 10:50:54.395 ThaliTest[3141:5563012] Multi-tasking -> Device: YES, App: YES
,2016-09-23 10:50:54.417 ThaliTest[3141:5563012] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 10:50:56.425 ThaliTest[3141:5563012] Using UIWebView
,2016-09-23 10:50:56.432 ThaliTest[3141:5563012] [CDVTimer][handleopenurl] 0.326991ms
,2016-09-23 10:50:56.438 ThaliTest[3141:5563012] [CDVTimer][intentandnavigationfilter] 6.264985ms
,2016-09-23 10:50:56.439 ThaliTest[3141:5563012] [CDVTimer][gesturehandler] 0.285983ms
,2016-09-23 10:50:56.439 ThaliTest[3141:5563012] [CDVTimer][TotalPluginStartup] 8.358002ms
,2016-09-23 10:51:02.744 ThaliTest[3141:5563012] Resetting plugins due to page load.
,2016-09-23 10:51:05.628 ThaliTest[3141:5563012] Finished load of: file:///var/mobile/Containers/Bundle/Application/962B347A-1545-4C1B-BB46-6F833AF32855/ThaliTest.app/www/index.html
,2016-09-23 10:51:05.841 ThaliTest[3141:5563012] JXcore Cordova plugin initializing
,2016-09-23 10:51:05.842 ThaliTest[3141:5563278] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x159a045b0>
,Optional("A7FD6B39-DA0F-4392-9877-22E8B4A2272C")
,nil
,nil
,Optional("92807101-C00F-4F02-AD2F-02AE9457E08A")
,Optional("03E5903D-67DE-4FC0-92C7-9D2616457669")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 10:51:31.568 ThaliTest[3141:5563012] Getting shared instance of BTmanager
2016-09-23 10:51:31.568 ThaliTest[3141:5563012] Dispatch_once working
,2016-09-23 10:51:31.790 ThaliTest[3141:5563012] Initializing BluetoothHardwareControlManager
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] Getting private API's class
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] Finishing getting private API's class BluetoothManager
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] BTM: attaching to BTServer
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] Adding notification in BluetoothHardwareControlManager
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 10:51:31.791 ThaliTest[3141:5563012] Finishing initializing BluetoothHardwareControlManager
,Process 3141 stopped
* thread #1: tid = 0x54e284, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x19abf1bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x19abf1bd4 <+20>: and    w12, w1, w11
    0x19abf1bd8 <+24>: add    x12, x10, x12, lsl #4
    0x19abf1bdc <+28>: ldp    x16, x17, [x12]
,* thread #1: tid = 0x54e284, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000186eadc54 Foundation`_NSDescriptionWithStringProxyFunc + 64
    frame #2: 0x0000000185f37764 CoreFoundation`<redacted> + 7712
    frame #3: 0x0000000185f3590c CoreFoundation`_CFStringCreateWithFormatAndArgumentsAux2 + 244
    frame #4: 0x0000000185f52d5c CoreFoundation`_CFLogvEx2 + 152
    frame #5: 0x0000000185f5325c CoreFoundation`_CFLogvEx3 + 156
    frame #6: 0x0000000186e99e18 Foundation`<redacted> + 132
    frame #7: 0x0000000186dceea4 Foundation`NSLog + 32
    frame #8: 0x0000000100857bbc ThaliCore`__49+[BluetoothHardwareControlManager sharedInstance]_block_invoke + 144
    frame #9: 0x000000019b3f16a8 libdispatch.dylib`<redacted> + 16
    frame #10: 0x000000019b3f24ec libdispatch.dylib`dispatch_once_f + 80
    frame #11: 0x0000000100857b28 ThaliCore`+[BluetoothHardwareControlManager sharedInstance] + 108
    frame #12: 0x00000001000a76b8 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 376
    frame #13: 0x00000001000a87a4 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #14: 0x0000000185f72a70 CoreFoundation`<redacted> + 144
    frame #15: 0x0000000185e704d4 CoreFoundation`<redacted> + 284
    frame #16: 0x0000000100949300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #17: 0x000000010097b6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #18: 0x0000000100949180 XCTest`-[XCTestCase invokeTest] + 164
    frame #19: 0x000000010094976c XCTest`-[XCTestCase performTest:] + 460
    frame #20: 0x00000001009471d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #21: 0x00000001009471d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #22: 0x00000001009471d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #24: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #25: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #26: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #27: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #28: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #29: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #30: 0x000000010009299c ThaliTest`main + 76
    frame #31: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
