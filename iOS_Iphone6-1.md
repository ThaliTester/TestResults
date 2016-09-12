#### Test 84265062d118465_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/633D1596-3051-4788-9A24-B38876ABD539/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/633D1596-3051-4788-9A24-B38876ABD539/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/31F80911-ACC7-4DB0-8A22-1B24EE208264/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50587"
,(lldb)     command script import "/tmp/633D1596-3051-4788-9A24-B38876ABD539/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
,(lldb)     autoexit
,2016-09-12 18:12:20.493 ThaliTest[414:498816] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/72DC9C05-694C-4541-9B5D-15128C8B2A79/Library/Cookies/Cookies.binarycookies
,2016-09-12 18:12:20.587 ThaliTest[414:498816] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 18:12:20.589 ThaliTest[414:498816] Multi-tasking -> Device: YES, App: YES
,2016-09-12 18:12:20.610 ThaliTest[414:498816] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 18:12:21.254 ThaliTest[414:498816] Using UIWebView
2016-09-12 18:12:21.259 ThaliTest[414:498816] [CDVTimer][handleopenurl] 0.202000ms
2016-09-12 18:12:21.264 ThaliTest[414:498816] [CDVTimer][intentandnavigationfilter] 4.975975ms
2016-09-12 18,:12:21.265 ThaliTest[414:498816] [CDVTimer][gesturehandler] 0.200987ms
2016-09-12 18:12:21.265 ThaliTest[414:498816] [CDVTimer][TotalPluginStartup] 6.339014ms
,2016-09-12 18:12:26.968 ThaliTest[414:498816] Resetting plugins due to page load.
,2016-09-12 18:12:27.444 ThaliTest[414:498816] Finished load of: file:///var/containers/Bundle/Application/31F80911-ACC7-4DB0-8A22-1B24EE208264/ThaliTest.app/www/index.html
,2016-09-12 18:12:27.837 ThaliTest[414:498816] JXcore Cordova plugin initializing
,2016-09-12 18:12:27.837 ThaliTest[414:498986] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,* thread #1: tid = 0x79c80, 0x00000001832b1dc8 libobjc.A.dylib`<redacted> + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x00000001832b1dc8 libobjc.A.dylib`<redacted> + 8
    frame #1: 0x00000001832a791c libobjc.A.dylib`<redacted> + 284
    frame #2: 0x00000001832b1d78 libobjc.A.dylib`<redacted> + 56
    frame #3: 0x0000000100925224 XCTest`-[XCTestObservationCenter _testCaseDidStop:] + 140
    frame #4: 0x00000001009147a0 XCTest`-[XCTestCaseRun stop] + 84
    frame #5: 0x0000000100919848 XCTest`-[XCTestCase performTest:] + 680
    frame #6: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #7: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #8: 0x00000001009171d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #9: 0x000000018461002c Foundation`<redacted> + 340
    frame #10: 0x0000000183bf109c CoreFoundation`<redacted> + 24
    frame #11: 0x0000000183bf0b30 CoreFoundation`<redacted> + 540
    frame #12: 0x0000000183bee830 CoreFoundation`<redacted> + 724
    frame #13: 0x0000000183b18c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #14: 0x0000000185400088 GraphicsServices`GSEventRunModal + 180
    frame #15: 0x0000000188e06088 UIKit`UIApplicationMain + 204
    frame #16: 0x00000001000d21a4 ThaliTest`main + 76
    frame #17: 0x00000001836b68b8 libdyld.dylib`<redacted> + 4

```
