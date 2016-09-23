#### Test 864728855eac790_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4C82902B-36C1-481F-A3A1-1EF252CB4E93/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4C82902B-36C1-481F-A3A1-1EF252CB4E93/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/99DF1A9E-B13C-4E39-A7A9-AFCFC8304F27/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52088"
,(lldb)     command script import "/tmp/4C82902B-36C1-481F-A3A1-1EF252CB4E93/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 01:50:49.505 ThaliTest[1441:1767241] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CDE663F6-3394-435E-88C4-4AE7736F1666/Library/Cookies/Cookies.binarycookies
,2016-09-23 01:50:49.541 ThaliTest[1441:1767241] Apache Cordova native platform version 4.2.1 is starting.
2016-09-23 01:50:49.542 ThaliTest[1441:1767241] Multi-tasking -> Device: YES, App: YES
,2016-09-23 01:50:49.553 ThaliTest[1441:1767241] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 01:50:49.905 ThaliTest[1441:1767241] Using UIWebView
,2016-09-23 01:50:49.910 ThaliTest[1441:1767241] [CDVTimer][handleopenurl] 0.323057ms
,2016-09-23 01:50:49.915 ThaliTest[1441:1767241] [CDVTimer][intentandnavigationfilter] 4.768014ms
2016-09-23 01:50:49.915 ThaliTest[1441:1767241] [CDVTimer][gesturehandler] 0.182986ms
2016-09-23 01:50:49.916 ThaliTest[1441:1767241] [CDVTimer][TotalPluginS,tartup] 6.312013ms
,2016-09-23 01:50:55.787 ThaliTest[1441:1767241] Resetting plugins due to page load.
,2016-09-23 01:50:56.263 ThaliTest[1441:1767241] Finished load of: file:///var/containers/Bundle/Application/99DF1A9E-B13C-4E39-A7A9-AFCFC8304F27/ThaliTest.app/www/index.html
,2016-09-23 01:50:56.634 ThaliTest[1441:1767241] JXcore Cordova plugin initializing
,2016-09-23 01:50:56.635 ThaliTest[1441:1767407] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15ed4dfa0>
,Optional("73892FCE-62C5-4863-AAAF-9E7B2B0E8384")
,nil
,nil
,Optional("6A22B263-0EB2-453F-B0CC-267B1793874D")
,Optional("36FBC1F3-A73F-40DB-804F-A855CD220FA6")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 01:51:18.598 ThaliTest[1441:1767241] Getting shared instance of BTmanager
2016-09-23 01:51:18.598 ThaliTest[1441:1767241] Dispatch_once working
,2016-09-23 01:51:18.782 ThaliTest[1441:1767241] Initializing BluetoothHardwareControlManager
2016-09-23 01:51:18.782 ThaliTest[1441:1767241] Getting private API's class
2016-09-23 01:51:18.782 ThaliTest[1441:1767241] Finishing getting private API's class, BluetoothManager
2016-09-23 01:51:18.783 ThaliTest[1441:1767241] BTM: attaching to BTServer
2016-09-23 01:51:18.783 ThaliTest[1441:1767241] Adding notification in BluetoothHardwareControlManager
2016-09-23 01:51:18.783 ThaliTest[1441:1767241] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 01:51:18.783 ThaliTest[1441:1767241] Finishing initializing BluetoothHardwareControlManager
,Process 1441 stopped
* thread #1: tid = 0x1af749, 0x0000000180a11b90 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 21 messages, stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x0000000180a11b90 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x180a11b90 <+16>: ldp    x10, x11, [x9, #16]
    0x180a11b94 <+20>: and    w12, w1, w11
    0x180a11b98 <+24>: add    x12, x10, x12, lsl #4
    0x180a11b9c <+28>: ldp    x16, x17, [x12]
,* thread #1: tid = 0x1af749, 0x0000000180a11b90 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 21 messages, stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x0000000180a11b90 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000181d6de20 Foundation`_NSDescriptionWithStringProxyFunc + 64
    frame #2: 0x000000018136432c CoreFoundation`<redacted> + 7824
    frame #3: 0x0000000181362464 CoreFoundation`_CFStringCreateWithFormatAndArgumentsAux2 + 244
    frame #4: 0x0000000181380bc4 CoreFoundation`_CFLogvEx2 + 152
    frame #5: 0x00000001813810c4 CoreFoundation`_CFLogvEx3 + 156
    frame #6: 0x0000000181d59fe4 Foundation`<redacted> + 132
    frame #7: 0x0000000181c8e904 Foundation`NSLog + 32
    frame #8: 0x00000001008c3bbc ThaliCore`__49+[BluetoothHardwareControlManager sharedInstance]_block_invoke + 144
    frame #9: 0x0000000180de547c libdispatch.dylib`<redacted> + 16
    frame #10: 0x0000000180de62c0 libdispatch.dylib`dispatch_once_f + 80
    frame #11: 0x00000001008c3b28 ThaliCore`+[BluetoothHardwareControlManager sharedInstance] + 108
    frame #12: 0x00000001000ff6b8 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 376
    frame #13: 0x00000001001007a4 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #14: 0x00000001813a0a60 CoreFoundation`<redacted> + 144
    frame #15: 0x0000000181298488 CoreFoundation`<redacted> + 284
    frame #16: 0x00000001009a9300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #17: 0x00000001009db6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #18: 0x00000001009a9180 XCTest`-[XCTestCase invokeTest] + 164
    frame #19: 0x00000001009a976c XCTest`-[XCTestCase performTest:] + 460
    frame #20: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #21: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #22: 0x00000001009a71d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x0000000181d7002c Foundation`<redacted> + 340
    frame #24: 0x000000018135109c CoreFoundation`<redacted> + 24
    frame #25: 0x0000000181350b30 CoreFoundation`<redacted> + 540
    frame #26: 0x000000018134e830 CoreFoundation`<redacted> + 724
    frame #27: 0x0000000181278c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #28: 0x0000000182b60088 GraphicsServices`GSEventRunModal + 180
    frame #29: 0x0000000186566088 UIKit`UIApplicationMain + 204
    frame #30: 0x00000001000ea99c ThaliTest`main + 76
    frame #31: 0x0000000180e168b8 libdyld.dylib`<redacted> + 4

```
