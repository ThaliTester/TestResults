#### Test 864728855eac790_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5CC49854-DAC6-4A7B-9E0F-8F10F32DD328/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5CC49854-DAC6-4A7B-9E0F-8F10F32DD328/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4B4FEEF1-A47F-4104-9660-57DE3DCD2F46/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52092"
,(lldb)     command script import "/tmp/5CC49854-DAC6-4A7B-9E0F-8F10F32DD328/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 10:50:51.842 ThaliTest[3038:6125643] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BC43C338-F953-4641-8727-63F7176693F0/Library/Cookies/Cookies.binarycookies
,2016-09-23 10:50:51.961 ThaliTest[3038:6125643] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 10:50:51.963 ThaliTest[3038:6125643] Multi-tasking -> Device: YES, App: YES
,2016-09-23 10:50:51.987 ThaliTest[3038:6125643] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 10:50:53.572 ThaliTest[3038:6125643] Using UIWebView
,2016-09-23 10:50:53.580 ThaliTest[3038:6125643] [CDVTimer][handleopenurl] 0.537038ms
,2016-09-23 10:50:53.589 ThaliTest[3038:6125643] [CDVTimer][intentandnavigationfilter] 8.228004ms
2016-09-23 10:50:53.590 ThaliTest[3038:6125643] [CDVTimer][gesturehandler] 0.433981ms
2016-09-23 10:50:53.591 ThaliTest[3038:6125643] [CDVTimer][TotalPluginS,tartup] 11.618018ms
,2016-09-23 10:50:59.443 ThaliTest[3038:6125643] Resetting plugins due to page load.
,2016-09-23 10:51:02.893 ThaliTest[3038:6125643] Finished load of: file:///var/mobile/Containers/Bundle/Application/4B4FEEF1-A47F-4104-9660-57DE3DCD2F46/ThaliTest.app/www/index.html
,2016-09-23 10:51:03.084 ThaliTest[3038:6125643] JXcore Cordova plugin initializing
,2016-09-23 10:51:03.085 ThaliTest[3038:6125842] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x13f0bf550>
,Optional("B5899A86-84DD-4FEB-AF7F-81A0A7ECF91A")
,nil
,nil
,Optional("3E2DD3D5-BD45-4930-89F9-870EC8FF337B")
,Optional("C3A49679-B58A-4C0D-BB3E-862C6A49AFCF")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 10:51:27.145 ThaliTest[3038:6125643] Getting shared instance of BTmanager
,2016-09-23 10:51:27.146 ThaliTest[3038:6125643] Dispatch_once working
,2016-09-23 10:51:27.373 ThaliTest[3038:6125643] Initializing BluetoothHardwareControlManager
,2016-09-23 10:51:27.374 ThaliTest[3038:6125643] Getting private API's class
,2016-09-23 10:51:27.374 ThaliTest[3038:6125643] Finishing getting private API's class BluetoothManager
2016-09-23 10:51:27.374 ThaliTest[3038:6125643] BTM: attaching to BTServer
,2016-09-23 10:51:27.375 ThaliTest[3038:6125643] Adding notification in BluetoothHardwareControlManager
,2016-09-23 10:51:27.375 ThaliTest[3038:6125643] Adding notification in BluetoothHardwareControlManager
,2016-09-23 10:51:27.375 ThaliTest[3038:6125643] Finishing initializing BluetoothHardwareControlManager
,Process 3038 stopped
* thread #1: tid = 0x5d784b, 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x199549bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x199549bd4 <+20>: and    w12, w1, w11
    0x199549bd8 <+24>: add    x12, x10, x12, lsl #4
    0x199549bdc <+28>: ldp    x16, x17, [x12]
,* thread #1: tid = 0x5d784b, 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x00000001859b5c54 Foundation`_NSDescriptionWithStringProxyFunc + 64
    frame #2: 0x0000000184a3f764 CoreFoundation`<redacted> + 7712
    frame #3: 0x0000000184a3d90c CoreFoundation`_CFStringCreateWithFormatAndArgumentsAux2 + 244
    frame #4: 0x0000000184a5ad5c CoreFoundation`_CFLogvEx2 + 152
    frame #5: 0x0000000184a5b25c CoreFoundation`_CFLogvEx3 + 156
    frame #6: 0x00000001859a1e18 Foundation`<redacted> + 132
    frame #7: 0x00000001858d6ea4 Foundation`NSLog + 32
    frame #8: 0x00000001008afbbc ThaliCore`__49+[BluetoothHardwareControlManager sharedInstance]_block_invoke + 144
    frame #9: 0x0000000199d556a8 libdispatch.dylib`<redacted> + 16
    frame #10: 0x0000000199d564ec libdispatch.dylib`dispatch_once_f + 80
    frame #11: 0x00000001008afb28 ThaliCore`+[BluetoothHardwareControlManager sharedInstance] + 108
    frame #12: 0x00000001000f76b8 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 376
    frame #13: 0x00000001000f87a4 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #14: 0x0000000184a7aa70 CoreFoundation`<redacted> + 144
    frame #15: 0x00000001849784d4 CoreFoundation`<redacted> + 284
    frame #16: 0x00000001009a9300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #17: 0x00000001009db6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #18: 0x00000001009a9180 XCTest`-[XCTestCase invokeTest] + 164
    frame #19: 0x00000001009a976c XCTest`-[XCTestCase performTest:] + 460
    frame #20: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #21: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #22: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x00000001859b7e60 Foundation`<redacted> + 340
    frame #24: 0x0000000184a2c544 CoreFoundation`<redacted> + 24
    frame #25: 0x0000000184a2bfd8 CoreFoundation`<redacted> + 540
    frame #26: 0x0000000184a29cd8 CoreFoundation`<redacted> + 724
    frame #27: 0x0000000184958ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #28: 0x000000018fb94088 GraphicsServices`GSEventRunModal + 180
    frame #29: 0x000000018a070ffc UIKit`UIApplicationMain + 204
    frame #30: 0x00000001000e299c ThaliTest`main + 76
    frame #31: 0x0000000199d868b8 libdyld.dylib`<redacted> + 4

```
