#### Test 9772710378c4b3e_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/8B65DE4C-B11D-4F3A-8A4F-2F082D6E6E77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8B65DE4C-B11D-4F3A-8A4F-2F082D6E6E77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C344346F-A699-42EF-A828-8F28AA2DEF41/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54418"
,(lldb)     command script import "/tmp/8B65DE4C-B11D-4F3A-8A4F-2F082D6E6E77/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 13:34:01.627 ThaliTest[683:796124] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4E76F3F0-8F4E-4D51-A1F0-F0D032B8855B/Library/Cookies/Cookies.binarycookies
,2016-12-13 13:34:01.694 ThaliTest[683:796124] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 13:34:01.695 ThaliTest[683:796124] Multi-tasking -> Device: YES, App: YES
,2016-12-13 13:34:01.716 ThaliTest[683:796124] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 13:34:02.035 ThaliTest[683:796124] Using UIWebView
2016-12-13 13:34:02.038 ThaliTest[683:796124] [CDVTimer][handleopenurl] 0.153005ms
,2016-12-13 13:34:02.045 ThaliTest[683:796124] [CDVTimer][intentandnavigationfilter] 5.829990ms
2016-12-13 13:34:02.045 ThaliTest[683:796124] [CDVTimer][gesturehandler] 0.163972ms
,2016-12-13 13:34:02.045 ThaliTest[683:796124] [CDVTimer][TotalPluginStartup] 6.927013ms
,2016-12-13 13:34:08.027 ThaliTest[683:796124] Resetting plugins due to page load.
,2016-12-13 13:34:08.442 ThaliTest[683:796124] Finished load of: file:///var/containers/Bundle/Application/C344346F-A699-42EF-A828-8F28AA2DEF41/ThaliTest.app/www/index.html
,2016-12-13 13:34:08.771 ThaliTest[683:796124] JXcore Cordova plugin initializing
,2016-12-13 13:34:08.772 ThaliTest[683:796309] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 12:34:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 12:34:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 12:34:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 12:34:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 12:34:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0xc25dc, 0x0000000182525e30 libobjc.A.dylib`<redacted> + 112, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000182525e30 libobjc.A.dylib`<redacted> + 112
    frame #1: 0x000000018251b840 libobjc.A.dylib`<redacted> + 64
    frame #2: 0x000000018251b7cc libobjc.A.dylib`<redacted> + 12
    frame #3: 0x0000000182513080 libobjc.A.dylib`<redacted> + 36
    frame #4: 0x000000018252e220 libobjc.A.dylib`<redacted> + 52
    frame #5: 0x0000000100a613b4 XCTest`-[XCTestObservationCenter _testCaseDidStop:] + 540
    frame #6: 0x0000000100a507a0 XCTest`-[XCTestCaseRun stop] + 84
    frame #7: 0x0000000100a55848 XCTest`-[XCTestCase performTest:] + 680
    frame #8: 0x0000000100a531d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x0000000100a531d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #10: 0x0000000100a531d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #11: 0x0000000100899eac ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #12: 0x0000000100899f30 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #13: 0x000000018388402c Foundation`<redacted> + 340
    frame #14: 0x0000000182e6509c CoreFoundation`<redacted> + 24
    frame #15: 0x0000000182e64b30 CoreFoundation`<redacted> + 540
    frame #16: 0x0000000182e62830 CoreFoundation`<redacted> + 724
    frame #17: 0x0000000182d8cc50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #18: 0x0000000184674088 GraphicsServices`GSEventRunModal + 180
    frame #19: 0x000000018807a088 UIKit`UIApplicationMain + 204
    frame #20: 0x00000001000cb860 ThaliTest`main + 76
    frame #21: 0x000000018292a8b8 libdyld.dylib`<redacted> + 4

```
