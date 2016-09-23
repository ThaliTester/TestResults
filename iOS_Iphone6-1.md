#### Test 864728855eac790_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7456200A-A59A-40D3-9840-1A9E133C2278/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7456200A-A59A-40D3-9840-1A9E133C2278/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728855eac790/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5B6F198F-E260-45E1-A0BC-639F83CAAC0A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52086"
,(lldb)     command script import "/tmp/7456200A-A59A-40D3-9840-1A9E133C2278/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 10:50:49.051 ThaliTest[1281:1860783] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/54744A25-22EF-479B-A34D-521C742E596E/Library/Cookies/Cookies.binarycookies
,2016-09-23 10:50:49.126 ThaliTest[1281:1860783] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 10:50:49.128 ThaliTest[1281:1860783] Multi-tasking -> Device: YES, App: YES
,2016-09-23 10:50:49.148 ThaliTest[1281:1860783] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 10:50:49.632 ThaliTest[1281:1860783] Using UIWebView
,2016-09-23 10:50:49.639 ThaliTest[1281:1860783] [CDVTimer][handleopenurl] 0.333011ms
,2016-09-23 10:50:49.648 ThaliTest[1281:1860783] [CDVTimer][intentandnavigationfilter] 7.676005ms
2016-09-23 10:50:49.648 ThaliTest[1281:1860783] [CDVTimer][gesturehandler] 0.316024ms
2016-09-23 10:50:49.649 ThaliTest[1281:1860783] [CDVTimer][TotalPluginS,tartup] 9.974957ms
,2016-09-23 10:50:54.972 ThaliTest[1281:1860783] Resetting plugins due to page load.
,2016-09-23 10:50:55.342 ThaliTest[1281:1860783] Finished load of: file:///var/containers/Bundle/Application/5B6F198F-E260-45E1-A0BC-639F83CAAC0A/ThaliTest.app/www/index.html
,2016-09-23 10:50:55.673 ThaliTest[1281:1860783] JXcore Cordova plugin initializing
,2016-09-23 10:50:55.674 ThaliTest[1281:1860937] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13f8680a0>
,Optional("C114B223-0F92-4E8D-B9E8-AC5D8888CD72")
,nil
,nil
,Optional("F54FE484-C8DC-48D9-8D47-851E6A8F9F4D")
,Optional("FB05871C-5EB8-4EEB-BC06-E9B44BFF85E3")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 10:51:18.228 ThaliTest[1281:1860783] Getting shared instance of BTmanager
2016-09-23 10:51:18.228 ThaliTest[1281:1860783] Dispatch_once working
,2016-09-23 10:51:18.356 ThaliTest[1281:1860783] Initializing BluetoothHardwareControlManager
2016-09-23 10:51:18.356 ThaliTest[1281:1860783] Getting private API's class
2016-09-23 10:51:18.356 ThaliTest[1281:1860783] Finishing getting private API's class, BluetoothManager
2016-09-23 10:51:18.356 ThaliTest[1281:1860783] BTM: attaching to BTServer
2016-09-23 10:51:18.356 ThaliTest[1281:1860783] Adding notification in BluetoothHardwareControlManager
2016-09-23 10:51:18.356 ThaliTest[1281:1860783] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 10:51:18.357 ThaliTest[1281:1860783] Finishing initializing BluetoothHardwareControlManager
,* thread #1: tid = 0x1c64af, 0x00000001832b1b90 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 16 messages, stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x00000001832b1b90 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x000000018460de20 Foundation`_NSDescriptionWithStringProxyFunc + 64
    frame #2: 0x0000000183c0432c CoreFoundation`<redacted> + 7824
    frame #3: 0x0000000183c02464 CoreFoundation`_CFStringCreateWithFormatAndArgumentsAux2 + 244
    frame #4: 0x0000000183c20bc4 CoreFoundation`_CFLogvEx2 + 152
    frame #5: 0x0000000183c210c4 CoreFoundation`_CFLogvEx3 + 156
    frame #6: 0x00000001845f9fe4 Foundation`<redacted> + 132
    frame #7: 0x000000018452e904 Foundation`NSLog + 32
    frame #8: 0x00000001008a3bbc ThaliCore`__49+[BluetoothHardwareControlManager sharedInstance]_block_invoke + 144
    frame #9: 0x000000018368547c libdispatch.dylib`<redacted> + 16
    frame #10: 0x00000001836862c0 libdispatch.dylib`dispatch_once_f + 80
    frame #11: 0x00000001008a3b28 ThaliCore`+[BluetoothHardwareControlManager sharedInstance] + 108
    frame #12: 0x00000001000eb6b8 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 376
    frame #13: 0x00000001000ec7a4 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #14: 0x0000000183c40a60 CoreFoundation`<redacted> + 144
    frame #15: 0x0000000183b38488 CoreFoundation`<redacted> + 284
    frame #16: 0x0000000100999300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #17: 0x00000001009cb6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #18: 0x0000000100999180 XCTest`-[XCTestCase invokeTest] + 164
    frame #19: 0x000000010099976c XCTest`-[XCTestCase performTest:] + 460
    frame #20: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #21: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #22: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x000000018461002c Foundation`<redacted> + 340
    frame #24: 0x0000000183bf109c CoreFoundation`<redacted> + 24
    frame #25: 0x0000000183bf0b30 CoreFoundation`<redacted> + 540
    frame #26: 0x0000000183bee830 CoreFoundation`<redacted> + 724
    frame #27: 0x0000000183b18c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #28: 0x0000000185400088 GraphicsServices`GSEventRunModal + 180
    frame #29: 0x0000000188e06088 UIKit`UIApplicationMain + 204
    frame #30: 0x00000001000d699c ThaliTest`main + 76
    frame #31: 0x00000001836b68b8 libdyld.dylib`<redacted> + 4

```
