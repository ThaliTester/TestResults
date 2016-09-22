#### Test 8617437972ae596_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E31CD295-00AF-4332-8D41-44B1EFEA0962/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E31CD295-00AF-4332-8D41-44B1EFEA0962/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D401E4F-3084-4D63-B06F-147CB5D18DCB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56438"
,(lldb)     command script import "/tmp/E31CD295-00AF-4332-8D41-44B1EFEA0962/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:16:01.879 ThaliTest[2978:5419309] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DA31D13-B8F6-4A62-824D-D6D48B013FE6/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:16:02.201 ThaliTest[2978:5419309] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:16:02.202 ThaliTest[2978:5419309] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:16:02.217 ThaliTest[2978:5419309] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:16:03.894 ThaliTest[2978:5419309] Using UIWebView
,2016-09-22 10:16:03.900 ThaliTest[2978:5419309] [CDVTimer][handleopenurl] 0.367999ms
,2016-09-22 10:16:03.907 ThaliTest[2978:5419309] [CDVTimer][intentandnavigationfilter] 6.483018ms
,2016-09-22 10:16:03.908 ThaliTest[2978:5419309] [CDVTimer][gesturehandler] 0.284016ms
,2016-09-22 10:16:03.908 ThaliTest[2978:5419309] [CDVTimer][TotalPluginStartup] 8.668005ms
,2016-09-22 10:16:10.305 ThaliTest[2978:5419309] Resetting plugins due to page load.
,2016-09-22 10:16:13.387 ThaliTest[2978:5419309] Finished load of: file:///var/mobile/Containers/Bundle/Application/1D401E4F-3084-4D63-B06F-147CB5D18DCB/ThaliTest.app/www/index.html
,2016-09-22 10:16:13.588 ThaliTest[2978:5419309] JXcore Cordova plugin initializing
,2016-09-22 10:16:13.589 ThaliTest[2978:5419567] JXcore instance initializing
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
,* thread #1: tid = 0x52b12d, 0x0000000100c3ac38 libswiftCore.dylib`swift::MetadataCache<(anonymous namespace)::GenericCacheEntry>::findOrAdd(void const* const*, unsigned long, llvm::function_ref<(anonymous namespace)::GenericCacheEntry* ()>) + 268, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000100c3ac38 libswiftCore.dylib`swift::MetadataCache<(anonymous namespace)::GenericCacheEntry>::findOrAdd(void const* const*, unsigned long, llvm::function_ref<(anonymous namespace)::GenericCacheEntry* ()>) + 268
    frame #1: 0x0000000100c3adf0 libswiftCore.dylib`swift_getGenericMetadata1 + 96
    frame #2: 0x00000001008a96d0 ThaliCore`ThaliCore.Atomic.__allocating_init (A) -> ThaliCore.Atomic<A> + 32
    frame #3: 0x00000001008a511c ThaliCore`ThaliCore.SocketRelay.init (createSocketTimeout : Swift.Double) -> ThaliCore.SocketRelay<A> + 476
    frame #4: 0x000000010089c560 ThaliCore`ThaliCore.AdvertiserManager.__allocating_init (serviceType : Swift.String, disposeAdvertiserTimeout : Swift.Double, inputStreamReceiveTimeout : Swift.Double) -> ThaliCore.AdvertiserManager + 300
    frame #5: 0x00000001000d52d0 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 168
    frame #6: 0x00000001000d1f9c ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #7: 0x00000001000db40c ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 56
    frame #8: 0x000000010098520c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #9: 0x00000001009b76ec XCTest`-[XCTestContext performInScope:] + 208
    frame #10: 0x0000000100985180 XCTest`-[XCTestCase invokeTest] + 164
    frame #11: 0x000000010098576c XCTest`-[XCTestCase performTest:] + 460
    frame #12: 0x00000001009831d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #13: 0x00000001009831d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #14: 0x00000001009831d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #15: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #16: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #17: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #18: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #19: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #20: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #21: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #22: 0x00000001000c699c ThaliTest`main + 76
    frame #23: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
