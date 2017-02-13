#### Test 1027067425e01561_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F91F04FC-7727-461C-8D6C-1BE076F237B3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F91F04FC-7727-461C-8D6C-1BE076F237B3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067425e01561/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/810FF582-3742-45CA-9720-9F1E7EA7EF99/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50039"
,(lldb)     command script import "/tmp/F91F04FC-7727-461C-8D6C-1BE076F237B3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-13 15:48:59.021 ThaliTest[3593:10394862] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A09740DD-61BF-4D5B-A81D-9B79E61A3D33/Library/Cookies/Cookies.binarycookies
,2017-02-13 15:48:59.405 ThaliTest[3593:10394862] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-13 15:48:59.406 ThaliTest[3593:10394862] Multi-tasking -> Device: YES, App: YES
,2017-02-13 15:48:59.426 ThaliTest[3593:10394862] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-13 15:49:01.594 ThaliTest[3593:10394862] Using UIWebView
,2017-02-13 15:49:01.611 ThaliTest[3593:10394862] [CDVTimer][handleopenurl] 0.340998ms
,2017-02-13 15:49:01.618 ThaliTest[3593:10394862] [CDVTimer][intentandnavigationfilter] 6.578028ms
,2017-02-13 15:49:01.619 ThaliTest[3593:10394862] [CDVTimer][gesturehandler] 0.284970ms
,2017-02-13 15:49:01.619 ThaliTest[3593:10394862] [CDVTimer][TotalPluginStartup] 9.018004ms
,2017-02-13 15:49:08.738 ThaliTest[3593:10394862] Resetting plugins due to page load.
,2017-02-13 15:49:12.230 ThaliTest[3593:10394862] Finished load of: file:///var/mobile/Containers/Bundle/Application/810FF582-3742-45CA-9720-9F1E7EA7EF99/ThaliTest.app/www/index.html
,2017-02-13 15:49:12.443 ThaliTest[3593:10394862] JXcore Cordova plugin initializing
2017-02-13 15:49:12.443 ThaliTest[3593:10395128] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-13 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Process 3593 stopped
* thread #15: tid = 0x9e9e21, 0x0000000183bb3a98 CoreFoundation`CFArrayGetValueAtIndex + 44, queue = 'com.apple.MCSession.callbackQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x0)
    frame #0: 0x0000000183bb3a98 CoreFoundation`CFArrayGetValueAtIndex + 44
CoreFoundation`CFArrayGetValueAtIndex:
->  0x183bb3a98 <+44>: ldr    x8, [x20]
    0x183bb3a9c <+48>: cbz    x8, 0x183bb3af4           ; <+136>
    0x183bb3aa0 <+52>: adrp   x9, 114605
    0x183bb3aa4 <+56>: add    x9, x9, #8                ; =8 
,* thread #15: tid = 0x9e9e21, 0x0000000183bb3a98 CoreFoundation`CFArrayGetValueAtIndex + 44, queue = 'com.apple.MCSession.callbackQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x0)
  * frame #0: 0x0000000183bb3a98 CoreFoundation`CFArrayGetValueAtIndex + 44
    frame #1: 0x0000000183c310dc CoreFoundation`<redacted> + 172
    frame #2: 0x0000000183bdbe78 CoreFoundation`<redacted> + 240
    frame #3: 0x0000000183bcbf04 CoreFoundation`<redacted> + 124
    frame #4: 0x0000000183bdbd64 CoreFoundation`CFReadStreamOpen + 120
    frame #5: 0x00000001008a0a54 ThaliCore`ThaliCore.VirtualSocket.openStreams () -> () + 308
    frame #6: 0x00000001008718cc ThaliCore`ThaliCore.AdvertiserRelay.((sessionDidReceiveInputStreamHandler in _DB3503884CE3B5744EF825043FAE73DC) (__ObjC.NSInputStream, inputStreamName : Swift.String) -> ()).(closure #1).(closure #1) + 488
    frame #7: 0x000000010085d758 ThaliCore`ThaliCore.TCPClient.connectToLocalhost (onPort : Swift.UInt16, completion : (socket : Swift.Optional<__ObjC.GCDAsyncSocket>, port : Swift.Optional<Swift.UInt16>, error : Swift.Optional<Swift.ErrorType>) -> ()) -> () + 228
    frame #8: 0x0000000100871698 ThaliCore`ThaliCore.AdvertiserRelay.((sessionDidReceiveInputStreamHandler in _DB3503884CE3B5744EF825043FAE73DC) (__ObjC.NSInputStream, inputStreamName : Swift.String) -> ()).(closure #1) + 176
    frame #9: 0x0000000100847350 ThaliCore`ThaliCore.AdvertiserVirtualSocketBuilder.createVirtualSocket (with : __ObjC.NSInputStream, inputStreamName : Swift.String) -> () + 280
    frame #10: 0x0000000100870a7c ThaliCore`ThaliCore.AdvertiserRelay.(sessionDidReceiveInputStreamHandler in _DB3503884CE3B5744EF825043FAE73DC) (__ObjC.NSInputStream, inputStreamName : Swift.String) -> () + 236
    frame #11: 0x0000000100870cfc ThaliCore`partial apply forwarder for ThaliCore.AdvertiserRelay.(sessionDidReceiveInputStreamHandler in _DB3503884CE3B5744EF825043FAE73DC) (__ObjC.NSInputStream, inputStreamName : Swift.String) -> () + 20
    frame #12: 0x000000010085ba20 ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, didReceiveStream : __ObjC.NSInputStream, withName : Swift.String, fromPeer : __ObjC.MCPeerID) -> () + 236
    frame #13: 0x0000000186f38520 MultipeerConnectivity`<redacted> + 124
    frame #14: 0x00000001991556e8 libdispatch.dylib`<redacted> + 24
    frame #15: 0x00000001991556a8 libdispatch.dylib`<redacted> + 16
    frame #16: 0x00000001991616ec libdispatch.dylib`<redacted> + 864
    frame #17: 0x00000001991591ac libdispatch.dylib`<redacted> + 464
    frame #18: 0x00000001991635bc libdispatch.dylib`<redacted> + 728
    frame #19: 0x00000001991632dc libdispatch.dylib`<redacted> + 112
    frame #20: 0x0000000199375470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #21: 0x0000000199375020 libsystem_pthread.dylib`start_wqthread + 4

```
