#### Test 9965213169fe96d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/16AA4656-7E66-4918-ABA4-18CD357B1605/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/16AA4656-7E66-4918-ABA4-18CD357B1605/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B61EFE2-2DF4-45DA-B953-E1F441842EDF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63261"
,(lldb)     command script import "/tmp/16AA4656-7E66-4918-ABA4-18CD357B1605/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:37:43.484 ThaliTest[1630:3407863] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6C614EC9-2F9B-4652-992D-7620C966E991/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:37:43.835 ThaliTest[1630:3407863] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:37:43.836 ThaliTest[1630:3407863] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:37:43.855 ThaliTest[1630:3407863] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:37:45.802 ThaliTest[1630:3407863] Using UIWebView
,2016-12-29 14:37:45.809 ThaliTest[1630:3407863] [CDVTimer][handleopenurl] 0.339985ms
,2016-12-29 14:37:45.816 ThaliTest[1630:3407863] [CDVTimer][intentandnavigationfilter] 6.362021ms
,2016-12-29 14:37:45.817 ThaliTest[1630:3407863] [CDVTimer][gesturehandler] 0.258982ms
,2016-12-29 14:37:45.817 ThaliTest[1630:3407863] [CDVTimer][TotalPluginStartup] 8.450031ms
,2016-12-29 14:37:52.199 ThaliTest[1630:3407863] Resetting plugins due to page load.
,2016-12-29 14:37:55.153 ThaliTest[1630:3407863] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B61EFE2-2DF4-45DA-B953-E1F441842EDF/ThaliTest.app/www/index.html
,2016-12-29 14:37:55.423 ThaliTest[1630:3407863] JXcore Cordova plugin initializing
,2016-12-29 14:37:55.424 ThaliTest[1630:3408111] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 1630 stopped
* thread #16: tid = 0x3401cf, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x198955bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x198955bd4 <+20>: and    w12, w1, w11
    0x198955bd8 <+24>: add    x12, x10, x12, lsl #4
    0x198955bdc <+28>: ldp    x16, x17, [x12]
,* thread #16: tid = 0x3401cf, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000184b26f70 Foundation`<redacted> + 68
    frame #2: 0x00000001000e71c4 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x00000001000e3b80 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
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
