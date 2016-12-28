#### Test 99448283f49b3a7_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D2DBBBC5-7FAF-4A1B-99AD-3DBC65D12B0D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/D2DBBBC5-7FAF-4A1B-99AD-3DBC65D12B0D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/247C94F2-C4B4-4959-B4A0-B0554191D5BF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51143"
,(lldb)     command script import "/tmp/D2DBBBC5-7FAF-4A1B-99AD-3DBC65D12B0D/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 16:58:19.589 ThaliTest[1527:2698710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4881125-1C6C-4F8D-9E18-CA29BF67E951/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:58:19.630 ThaliTest[1527:2698710] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:58:19.631 ThaliTest[1527:2698710] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:58:19.647 ThaliTest[1527:2698710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:58:19.961 ThaliTest[1527:2698710] Using UIWebView
,2016-12-28 16:58:19.965 ThaliTest[1527:2698710] [CDVTimer][handleopenurl] 0.207007ms
,2016-12-28 16:58:19.969 ThaliTest[1527:2698710] [CDVTimer][intentandnavigationfilter] 4.373014ms
2016-12-28 16:58:19.970 ThaliTest[1527:2698710] [CDVTimer][gesturehandler] 0.147998ms
2016-12-28 16:58:19.970 ThaliTest[1527:2698710] [CDVTimer][TotalPluginS,tartup] 5.611956ms
,2016-12-28 16:58:25.711 ThaliTest[1527:2698710] Resetting plugins due to page load.
,2016-12-28 16:58:26.108 ThaliTest[1527:2698710] Finished load of: file:///var/containers/Bundle/Application/247C94F2-C4B4-4959-B4A0-B0554191D5BF/ThaliTest.app/www/index.html
,2016-12-28 16:58:26.450 ThaliTest[1527:2698710] JXcore Cordova plugin initializing
,2016-12-28 16:58:26.451 ThaliTest[1527:2698886] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:58:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:58:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:58:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-28 15:58:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:58:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0x292dd6, 0x0000000182dab9cc CoreFoundation`<redacted> + 4, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000182dab9cc CoreFoundation`<redacted> + 4
    frame #1: 0x0000000182dab9fc CoreFoundation`<redacted> + 20
    frame #2: 0x0000000182dac148 CoreFoundation`<redacted> + 64
    frame #3: 0x0000000182db0d64 CoreFoundation`<redacted> + 36
    frame #4: 0x0000000100a6d128 XCTest`-[XCTestCase invokeTest] + 76
    frame #5: 0x0000000100a6d76c XCTest`-[XCTestCase performTest:] + 460
    frame #6: 0x0000000100a6b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #7: 0x0000000100a6b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #8: 0x0000000100a6b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x00000001008c9eac ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #10: 0x00000001008c9f30 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #11: 0x000000018388402c Foundation`<redacted> + 340
    frame #12: 0x0000000182e6509c CoreFoundation`<redacted> + 24
    frame #13: 0x0000000182e64b30 CoreFoundation`<redacted> + 540
    frame #14: 0x0000000182e62830 CoreFoundation`<redacted> + 724
    frame #15: 0x0000000182d8cc50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #16: 0x0000000184674088 GraphicsServices`GSEventRunModal + 180
    frame #17: 0x000000018807a088 UIKit`UIApplicationMain + 204
    frame #18: 0x00000001000fb200 ThaliTest`main + 76
    frame #19: 0x000000018292a8b8 libdyld.dylib`<redacted> + 4

```
