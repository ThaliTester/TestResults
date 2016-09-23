#### Test 85046911dcbf444_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F639361A-D2AE-47D7-B920-44C33E41B7ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F639361A-D2AE-47D7-B920-44C33E41B7ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D008A23D-B140-4D5D-9856-E532D879BDBE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61770"
,(lldb)     command script import "/tmp/F639361A-D2AE-47D7-B920-44C33E41B7ED/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:39:33.406 ThaliTest[3113:5548458] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B5DE73E-53FC-40A1-835B-0E38F3ACF867/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:39:33.733 ThaliTest[3113:5548458] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:39:33.734 ThaliTest[3113:5548458] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:39:33.751 ThaliTest[3113:5548458] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:39:35.604 ThaliTest[3113:5548458] Using UIWebView
,2016-09-23 08:39:35.611 ThaliTest[3113:5548458] [CDVTimer][handleopenurl] 0.338018ms
,2016-09-23 08:39:35.618 ThaliTest[3113:5548458] [CDVTimer][intentandnavigationfilter] 6.880045ms
,2016-09-23 08:39:35.619 ThaliTest[3113:5548458] [CDVTimer][gesturehandler] 0.340044ms
,2016-09-23 08:39:35.619 ThaliTest[3113:5548458] [CDVTimer][TotalPluginStartup] 9.092987ms
,2016-09-23 08:39:42.711 ThaliTest[3113:5548458] Resetting plugins due to page load.
,2016-09-23 08:39:45.981 ThaliTest[3113:5548458] Finished load of: file:///var/mobile/Containers/Bundle/Application/D008A23D-B140-4D5D-9856-E532D879BDBE/ThaliTest.app/www/index.html
,2016-09-23 08:39:46.195 ThaliTest[3113:5548458] JXcore Cordova plugin initializing
,2016-09-23 08:39:46.196 ThaliTest[3113:5548733] JXcore instance initializing
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
,* thread #1: tid = 0x54a9aa, 0x0000000186df2690 Foundation`<redacted> + 364, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000186df2690 Foundation`<redacted> + 364
    frame #1: 0x0000000186df23b8 Foundation`<redacted> + 360
    frame #2: 0x0000000186df20ec Foundation`<redacted> + 124
    frame #3: 0x0000000185bda7e4 CoreBluetooth`<redacted> + 228
    frame #4: 0x000000010002f9e0 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 864
    frame #5: 0x000000010002ceb8 ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #6: 0x000000010003541c ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 56
    frame #7: 0x000000010087120c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #8: 0x00000001008a36ec XCTest`-[XCTestContext performInScope:] + 208
    frame #9: 0x0000000100871180 XCTest`-[XCTestCase invokeTest] + 164
    frame #10: 0x000000010087176c XCTest`-[XCTestCase performTest:] + 460
    frame #11: 0x000000010086f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #12: 0x000000010086f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x000000010086f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #14: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #15: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #16: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #17: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #18: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #19: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #20: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #21: 0x0000000100021d34 ThaliTest`main + 76
    frame #22: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
