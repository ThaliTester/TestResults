#### Test 103282205679c014_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103282205679c014/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/625B52F5-B8B8-4982-854F-02E0AE7AF89C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/625B52F5-B8B8-4982-854F-02E0AE7AF89C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103282205679c014/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103282205679c014/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/65214B62-BF8B-4E8E-8765-CAF4DEC6543E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52176"
,(lldb)     command script import "/tmp/625B52F5-B8B8-4982-854F-02E0AE7AF89C/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-02 16:27:15.729 ThaliTest[1073:2815269] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3611EFB9-7235-40A6-8D85-E79D3F24D157/Library/Cookies/Cookies.binarycookies
,2017-02-02 16:27:15.785 ThaliTest[1073:2815269] Apache Cordova native platform version 4.3.1 is starting.
2017-02-02 16:27:15.786 ThaliTest[1073:2815269] Multi-tasking -> Device: YES, App: YES
,2017-02-02 16:27:15.801 ThaliTest[1073:2815269] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-02 16:27:16.118 ThaliTest[1073:2815269] Using UIWebView
,2017-02-02 16:27:16.122 ThaliTest[1073:2815269] [CDVTimer][handleopenurl] 0.307977ms
,2017-02-02 16:27:16.129 ThaliTest[1073:2815269] [CDVTimer][intentandnavigationfilter] 5.896032ms
2017-02-02 16:27:16.129 ThaliTest[1073:2815269] [CDVTimer][gesturehandler] 0.199020ms
2017-02-02 16:27:16.129 ThaliTest[1073:2815269] [CDVTimer][TotalPluginS,tartup] 7.583976ms
,2017-02-02 16:27:22.389 ThaliTest[1073:2815269] Resetting plugins due to page load.
,2017-02-02 16:27:22.767 ThaliTest[1073:2815269] Finished load of: file:///var/containers/Bundle/Application/65214B62-BF8B-4E8E-8765-CAF4DEC6543E/ThaliTest.app/www/index.html
,2017-02-02 16:27:23.240 ThaliTest[1073:2815269] JXcore Cordova plugin initializing
,2017-02-02 16:27:23.241 ThaliTest[1073:2815447] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-02 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Process 1073 stopped
* thread #16: tid = 0x2af627, 0x00000001810e0630 CoreFoundation`CFRunLoopAddSource + 100, stop reason = EXC_BAD_ACCESS (code=1, address=0x8)
    frame #0: 0x00000001810e0630 CoreFoundation`CFRunLoopAddSource + 100
CoreFoundation`CFRunLoopAddSource:
->  0x1810e0630 <+100>: ldrb   w8, [x21, #8]
    0x1810e0634 <+104>: tbz    w8, #3, 0x1810e07c0       ; <+500>
    0x1810e0638 <+108>: add    x19, x20, #16             ; =16 
    0x1810e063c <+112>: mov    x0, x19
,* thread #16: tid = 0x2af627, 0x00000001810e0630 CoreFoundation`CFRunLoopAddSource + 100, stop reason = EXC_BAD_ACCESS (code=1, address=0x8)
  * frame #0: 0x00000001810e0630 CoreFoundation`CFRunLoopAddSource + 100
    frame #1: 0x0000000181120f2c CoreFoundation`<redacted> + 176
    frame #2: 0x00000001811150b0 CoreFoundation`<redacted> + 1612
    frame #3: 0x00000001810cc320 CoreFoundation`CFReadStreamRead + 196
    frame #4: 0x00000001008bdf34 ThaliCore`ThaliCore.VirtualSocket.((handleEventOnInputStream in _298C6A8C9EC56D99DE30C0D2A7A5542F) (__C.NSStreamEvent) -> ()).(closure #1) + 136
    frame #5: 0x0000000180c114bc libdispatch.dylib`<redacted> + 24
    frame #6: 0x0000000180c1147c libdispatch.dylib`<redacted> + 16
    frame #7: 0x0000000180c1d4c0 libdispatch.dylib`<redacted> + 864
    frame #8: 0x0000000180c14f80 libdispatch.dylib`<redacted> + 464
    frame #9: 0x0000000180c1f390 libdispatch.dylib`<redacted> + 728
    frame #10: 0x0000000180c1f0b0 libdispatch.dylib`<redacted> + 112
    frame #11: 0x0000000180e29470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #12: 0x0000000180e29020 libsystem_pthread.dylib`start_wqthread + 4

```
