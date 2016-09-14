#### Test 852639023cb0bc0_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6661E206-8ECD-408A-8936-38F7616B4906/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/6661E206-8ECD-408A-8936-38F7616B4906/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639023cb0bc0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FEFAD939-AD9F-41E0-AC95-365EBE686416/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50274"
,(lldb)     command script import "/tmp/6661E206-8ECD-408A-8936-38F7616B4906/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 15:22:55.864 ThaliTest[761:808335] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F83CE8C8-B3D5-4423-A628-0BBC42D87229/Library/Cookies/Cookies.binarycookies
,2016-09-14 15:22:55.901 ThaliTest[761:808335] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 15:22:55.903 ThaliTest[761:808335] Multi-tasking -> Device: YES, App: YES
,2016-09-14 15:22:55.913 ThaliTest[761:808335] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 15:22:56.241 ThaliTest[761:808335] Using UIWebView
,2016-09-14 15:22:56.246 ThaliTest[761:808335] [CDVTimer][handleopenurl] 0.334024ms
,2016-09-14 15:22:56.250 ThaliTest[761:808335] [CDVTimer][intentandnavigationfilter] 4.082978ms
2016-09-14 15:22:56.251 ThaliTest[761:808335] [CDVTimer][gesturehandler] 0.133038ms
2016-09-14 15:22:56.251 ThaliTest[761:808335] [CDVTimer][TotalPluginStartup] 5.491018ms
,2016-09-14 15:23:02.573 ThaliTest[761:808335] Resetting plugins due to page load.
,2016-09-14 15:23:03.278 ThaliTest[761:808335] Finished load of: file:///var/containers/Bundle/Application/FEFAD939-AD9F-41E0-AC95-365EBE686416/ThaliTest.app/www/index.html
,2016-09-14 15:23:03.655 ThaliTest[761:808335] JXcore Cordova plugin initializing
,2016-09-14 15:23:03.656 ThaliTest[761:808503] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x141d0e150>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 15:23:27.588 ThaliTest[761:808335] BTM: attaching to BTServer
,2016-09-14 15:23:38.182 ThaliTest[761:808335] BTM: local device power state changed
,2016-09-14 15:23:38.938 ThaliTest[761:808335] BTM: local device power state changed
2016-09-14 15:23:38.942 ThaliTest[761:808335] BTM: power is now on
,* thread #1: tid = 0xc558f, 0x0000000180de9d48 libdispatch.dylib`<redacted> + 148, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 11 messages, stop reason = EXC_BREAKPOINT (code=1, subcode=0x180de9d48)
  * frame #0: 0x0000000180de9d48 libdispatch.dylib`<redacted> + 148
    frame #1: 0x0000000180de9990 libdispatch.dylib`<redacted> + 56
    frame #2: 0x0000000180de55d8 libdispatch.dylib`<redacted> + 56
    frame #3: 0x000000010010528c ThaliTest`function signature specialization <Arg[1] = Dead> of ThaliTest.AppContextTests.(changeBluetoothState in _F556606E85F68DC26CEAF18691199363) (to : ThaliTest.BluetoothHardwareState, andWaitUntilChangesWithTimeout : Swift.Double) -> () + 1456
    frame #4: 0x0000000100102c90 ThaliTest`ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 4548
    frame #5: 0x0000000100102d28 ThaliTest`@objc ThaliTest.AppContextTests.testUpdateNetworkStatus () -> () + 28
    frame #6: 0x00000001813a0a60 CoreFoundation`<redacted> + 144
    frame #7: 0x0000000181298488 CoreFoundation`<redacted> + 284
    frame #8: 0x000000010099d300 XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 364
    frame #9: 0x00000001009cf6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #10: 0x000000010099d180 XCTest`-[XCTestCase invokeTest] + 164
    frame #11: 0x000000010099d76c XCTest`-[XCTestCase performTest:] + 460
    frame #12: 0x000000010099b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x000000010099b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #14: 0x000000010099b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #15: 0x0000000181d7002c Foundation`<redacted> + 340
    frame #16: 0x000000018135109c CoreFoundation`<redacted> + 24
    frame #17: 0x0000000181350b30 CoreFoundation`<redacted> + 540
    frame #18: 0x000000018134e830 CoreFoundation`<redacted> + 724
    frame #19: 0x0000000181278c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #20: 0x0000000182b60088 GraphicsServices`GSEventRunModal + 180
    frame #21: 0x0000000186566088 UIKit`UIApplicationMain + 204
    frame #22: 0x00000001000ee360 ThaliTest`main + 76
    frame #23: 0x0000000180e168b8 libdyld.dylib`<redacted> + 4

```
