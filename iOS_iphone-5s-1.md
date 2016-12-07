#### Test 953210620aa0610_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/53A9ED50-DE0D-4949-B091-92075AEA1CC1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/53A9ED50-DE0D-4949-B091-92075AEA1CC1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/26268944-B0B0-4B7D-8DEB-1E102CE25541/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54851"
,(lldb)     command script import "/tmp/53A9ED50-DE0D-4949-B091-92075AEA1CC1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:47:19.039 ThaliTest[423:295569] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F72A4CE8-9082-4404-95D2-0EF713670757/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:47:19.152 ThaliTest[423:295569] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:47:19.154 ThaliTest[423:295569] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:47:19.178 ThaliTest[423:295569] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:47:20.760 ThaliTest[423:295569] Using UIWebView
,2016-12-07 16:47:20.771 ThaliTest[423:295569] [CDVTimer][handleopenurl] 0.424027ms
,2016-12-07 16:47:20.783 ThaliTest[423:295569] [CDVTimer][intentandnavigationfilter] 11.000991ms
2016-12-07 16:47:20.784 ThaliTest[423:295569] [CDVTimer][gesturehandler] 0.395000ms
2016-12-07 16:47:20.784 ThaliTest[423:295569] [CDVTimer][TotalPluginStartu,p] 13.777971ms
,2016-12-07 16:47:27.292 ThaliTest[423:295569] Resetting plugins due to page load.
,2016-12-07 16:47:31.626 ThaliTest[423:295569] Finished load of: file:///var/mobile/Containers/Bundle/Application/26268944-B0B0-4B7D-8DEB-1E102CE25541/ThaliTest.app/www/index.html
,2016-12-07 16:47:31.940 ThaliTest[423:295569] JXcore Cordova plugin initializing
,2016-12-07 16:47:31.941 ThaliTest[423:295804] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:47:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:47:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:47:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 15:47:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:47:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0x48291, 0x000000019b42e5d0 libsystem_platform.dylib`_platform_memset + 176, queue = 'com.apple.main-thread'
  * frame #0: 0x000000019b42e5d0 libsystem_platform.dylib`_platform_memset + 176
    frame #1: 0x000000019b39a01c libsystem_malloc.dylib`<redacted> + 2924
    frame #2: 0x000000019b39d940 libsystem_malloc.dylib`malloc_zone_calloc + 124
    frame #3: 0x000000019b39d8a0 libsystem_malloc.dylib`calloc + 60
    frame #4: 0x000000019aa15b40 libobjc.A.dylib`<redacted> + 44
    frame #5: 0x000000019aa158a4 libobjc.A.dylib`<redacted> + 276
    frame #6: 0x000000019aa1c32c libobjc.A.dylib`objc_storeWeak + 332
    frame #7: 0x0000000185f3b540 CoreFoundation`<redacted> + 68
    frame #8: 0x0000000185ec816c CoreFoundation`<redacted> + 84
    frame #9: 0x0000000185eb35b0 CoreFoundation`<redacted> + 40
    frame #10: 0x0000000185f4cc98 CoreFoundation`<redacted> + 240
    frame #11: 0x0000000185e30400 CoreFoundation`_CFXNotificationRegisterObserver + 1164
    frame #12: 0x0000000186d93468 Foundation`<redacted> + 296
    frame #13: 0x00000001007f95e4 ThaliCore`ThaliCore.ApplicationStateNotificationsManager.__allocating_init () -> ThaliCore.ApplicationStateNotificationsManager + 228
    frame #14: 0x000000010002e550 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.init (serviceType : Swift.String) -> ThaliTest.AppContext + 112
    frame #15: 0x000000010002ad80 ThaliTest`ThaliTest.AppContext.__allocating_init (serviceType : Swift.String) -> ThaliTest.AppContext + 96
    frame #16: 0x0000000100035c5c ThaliTest`@objc ThaliTest.AppContextTests.setUp () -> () + 84
    frame #17: 0x000000010099920c XCTest`__24-[XCTestCase invokeTest]_block_invoke_2 + 120
    frame #18: 0x00000001009cb6ec XCTest`-[XCTestContext performInScope:] + 208
    frame #19: 0x0000000100999180 XCTest`-[XCTestCase invokeTest] + 164
    frame #20: 0x000000010099976c XCTest`-[XCTestCase performTest:] + 460
    frame #21: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #22: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #23: 0x00000001009971d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #24: 0x00000001007f1eb0 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #25: 0x00000001007f1f34 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #26: 0x0000000186e83e60 Foundation`<redacted> + 340
    frame #27: 0x0000000185ef8544 CoreFoundation`<redacted> + 24
    frame #28: 0x0000000185ef7fd8 CoreFoundation`<redacted> + 540
    frame #29: 0x0000000185ef5cd8 CoreFoundation`<redacted> + 724
    frame #30: 0x0000000185e24ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #31: 0x0000000191060088 GraphicsServices`GSEventRunModal + 180
    frame #32: 0x000000018b53cffc UIKit`UIApplicationMain + 204
    frame #33: 0x000000010001f860 ThaliTest`main + 76
    frame #34: 0x000000019b2528b8 libdyld.dylib`<redacted> + 4

```
