#### Test 86482582e70b00a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C3A1D199-CB41-4456-8B50-6E3944358145/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C3A1D199-CB41-4456-8B50-6E3944358145/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D9B6CB4-01BB-4AEE-B7EF-79510D30C0BF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64637"
,(lldb)     command script import "/tmp/C3A1D199-CB41-4456-8B50-6E3944358145/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 12:32:27.593 ThaliTest[3243:6615112] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/95ED8801-7BD8-44D0-B79C-F43BE853D261/Library/Cookies/Cookies.binarycookies
,2016-09-26 12:32:27.707 ThaliTest[3243:6615112] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 12:32:27.708 ThaliTest[3243:6615112] Multi-tasking -> Device: YES, App: YES
,2016-09-26 12:32:27.730 ThaliTest[3243:6615112] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 12:32:29.318 ThaliTest[3243:6615112] Using UIWebView
,2016-09-26 12:32:29.329 ThaliTest[3243:6615112] [CDVTimer][handleopenurl] 0.474036ms
,2016-09-26 12:32:29.338 ThaliTest[3243:6615112] [CDVTimer][intentandnavigationfilter] 8.503020ms
2016-09-26 12:32:29.339 ThaliTest[3243:6615112] [CDVTimer][gesturehandler] 0.356972ms
2016-09-26 12:32:29.339 ThaliTest[3243:6615112] [CDVTimer][TotalPluginS,tartup] 11.219025ms
,2016-09-26 12:32:35.265 ThaliTest[3243:6615112] Resetting plugins due to page load.
,2016-09-26 12:32:38.846 ThaliTest[3243:6615112] Finished load of: file:///var/mobile/Containers/Bundle/Application/1D9B6CB4-01BB-4AEE-B7EF-79510D30C0BF/ThaliTest.app/www/index.html
,2016-09-26 12:32:39.148 ThaliTest[3243:6615112] JXcore Cordova plugin initializing
,2016-09-26 12:32:39.149 ThaliTest[3243:6615354] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Process 3243 stopped
* thread #10: tid = 0x64f0e8, 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x199549bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x199549bd4 <+20>: and    w12, w1, w11
    0x199549bd8 <+24>: add    x12, x10, x12, lsl #4
    0x199549bdc <+28>: ldp    x16, x17, [x12]
,* thread #10: tid = 0x64f0e8, 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x0000000199549bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x00000001858cae74 Foundation`<redacted> + 132
    frame #2: 0x00000001858cadb0 Foundation`<redacted> + 40
    frame #3: 0x00000001000deda8 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #4: 0x00000001000db340 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
    frame #5: 0x00000001846f0ee0 CoreBluetooth`<redacted> + 60
    frame #6: 0x0000000199d556e8 libdispatch.dylib`<redacted> + 24
    frame #7: 0x0000000199d556a8 libdispatch.dylib`<redacted> + 16
    frame #8: 0x0000000199d616ec libdispatch.dylib`<redacted> + 864
    frame #9: 0x0000000199d591ac libdispatch.dylib`<redacted> + 464
    frame #10: 0x0000000199d635bc libdispatch.dylib`<redacted> + 728
    frame #11: 0x0000000199d632dc libdispatch.dylib`<redacted> + 112
    frame #12: 0x0000000199f69470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #13: 0x0000000199f69020 libsystem_pthread.dylib`start_wqthread + 4

```
