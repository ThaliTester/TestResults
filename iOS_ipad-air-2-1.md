#### Test 993933123c9286c_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A50A1C09-0A72-4F57-A470-45C6808FD27A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A50A1C09-0A72-4F57-A470-45C6808FD27A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7214A6B-7CF7-4AA7-9283-41E314C79071/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54776"
,(lldb)     command script import "/tmp/A50A1C09-0A72-4F57-A470-45C6808FD27A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 00:22:04.955 ThaliTest[1406:3008292] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/150375D7-9B9E-491C-AD4C-FC251912FB51/Library/Cookies/Cookies.binarycookies
,2016-12-27 00:22:05.289 ThaliTest[1406:3008292] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 00:22:05.290 ThaliTest[1406:3008292] Multi-tasking -> Device: YES, App: YES
,2016-12-27 00:22:05.307 ThaliTest[1406:3008292] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 00:22:07.328 ThaliTest[1406:3008292] Using UIWebView
,2016-12-27 00:22:07.335 ThaliTest[1406:3008292] [CDVTimer][handleopenurl] 0.429988ms
,2016-12-27 00:22:07.342 ThaliTest[1406:3008292] [CDVTimer][intentandnavigationfilter] 6.340981ms
,2016-12-27 00:22:07.342 ThaliTest[1406:3008292] [CDVTimer][gesturehandler] 0.313997ms
,2016-12-27 00:22:07.343 ThaliTest[1406:3008292] [CDVTimer][TotalPluginStartup] 8.651972ms
,2016-12-27 00:22:14.662 ThaliTest[1406:3008292] Resetting plugins due to page load.
,2016-12-27 00:22:18.301 ThaliTest[1406:3008292] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7214A6B-7CF7-4AA7-9283-41E314C79071/ThaliTest.app/www/index.html
,2016-12-27 00:22:18.571 ThaliTest[1406:3008292] JXcore Cordova plugin initializing
,2016-12-27 00:22:18.571 ThaliTest[1406:3008507] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 23:22:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 23:22:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 23:22:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 23:22:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 23:22:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 1406 stopped
* thread #17: tid = 0x2de8e7, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x13fa1c28)
    frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x198955bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x198955bd4 <+20>: and    w12, w1, w11
    0x198955bd8 <+24>: add    x12, x10, x12, lsl #4
    0x198955bdc <+28>: ldp    x16, x17, [x12]
,* thread #17: tid = 0x2de8e7, 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x13fa1c28)
  * frame #0: 0x0000000198955bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000184b26f70 Foundation`<redacted> + 68
    frame #2: 0x00000001000fb1c4 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x00000001000f7b80 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
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
