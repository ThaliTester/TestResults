#### Test 1022710398c29c0f_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0F4D56F6-7CBC-4DD2-9D41-4FE350A093CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0F4D56F6-7CBC-4DD2-9D41-4FE350A093CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7C7FB911-224D-4AAC-AC81-CA8E07A29D86/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55813"
,(lldb)     command script import "/tmp/0F4D56F6-7CBC-4DD2-9D41-4FE350A093CE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-20 13:56:00.289 ThaliTest[2529:6476764] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5E9753A2-5451-43B0-9945-89A82F7458A7/Library/Cookies/Cookies.binarycookies
,2017-01-20 13:56:00.514 ThaliTest[2529:6476764] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-20 13:56:00.515 ThaliTest[2529:6476764] Multi-tasking -> Device: YES, App: YES
,2017-01-20 13:56:00.528 ThaliTest[2529:6476764] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-20 13:56:01.318 ThaliTest[2529:6476764] Using UIWebView
,2017-01-20 13:56:01.320 ThaliTest[2529:6476764] [CDVTimer][handleopenurl] 0.109971ms
,2017-01-20 13:56:01.322 ThaliTest[2529:6476764] [CDVTimer][intentandnavigationfilter] 1.836002ms
2017-01-20 13:56:01.322 ThaliTest[2529:6476764] [CDVTimer][gesturehandler] 0.082016ms
2017-01-20 13:56:01.322 ThaliTest[2529:6476764] [CDVTimer][TotalPluginS,tartup] 2.480984ms
,2017-01-20 13:56:04.424 ThaliTest[2529:6476764] Resetting plugins due to page load.
,2017-01-20 13:56:05.864 ThaliTest[2529:6476764] Finished load of: file:///var/mobile/Containers/Bundle/Application/7C7FB911-224D-4AAC-AC81-CA8E07A29D86/ThaliTest.app/www/index.html
,2017-01-20 13:56:06.003 ThaliTest[2529:6476764] JXcore Cordova plugin initializing
,2017-01-20 13:56:06.004 ThaliTest[2529:6476943] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-20 12:56:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-20 12:56:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-20 12:56:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-20 12:56:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-20 12:56:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 2529 stopped
* thread #15: tid = 0x62d57e, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x12978390)
    frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x198955bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x198955bd4 <+20>: and    w12, w1, w11
    0x198955bd8 <+24>: add    x12, x10, x12, lsl #4
    0x198955bdc <+28>: ldp    x16, x17, [x12]
,* thread #15: tid = 0x62d57e, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x12978390)
  * frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000184b26f70 Foundation`<redacted> + 68
    frame #2: 0x00000001000671c4 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x0000000100063b80 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
    frame #4: 0x000000018394cee0 CoreBluetooth`<redacted> + 60
    frame #5: 0x00000001991556e8 libdispatch.dylib`<redacted> + 24
    frame #6: 0x00000001991556a8 libdispatch.dylib`<redacted> + 16
    frame #7: 0x00000001991616ec libdispatch.dylib`<redacted> + 864
    frame #8: 0x00000001991591ac libdispatch.dylib`<redacted> + 464
    frame #9: 0x00000001991635bc libdispatch.dylib`<redacted> + 728
    frame #10: 0x00000001991632dc libdispatch.dylib`<redacted> + 112
    frame #11: 0x0000000199375470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #12: 0x0000000199375020 libsystem_pthread.dylib`start_wqthread + 4

```
