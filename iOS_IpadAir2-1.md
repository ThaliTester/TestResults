#### Test 92300911d00ab7e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D6B5388E-DBA9-4465-B80D-62F5AE267BF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D6B5388E-DBA9-4465-B80D-62F5AE267BF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F62CC34-5EDE-4A7D-B327-319AB4959340/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60754"
,(lldb)     command script import "/tmp/D6B5388E-DBA9-4465-B80D-62F5AE267BF9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 09:57:20.235 ThaliTest[5058:10738562] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E488B2F-EEA7-431D-B976-EA5884A35F78/Library/Cookies/Cookies.binarycookies
,2016-11-04 09:57:20.600 ThaliTest[5058:10738562] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 09:57:20.602 ThaliTest[5058:10738562] Multi-tasking -> Device: YES, App: YES
,2016-11-04 09:57:20.622 ThaliTest[5058:10738562] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 09:57:22.659 ThaliTest[5058:10738562] Using UIWebView
,2016-11-04 09:57:22.668 ThaliTest[5058:10738562] [CDVTimer][handleopenurl] 0.331998ms
,2016-11-04 09:57:22.675 ThaliTest[5058:10738562] [CDVTimer][intentandnavigationfilter] 6.682038ms
,2016-11-04 09:57:22.676 ThaliTest[5058:10738562] [CDVTimer][gesturehandler] 0.297010ms
,2016-11-04 09:57:22.676 ThaliTest[5058:10738562] [CDVTimer][TotalPluginStartup] 8.893967ms
,2016-11-04 09:57:29.279 ThaliTest[5058:10738562] Resetting plugins due to page load.
,2016-11-04 09:57:32.316 ThaliTest[5058:10738562] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F62CC34-5EDE-4A7D-B327-319AB4959340/ThaliTest.app/www/index.html
,2016-11-04 09:57:32.540 ThaliTest[5058:10738562] JXcore Cordova plugin initializing
,2016-11-04 09:57:32.541 ThaliTest[5058:10738822] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 08:57:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 08:57:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 08:57:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-04 08:57:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 08:57:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,* thread #1: tid = 0xa3db82, 0x000000019b60a9dc libsystem_platform.dylib`<redacted> + 40, queue = 'com.apple.main-thread'
  * frame #0: 0x000000019b60a9dc libsystem_platform.dylib`<redacted> + 40
    frame #1: 0x000000019b577308 libsystem_malloc.dylib`<redacted> + 672
    frame #2: 0x0000000185e4cfc4 CoreFoundation`CFRelease + 1088
    frame #3: 0x0000000185e70a38 CoreFoundation`CFRunLoopAddObserver + 436
    frame #4: 0x0000000100a0d754 XCTest`-[XCTestCase performTest:] + 436
    frame #5: 0x0000000100a0b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #6: 0x0000000100a0b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #7: 0x0000000100a0b1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #8: 0x000000010086f09c ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #9: 0x000000010086f120 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #10: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #11: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #12: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #13: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #14: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #15: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #16: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #17: 0x000000010009f3cc ThaliTest`main + 76
    frame #18: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
