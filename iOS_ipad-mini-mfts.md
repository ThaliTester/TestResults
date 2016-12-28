#### Test 994652477e4ad1f_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BDFB023D-C378-4912-AF89-114728F2CB0A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/BDFB023D-C378-4912-AF89-114728F2CB0A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D6C0DC2C-849B-4FA8-A5FE-EA70A7B6FCB8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62684"
,(lldb)     command script import "/tmp/BDFB023D-C378-4912-AF89-114728F2CB0A/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 15:21:08.667 ThaliTest[1075:3200594] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1AB391D4-B448-458E-8E06-3EC6BF6352C5/Library/Cookies/Cookies.binarycookies
,2016-12-28 15:21:08.802 ThaliTest[1075:3200594] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 15:21:08.805 ThaliTest[1075:3200594] Multi-tasking -> Device: YES, App: YES
,2016-12-28 15:21:08.828 ThaliTest[1075:3200594] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 15:21:09.459 ThaliTest[1075:3200594] Using UIWebView
,2016-12-28 15:21:09.465 ThaliTest[1075:3200594] [CDVTimer][handleopenurl] 0.566006ms
,2016-12-28 15:21:09.473 ThaliTest[1075:3200594] [CDVTimer][intentandnavigationfilter] 7.117987ms
2016-12-28 15:21:09.474 ThaliTest[1075:3200594] [CDVTimer][gesturehandler] 0.364006ms
2016-12-28 15:21:09.474 ThaliTest[1075:3200594] [CDVTimer][TotalPluginS,tartup] 9.419978ms
,2016-12-28 15:21:18.158 ThaliTest[1075:3200594] Resetting plugins due to page load.
,2016-12-28 15:21:18.847 ThaliTest[1075:3200594] Finished load of: file:///var/containers/Bundle/Application/D6C0DC2C-849B-4FA8-A5FE-EA70A7B6FCB8/ThaliTest.app/www/index.html
,2016-12-28 15:21:19.088 ThaliTest[1075:3200594] JXcore Cordova plugin initializing
,2016-12-28 15:21:19.090 ThaliTest[1075:3200777] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 14:21:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 14:21:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 14:21:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-28 14:21:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 14:21:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0x30d652, 0x243bd706 libsystem_platform.dylib`<redacted> + 34, queue = 'com.apple.main-thread'
  * frame #0: 0x243bd706 libsystem_platform.dylib`<redacted> + 34
    frame #1: 0x23e44fae libobjc.A.dylib`<redacted> + 42
    frame #2: 0x23e33dee libobjc.A.dylib`objc_destructInstance + 50
    frame #3: 0x23e33e02 libobjc.A.dylib`object_dispose + 14
    frame #4: 0x23e44f66 libobjc.A.dylib`<redacted> + 150
    frame #5: 0x00a0f10c XCTest`-[XCUIElementAsynchronousHandlerWrapper dealloc] + 40
    frame #6: 0x23e44f66 libobjc.A.dylib`<redacted> + 150
    frame #7: 0x245a6d98 CoreFoundation`<redacted> + 148
    frame #8: 0x23e44f66 libobjc.A.dylib`<redacted> + 150
    frame #9: 0x23e453a8 libobjc.A.dylib`<redacted> + 388
    frame #10: 0x009dda6e XCTest`-[XCTestCase performTest:] + 598
    frame #11: 0x009db374 XCTest`-[XCTestSuite performTest:] + 460
    frame #12: 0x009db374 XCTest`-[XCTestSuite performTest:] + 460
    frame #13: 0x009db374 XCTest`-[XCTestSuite performTest:] + 460
    frame #14: 0x0084d90c ThaliCore`ThaliCore.TestRunner.runTest () -> () + 196
    frame #15: 0x0084d9b0 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 24
    frame #16: 0x24eb96de Foundation`<redacted> + 386
    frame #17: 0x24651dfe CoreFoundation`<redacted> + 14
    frame #18: 0x246519ec CoreFoundation`<redacted> + 452
    frame #19: 0x2464fd5a CoreFoundation`<redacted> + 794
    frame #20: 0x2459f228 CoreFoundation`CFRunLoopRunSpecific + 520
    frame #21: 0x2459f014 CoreFoundation`CFRunLoopRunInMode + 108
    frame #22: 0x25b8fac8 GraphicsServices`GSEventRunModal + 160
    frame #23: 0x28c73188 UIKit`UIApplicationMain + 144
    frame #24: 0x000be7e2 ThaliTest`main + 50
    frame #25: 0x24247872 libdyld.dylib`<redacted> + 2

```
