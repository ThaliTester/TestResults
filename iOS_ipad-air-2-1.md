#### Test 96918947801caae_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96918947801caae/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7B9272A5-3797-4B16-8471-AB8819D7E162/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7B9272A5-3797-4B16-8471-AB8819D7E162/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96918947801caae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96918947801caae/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/041E3F7F-D2E6-44D0-B23C-8B294143BD42/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58961"
,(lldb)     command script import "/tmp/7B9272A5-3797-4B16-8471-AB8819D7E162/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 13:03:26.873 ThaliTest[2568:6617329] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65703334-694C-420B-B28E-BEEA43F08854/Library/Cookies/Cookies.binarycookies
,2017-01-21 13:03:27.123 ThaliTest[2568:6617329] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-21 13:03:27.124 ThaliTest[2568:6617329] Multi-tasking -> Device: YES, App: YES
,2017-01-21 13:03:27.137 ThaliTest[2568:6617329] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-21 13:03:28.049 ThaliTest[2568:6617329] Using UIWebView
,2017-01-21 13:03:28.052 ThaliTest[2568:6617329] [CDVTimer][handleopenurl] 0.096977ms
,2017-01-21 13:03:28.054 ThaliTest[2568:6617329] [CDVTimer][intentandnavigationfilter] 1.796961ms
2017-01-21 13:03:28.054 ThaliTest[2568:6617329] [CDVTimer][gesturehandler] 0.079989ms
2017-01-21 13:03:28.054 ThaliTest[2568:6617329] [CDVTimer][TotalPluginS,tartup] 2.413034ms
,2017-01-21 13:03:31.256 ThaliTest[2568:6617329] Resetting plugins due to page load.
,2017-01-21 13:03:32.750 ThaliTest[2568:6617329] Finished load of: file:///var/mobile/Containers/Bundle/Application/041E3F7F-D2E6-44D0-B23C-8B294143BD42/ThaliTest.app/www/index.html
,2017-01-21 13:03:32.888 ThaliTest[2568:6617329] JXcore Cordova plugin initializing
2017-01-21 13:03:32.888 ThaliTest[2568:6617523] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-01-21 12:03:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 2568 stopped
* thread #15: tid = 0x64fa95, 0x000000019895c0b0 libobjc.A.dylib`objc_retain + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x20)
    frame #0: 0x000000019895c0b0 libobjc.A.dylib`objc_retain + 16
libobjc.A.dylib`objc_retain:
->  0x19895c0b0 <+16>: ldrb   w8, [x8, #32]
    0x19895c0b4 <+20>: tbnz   w8, #1, 0x19895c0d0       ; <+48>
    0x19895c0b8 <+24>: adrp   x8, 29171
    0x19895c0bc <+28>: add    x8, x8, #1000             ; =1000 
,* thread #15: tid = 0x64fa95, 0x000000019895c0b0 libobjc.A.dylib`objc_retain + 16, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BAD_ACCESS (code=1, address=0x20)
  * frame #0: 0x000000019895c0b0 libobjc.A.dylib`objc_retain + 16
    frame #1: 0x000000010005bb74 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 36
    frame #2: 0x000000018394cee0 CoreBluetooth`<redacted> + 60
    frame #3: 0x00000001991556e8 libdispatch.dylib`<redacted> + 24
    frame #4: 0x00000001991556a8 libdispatch.dylib`<redacted> + 16
    frame #5: 0x00000001991616ec libdispatch.dylib`<redacted> + 864
    frame #6: 0x00000001991591ac libdispatch.dylib`<redacted> + 464
    frame #7: 0x00000001991635bc libdispatch.dylib`<redacted> + 728
    frame #8: 0x00000001991632dc libdispatch.dylib`<redacted> + 112
    frame #9: 0x0000000199375470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #10: 0x0000000199375020 libsystem_pthread.dylib`start_wqthread + 4

```
