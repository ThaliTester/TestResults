#### Test 871169237a0ab14_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0BD9A97E-35A5-45A7-9CD7-EDC572F183DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0BD9A97E-35A5-45A7-9CD7-EDC572F183DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2E5CF267-1F79-4D5A-AADB-127DC9A14056/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62468"
,(lldb)     command script import "/tmp/0BD9A97E-35A5-45A7-9CD7-EDC572F183DA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 13:42:13.062 ThaliTest[3620:6343506] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/94CFF368-A68B-43F6-9FEE-7B9A68391C12/Library/Cookies/Cookies.binarycookies
,2016-09-29 13:42:13.418 ThaliTest[3620:6343506] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 13:42:13.419 ThaliTest[3620:6343506] Multi-tasking -> Device: YES, App: YES
,2016-09-29 13:42:13.438 ThaliTest[3620:6343506] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 13:42:15.385 ThaliTest[3620:6343506] Using UIWebView
,2016-09-29 13:42:15.392 ThaliTest[3620:6343506] [CDVTimer][handleopenurl] 0.320017ms
,2016-09-29 13:42:15.399 ThaliTest[3620:6343506] [CDVTimer][intentandnavigationfilter] 6.715000ms
,2016-09-29 13:42:15.399 ThaliTest[3620:6343506] [CDVTimer][gesturehandler] 0.265002ms
,2016-09-29 13:42:15.400 ThaliTest[3620:6343506] [CDVTimer][TotalPluginStartup] 8.750975ms
,2016-09-29 13:42:21.787 ThaliTest[3620:6343506] Resetting plugins due to page load.
,2016-09-29 13:42:24.709 ThaliTest[3620:6343506] Finished load of: file:///var/mobile/Containers/Bundle/Application/2E5CF267-1F79-4D5A-AADB-127DC9A14056/ThaliTest.app/www/index.html
,2016-09-29 13:42:24.916 ThaliTest[3620:6343506] JXcore Cordova plugin initializing
,2016-09-29 13:42:24.917 ThaliTest[3620:6343763] JXcore instance initializing
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
,* thread #1: tid = 0x60cb52, 0x000000019abeae60 libobjc.A.dylib`<redacted> + 44, queue = 'com.apple.main-thread'
  * frame #0: 0x000000019abeae60 libobjc.A.dylib`<redacted> + 44
    frame #1: 0x000000019abe7a9c libobjc.A.dylib`<redacted> + 84
    frame #2: 0x000000019abe7970 libobjc.A.dylib`<redacted> + 304
    frame #3: 0x000000019abf1db8 libobjc.A.dylib`<redacted> + 56
    frame #4: 0x0000000100931224 XCTest`-[XCTestObservationCenter _testCaseDidStop:] + 140
    frame #5: 0x00000001009207a0 XCTest`-[XCTestCaseRun stop] + 84
    frame #6: 0x0000000100925848 XCTest`-[XCTestCase performTest:] + 680
    frame #7: 0x00000001009231d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #8: 0x00000001009231d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x00000001009231d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #10: 0x00000001008110c4 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #11: 0x0000000100811148 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #12: 0x0000000186eafe60 Foundation`<redacted> + 340
    frame #13: 0x0000000185f24544 CoreFoundation`<redacted> + 24
    frame #14: 0x0000000185f23fd8 CoreFoundation`<redacted> + 540
    frame #15: 0x0000000185f21cd8 CoreFoundation`<redacted> + 724
    frame #16: 0x0000000185e50ca0 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #17: 0x0000000190ed0088 GraphicsServices`GSEventRunModal + 180
    frame #18: 0x000000018b568ffc UIKit`UIApplicationMain + 204
    frame #19: 0x000000010002dd5c ThaliTest`main + 76
    frame #20: 0x000000019b4228b8 libdyld.dylib`<redacted> + 4

```
