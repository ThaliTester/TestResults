#### Test 871169230429d0a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D012ACEC-0724-4635-8C23-A0C435A28D2F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D012ACEC-0724-4635-8C23-A0C435A28D2F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5906F988-ED2B-408E-A254-ACD34E9355C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55486"
,(lldb)     command script import "/tmp/D012ACEC-0724-4635-8C23-A0C435A28D2F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 16:41:05.533 ThaliTest[3549:6231945] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D3588FC5-79E5-482B-93AE-4F158FD09B5C/Library/Cookies/Cookies.binarycookies
,2016-09-28 16:41:05.879 ThaliTest[3549:6231945] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 16:41:05.881 ThaliTest[3549:6231945] Multi-tasking -> Device: YES, App: YES
,2016-09-28 16:41:05.900 ThaliTest[3549:6231945] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 16:41:07.874 ThaliTest[3549:6231945] Using UIWebView
,2016-09-28 16:41:07.881 ThaliTest[3549:6231945] [CDVTimer][handleopenurl] 0.549018ms
,2016-09-28 16:41:07.888 ThaliTest[3549:6231945] [CDVTimer][intentandnavigationfilter] 6.484985ms
,2016-09-28 16:41:07.888 ThaliTest[3549:6231945] [CDVTimer][gesturehandler] 0.297964ms
,2016-09-28 16:41:07.889 ThaliTest[3549:6231945] [CDVTimer][TotalPluginStartup] 8.904994ms
,2016-09-28 16:41:14.452 ThaliTest[3549:6231945] Resetting plugins due to page load.
,2016-09-28 16:41:17.512 ThaliTest[3549:6231945] Finished load of: file:///var/mobile/Containers/Bundle/Application/5906F988-ED2B-408E-A254-ACD34E9355C4/ThaliTest.app/www/index.html
,2016-09-28 16:41:17.730 ThaliTest[3549:6231945] JXcore Cordova plugin initializing
,2016-09-28 16:41:17.730 ThaliTest[3549:6232186] JXcore instance initializing
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
,* thread #1: tid = 0x5f1789, 0x000000019abf1820 libobjc.A.dylib`<redacted> + 144, queue = 'com.apple.main-thread'
  * frame #0: 0x000000019abf1820 libobjc.A.dylib`<redacted> + 144
    frame #1: 0x000000019abf8510 libobjc.A.dylib`objc_storeWeakOrNil + 332
    frame #2: 0x0000000185f74cbc CoreFoundation`_NSObjectStoreWeak + 80
    frame #3: 0x0000000185efa7f8 CoreFoundation`<redacted> + 92
    frame #4: 0x0000000185fd3520 CoreFoundation`<redacted> + 372
    frame #5: 0x0000000185f78d9c CoreFoundation`<redacted> + 500
    frame #6: 0x0000000185e5c400 CoreFoundation`_CFXNotificationRegisterObserver + 1164
    frame #7: 0x0000000186dbf468 Foundation`<redacted> + 296
    frame #8: 0x0000000100884cc8 ThaliCore`ThaliCore.ApplicationStateNotificationsManager.__allocating_init () -> ThaliCore.ApplicationStateNotificationsManager + 228
    frame #9: 0x00000001000b0ab0 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 112
    frame #10: 0x00000001000ad628 ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #11: 0x00000001000b73f4 ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 56
    frame #12: 0x000000010099120c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #13: 0x00000001009c36ec XCTest`-[XCTestContext performInScope:] + 208
    frame #14: 0x0000000100991180 XCTest`-[XCTestCase invokeTest] + 164
    frame #15: 0x000000010099176c XCTest`-[XCTestCase performTest:] + 460
    frame #16: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #17: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #18: 0x000000010098f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #19: 0x000000010087d284 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #20: 0x000000010087d308 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #21: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #22: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #23: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #24: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #25: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #26: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #27: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #28: 0x00000001000a1d5c ThaliTest`main + 76
    frame #29: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
