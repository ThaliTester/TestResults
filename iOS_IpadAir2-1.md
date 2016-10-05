#### Test 88123934d30a103_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88123934d30a103/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2B5C8437-5E52-4645-9B70-6E58431D02C8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2B5C8437-5E52-4645-9B70-6E58431D02C8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88123934d30a103/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88123934d30a103/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F320B9CA-9002-4C34-99D2-8B48F93267DB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61367"
,(lldb)     command script import "/tmp/2B5C8437-5E52-4645-9B70-6E58431D02C8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-05 20:03:01.802 ThaliTest[3847:7104725] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C90E9737-C87F-480B-BD87-C4BE2FB8772C/Library/Cookies/Cookies.binarycookies
,2016-10-05 20:03:02.197 ThaliTest[3847:7104725] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-05 20:03:02.199 ThaliTest[3847:7104725] Multi-tasking -> Device: YES, App: YES
,2016-10-05 20:03:02.219 ThaliTest[3847:7104725] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-05 20:03:04.227 ThaliTest[3847:7104725] Using UIWebView
,2016-10-05 20:03:04.234 ThaliTest[3847:7104725] [CDVTimer][handleopenurl] 0.340998ms
,2016-10-05 20:03:04.241 ThaliTest[3847:7104725] [CDVTimer][intentandnavigationfilter] 6.362975ms
,2016-10-05 20:03:04.242 ThaliTest[3847:7104725] [CDVTimer][gesturehandler] 0.297964ms
2016-10-05 20:03:04.242 ThaliTest[3847:7104725] [CDVTimer][TotalPluginStartup] 8.565009ms
,2016-10-05 20:03:10.980 ThaliTest[3847:7104725] Resetting plugins due to page load.
,2016-10-05 20:03:14.015 ThaliTest[3847:7104725] Finished load of: file:///var/mobile/Containers/Bundle/Application/F320B9CA-9002-4C34-99D2-8B48F93267DB/ThaliTest.app/www/index.html
,2016-10-05 20:03:14.231 ThaliTest[3847:7104725] JXcore Cordova plugin initializing
,2016-10-05 20:03:14.232 ThaliTest[3847:7104973] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-05 18:03:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-05 18:03:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-05 18:03:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-05 18:03:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-05 18:03:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x12ef194a0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("54CB7540-E35E-4AF7-89C4-A2872CEB7971")
,nil
,nil
,Optional("988E4156-99A9-422C-879B-63A89CF5BE09")
,Optional("6A70C572-6A6E-4F08-9A04-3DB3B936CE42")
,Process 3847 stopped
* thread #16: tid = 0x6c6a03, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x19abf1bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x19abf1bd4 <+20>: and    w12, w1, w11
    0x19abf1bd8 <+24>: add    x12, x10, x12, lsl #4
    0x19abf1bdc <+28>: ldp    x16, x17, [x12]
,* thread #16: tid = 0x6c6a03, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000186dc2f70 Foundation`<redacted> + 68
    frame #2: 0x000000010008201c ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x000000010007e2f8 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
    frame #4: 0x0000000185be8ee0 CoreBluetooth`<redacted> + 60
    frame #5: 0x000000019b3f16e8 libdispatch.dylib`<redacted> + 24
    frame #6: 0x000000019b3f16a8 libdispatch.dylib`<redacted> + 16
    frame #7: 0x000000019b3fd6ec libdispatch.dylib`<redacted> + 864
    frame #8: 0x000000019b3f51ac libdispatch.dylib`<redacted> + 464
    frame #9: 0x000000019b3ff5bc libdispatch.dylib`<redacted> + 728
    frame #10: 0x000000019b3ff2dc libdispatch.dylib`<redacted> + 112
    frame #11: 0x000000019b611470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #12: 0x000000019b611020 libsystem_pthread.dylib`start_wqthread + 4

```
