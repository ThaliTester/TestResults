#### Test 96524298edd5c74_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/A956DAFA-F58B-42BF-9ED0-F98E0BF38DB8/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/A956DAFA-F58B-42BF-9ED0-F98E0BF38DB8/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9EDFACA0-D90C-4FE5-998E-4DEEF2A07F44/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60860"
,(lldb)     command script import "/tmp/A956DAFA-F58B-42BF-9ED0-F98E0BF38DB8/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:50:20.195 ThaliTest[279:161858] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77CBA375-88A7-4370-8328-4F10D4814D95/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:50:20.357 ThaliTest[279:161858] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:50:20.361 ThaliTest[279:161858] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:50:20.388 ThaliTest[279:161858] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:50:21.269 ThaliTest[279:161858] Using UIWebView
,2016-12-07 12:50:21.275 ThaliTest[279:161858] [CDVTimer][handleopenurl] 0.406027ms
,2016-12-07 12:50:21.283 ThaliTest[279:161858] [CDVTimer][intentandnavigationfilter] 7.264018ms
2016-12-07 12:50:21.283 ThaliTest[279:161858] [CDVTimer][gesturehandler] 0.332952ms
2016-12-07 12:50:21.284 ThaliTest[279:161858] [CDVTimer][TotalPluginStartup] 9.387016ms
,2016-12-07 12:50:32.280 ThaliTest[279:161858] Resetting plugins due to page load.
,2016-12-07 12:50:33.093 ThaliTest[279:161858] Finished load of: file:///var/containers/Bundle/Application/9EDFACA0-D90C-4FE5-998E-4DEEF2A07F44/ThaliTest.app/www/index.html
,2016-12-07 12:50:33.349 ThaliTest[279:161858] JXcore Cordova plugin initializing
,2016-12-07 12:50:33.351 ThaliTest[279:162055] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:51:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:51:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:51:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-07 11:51:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:51:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,Process 279 stopped
* thread #22: tid = 0x27b23, 0x23e37a66 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0xe000000c)
    frame #0: 0x23e37a66 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x23e37a66 <+6>:  .long  0xc00cf8b9                ; unknown opcode
    0x23e37a6a <+10>: .long  0x9008f8d9                ; unknown opcode
    0x23e37a6e <+14>: .long  0x0c01ea0c                ; unknown opcode
    0x23e37a72 <+18>: .long  0x09cceb09                ; unknown opcode
,* thread #22: tid = 0x27b23, 0x23e37a66 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0xe000000c)
  * frame #0: 0x23e37a66 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x24de2750 Foundation`<redacted> + 60
    frame #2: 0x23e44f66 libobjc.A.dylib`<redacted> + 150
    frame #3: 0x24de7112 Foundation`<redacted> + 30
    frame #4: 0x0009058c ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 256
    frame #5: 0x0008c7e0 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 44
    frame #6: 0x2979a9f2 CoreBluetooth`<redacted> + 62
    frame #7: 0x241fd822 libdispatch.dylib`<redacted> + 10
    frame #8: 0x2420a422 libdispatch.dylib`<redacted> + 1758
    frame #9: 0x24209a60 libdispatch.dylib`<redacted> + 284
    frame #10: 0x2420c15c libdispatch.dylib`<redacted> + 396
    frame #11: 0x2420bfcc libdispatch.dylib`<redacted> + 96
    frame #12: 0x243c1b28 libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #13: 0x243c1718 libsystem_pthread.dylib`start_wqthread + 8

```
