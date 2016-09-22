#### Test 8617437951c5913_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/31A8731F-6B73-4C1E-BC34-C97EF0F0A3E0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/31A8731F-6B73-4C1E-BC34-C97EF0F0A3E0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4271AEDE-2E61-4CF6-BBAF-C6BD18B62EE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60332"
,(lldb)     command script import "/tmp/31A8731F-6B73-4C1E-BC34-C97EF0F0A3E0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 16:52:36.537 ThaliTest[1204:1760921] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/981DC18F-CA2A-4974-A100-755A01D13C91/Library/Cookies/Cookies.binarycookies
,2016-09-22 16:52:36.577 ThaliTest[1204:1760921] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 16:52:36.578 ThaliTest[1204:1760921] Multi-tasking -> Device: YES, App: YES
,2016-09-22 16:52:36.592 ThaliTest[1204:1760921] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 16:52:36.946 ThaliTest[1204:1760921] Using UIWebView
,2016-09-22 16:52:36.951 ThaliTest[1204:1760921] [CDVTimer][handleopenurl] 0.297010ms
,2016-09-22 16:52:36.956 ThaliTest[1204:1760921] [CDVTimer][intentandnavigationfilter] 4.625022ms
2016-09-22 16:52:36.956 ThaliTest[1204:1760921] [CDVTimer][gesturehandler] 0.187039ms
2016-09-22 16:52:36.957 ThaliTest[1204:1760921] [CDVTimer][TotalPluginS,tartup] 6.192982ms
,2016-09-22 16:52:42.521 ThaliTest[1204:1760921] Resetting plugins due to page load.
,2016-09-22 16:52:42.875 ThaliTest[1204:1760921] Finished load of: file:///var/containers/Bundle/Application/4271AEDE-2E61-4CF6-BBAF-C6BD18B62EE0/ThaliTest.app/www/index.html
,2016-09-22 16:52:43.205 ThaliTest[1204:1760921] JXcore Cordova plugin initializing
,2016-09-22 16:52:43.206 ThaliTest[1204:1761099] JXcore instance initializing
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
,* thread #1: tid = 0x1ade99, 0x00000001832b8158 libobjc.A.dylib`objc_release + 8, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x7000000000000)
  * frame #0: 0x00000001832b8158 libobjc.A.dylib`objc_release + 8
    frame #1: 0x00000001000315bc ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 916
    frame #2: 0x000000010002df9c ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #3: 0x000000010003740c ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 56
    frame #4: 0x00000001008c120c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #5: 0x00000001008f36ec XCTest`-[XCTestContext performInScope:] + 208
    frame #6: 0x00000001008c1180 XCTest`-[XCTestCase invokeTest] + 164
    frame #7: 0x00000001008c176c XCTest`-[XCTestCase performTest:] + 460
    frame #8: 0x00000001008bf1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x00000001008bf1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #10: 0x00000001008bf1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #11: 0x000000018461002c Foundation`<redacted> + 340
    frame #12: 0x0000000183bf109c CoreFoundation`<redacted> + 24
    frame #13: 0x0000000183bf0b30 CoreFoundation`<redacted> + 540
    frame #14: 0x0000000183bee830 CoreFoundation`<redacted> + 724
    frame #15: 0x0000000183b18c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #16: 0x0000000185400088 GraphicsServices`GSEventRunModal + 180
    frame #17: 0x0000000188e06088 UIKit`UIApplicationMain + 204
    frame #18: 0x000000010002299c ThaliTest`main + 76
    frame #19: 0x00000001836b68b8 libdyld.dylib`<redacted> + 4

```
