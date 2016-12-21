#### Test 9856377413b1ea0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/43FBE464-6988-4A47-ACEA-F0D35225F9C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/43FBE464-6988-4A47-ACEA-F0D35225F9C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7DBD507E-B17D-4D44-96F9-45F7A91C1478/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56751"
,(lldb)     command script import "/tmp/43FBE464-6988-4A47-ACEA-F0D35225F9C7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-21 15:41:59.599 ThaliTest[1169:2301296] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/57929EE1-05C1-45D2-A6E7-D7B6AC4F81D9/Library/Cookies/Cookies.binarycookies
,2016-12-21 15:41:59.715 ThaliTest[1169:2301296] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 15:41:59.716 ThaliTest[1169:2301296] Multi-tasking -> Device: YES, App: YES
,2016-12-21 15:41:59.740 ThaliTest[1169:2301296] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 15:42:01.041 ThaliTest[1169:2301296] Using UIWebView
,2016-12-21 15:42:01.050 ThaliTest[1169:2301296] [CDVTimer][handleopenurl] 0.460029ms
,2016-12-21 15:42:01.061 ThaliTest[1169:2301296] [CDVTimer][intentandnavigationfilter] 10.215044ms
2016-12-21 15:42:01.062 ThaliTest[1169:2301296] [CDVTimer][gesturehandler] 0.476003ms
2016-12-21 15:42:01.062 ThaliTest[1169:2301296] [CDVTimer][TotalPluginStartup] 13.077974ms
,2016-12-21 15:42:06.882 ThaliTest[1169:2301296] Resetting plugins due to page load.
,2016-12-21 15:42:10.283 ThaliTest[1169:2301296] Finished load of: file:///var/mobile/Containers/Bundle/Application/7DBD507E-B17D-4D44-96F9-45F7A91C1478/ThaliTest.app/www/index.html
,2016-12-21 15:42:10.582 ThaliTest[1169:2301296] JXcore Cordova plugin initializing
,2016-12-21 15:42:10.583 ThaliTest[1169:2301487] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 14:42:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 14:42:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 14:42:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-21 14:42:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 14:42:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 1169 stopped
* thread #15: tid = 0x231efd, 0x000000019aa15bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x000000019aa15bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x19aa15bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x19aa15bd4 <+20>: and    w12, w1, w11
    0x19aa15bd8 <+24>: add    x12, x10, x12, lsl #4
    0x19aa15bdc <+28>: ldp    x16, x17, [x12]
,* thread #15: tid = 0x231efd, 0x000000019aa15bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x000000019aa15bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000186d96f70 Foundation`<redacted> + 68
    frame #2: 0x00000001001131c4 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x000000010010fb80 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
    frame #4: 0x0000000185bbcee0 CoreBluetooth`<redacted> + 60
    frame #5: 0x000000019b2216e8 libdispatch.dylib`<redacted> + 24
    frame #6: 0x000000019b2216a8 libdispatch.dylib`<redacted> + 16
    frame #7: 0x000000019b22d6ec libdispatch.dylib`<redacted> + 864
    frame #8: 0x000000019b2251ac libdispatch.dylib`<redacted> + 464
    frame #9: 0x000000019b22f5bc libdispatch.dylib`<redacted> + 728
    frame #10: 0x000000019b22f2dc libdispatch.dylib`<redacted> + 112
    frame #11: 0x000000019b435470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #12: 0x000000019b435020 libsystem_pthread.dylib`start_wqthread + 4

```
