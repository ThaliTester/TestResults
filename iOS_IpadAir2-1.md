#### Test 855258872e8b4bc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4418C3F7-7DB2-41F0-AEB1-07F55F001169/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4418C3F7-7DB2-41F0-AEB1-07F55F001169/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5C96054-3CB5-4F93-B645-121C38899469/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49657"
,(lldb)     command script import "/tmp/4418C3F7-7DB2-41F0-AEB1-07F55F001169/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 13:33:10.845 ThaliTest[3026:5442197] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/24799FBD-3CCC-4BA6-BBE4-CCD09799F785/Library/Cookies/Cookies.binarycookies
,2016-09-22 13:33:11.223 ThaliTest[3026:5442197] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 13:33:11.225 ThaliTest[3026:5442197] Multi-tasking -> Device: YES, App: YES
,2016-09-22 13:33:11.246 ThaliTest[3026:5442197] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 13:33:13.151 ThaliTest[3026:5442197] Using UIWebView
,2016-09-22 13:33:13.162 ThaliTest[3026:5442197] [CDVTimer][handleopenurl] 0.494003ms
,2016-09-22 13:33:13.170 ThaliTest[3026:5442197] [CDVTimer][intentandnavigationfilter] 7.425964ms
2016-09-22 13:33:13.171 ThaliTest[3026:5442197] [CDVTimer][gesturehandler] 0.349998ms
2016-09-22 13:33:13.171 ThaliTest[3026:5442197] [CDVTimer][TotalPluginStartup] 9.917974ms
,2016-09-22 13:33:19.888 ThaliTest[3026:5442197] Resetting plugins due to page load.
,2016-09-22 13:33:23.497 ThaliTest[3026:5442197] Finished load of: file:///var/mobile/Containers/Bundle/Application/F5C96054-3CB5-4F93-B645-121C38899469/ThaliTest.app/www/index.html
,2016-09-22 13:33:23.699 ThaliTest[3026:5442197] JXcore Cordova plugin initializing
2016-09-22 13:33:23.700 ThaliTest[3026:5442431] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Process 3026 stopped
* thread #3: tid = 0x530adf, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x19abf1bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x19abf1bd4 <+20>: and    w12, w1, w11
    0x19abf1bd8 <+24>: add    x12, x10, x12, lsl #4
    0x19abf1bdc <+28>: ldp    x16, x17, [x12]
,* thread #3: tid = 0x530adf, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000186dc2f70 Foundation`<redacted> + 68
    frame #2: 0x00000001000eca60 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x00000001000e9b14 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
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
