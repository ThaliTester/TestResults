#### Test 850469118f5d139_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CEB87573-6BC5-4A64-A212-C3FE3965ED78/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CEB87573-6BC5-4A64-A212-C3FE3965ED78/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8C509E13-5E3F-4FE0-84C6-74D66DB0C3DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58031"
,(lldb)     command script import "/tmp/CEB87573-6BC5-4A64-A212-C3FE3965ED78/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 14:01:44.347 ThaliTest[1548:2385218] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE1C75F2-5085-4EBC-8E06-43D5479DB859/Library/Cookies/Cookies.binarycookies
,2016-09-27 14:01:44.406 ThaliTest[1548:2385218] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 14:01:44.408 ThaliTest[1548:2385218] Multi-tasking -> Device: YES, App: YES
,2016-09-27 14:01:44.423 ThaliTest[1548:2385218] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 14:01:44.837 ThaliTest[1548:2385218] Using UIWebView
,2016-09-27 14:01:44.844 ThaliTest[1548:2385218] [CDVTimer][handleopenurl] 0.371993ms
,2016-09-27 14:01:44.852 ThaliTest[1548:2385218] [CDVTimer][intentandnavigationfilter] 6.991982ms
2016-09-27 14:01:44.853 ThaliTest[1548:2385218] [CDVTimer][gesturehandler] 0.264943ms
2016-09-27 14:01:44.853 ThaliTest[1548:2385218] [CDVTimer][TotalPluginStartup] 9.262025ms
,2016-09-27 14:01:50.483 ThaliTest[1548:2385218] Resetting plugins due to page load.
,2016-09-27 14:01:50.828 ThaliTest[1548:2385218] Finished load of: file:///var/containers/Bundle/Application/8C509E13-5E3F-4FE0-84C6-74D66DB0C3DC/ThaliTest.app/www/index.html
,2016-09-27 14:01:51.155 ThaliTest[1548:2385218] JXcore Cordova plugin initializing
2016-09-27 14:01:51.156 ThaliTest[1548:2385383] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1261c6d60>
,Optional("E9D1FEEA-F522-4E3A-82B4-1CE0F8956AB4")
nil
,nil
,Optional("E06A4B47-6C3E-4827-881D-C9CED03354B1")
,Optional("83F97080-2913-42BE-92BA-1EB456D53E99")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,* thread #1: tid = 0x246542, 0x00000001832a7a40 libobjc.A.dylib`<redacted> + 56, queue = 'com.apple.main-thread', activity = 'Breadcrumb initiated activity', 11 messages
  * frame #0: 0x00000001832a7a40 libobjc.A.dylib`<redacted> + 56
    frame #1: 0x00000001832a7930 libobjc.A.dylib`<redacted> + 304
    frame #2: 0x00000001832b1d78 libobjc.A.dylib`<redacted> + 56
    frame #3: 0x000000010091f25c XCTest`-[XCTestSuite performTest:] + 524
    frame #4: 0x000000010091f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #5: 0x000000010091f1d0 XCTest`-[XCTestSuite performTest:] + 384
    frame #6: 0x0000000100844ac0 ThaliCore`ThaliCore.TestRunner.runTest () -> () + 164
    frame #7: 0x0000000100844b44 ThaliCore`@objc ThaliCore.TestRunner.runTest () -> () + 28
    frame #8: 0x000000018461002c Foundation`<redacted> + 340
    frame #9: 0x0000000183bf109c CoreFoundation`<redacted> + 24
    frame #10: 0x0000000183bf0b30 CoreFoundation`<redacted> + 540
    frame #11: 0x0000000183bee830 CoreFoundation`<redacted> + 724
    frame #12: 0x0000000183b18c50 CoreFoundation`CFRunLoopRunSpecific + 384
    frame #13: 0x0000000185400088 GraphicsServices`GSEventRunModal + 180
    frame #14: 0x0000000188e06088 UIKit`UIApplicationMain + 204
    frame #15: 0x000000010007b110 ThaliTest`main + 76
    frame #16: 0x00000001836b68b8 libdyld.dylib`<redacted> + 4

```
