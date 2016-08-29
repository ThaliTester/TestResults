#### Test 8289468293e136b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D13F1DD2-A17C-412E-A2DF-C98384E0BBEC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D13F1DD2-A17C-412E-A2DF-C98384E0BBEC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A66D0378-6801-4F76-B5BF-4BA53939662C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59225"
,(lldb)     command script import "/tmp/D13F1DD2-A17C-412E-A2DF-C98384E0BBEC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:10:41.958 ThaliTest[1244:2361146] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/810506EB-C27B-4729-AF60-2F1E1C2DC183/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:10:42.359 ThaliTest[1244:2361146] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:10:42.360 ThaliTest[1244:2361146] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:10:42.381 ThaliTest[1244:2361146] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:10:44.221 ThaliTest[1244:2361146] Using UIWebView
,2016-08-29 13:10:44.228 ThaliTest[1244:2361146] [CDVTimer][handleopenurl] 0.447989ms
,2016-08-29 13:10:44.236 ThaliTest[1244:2361146] [CDVTimer][intentandnavigationfilter] 6.871998ms
,2016-08-29 13:10:44.237 ThaliTest[1244:2361146] [CDVTimer][gesturehandler] 0.344992ms
,2016-08-29 13:10:44.237 ThaliTest[1244:2361146] [CDVTimer][TotalPluginStartup] 9.416997ms
,2016-08-29 13:10:50.866 ThaliTest[1244:2361146] Resetting plugins due to page load.
,2016-08-29 13:10:54.487 ThaliTest[1244:2361146] Finished load of: file:///var/mobile/Containers/Bundle/Application/A66D0378-6801-4F76-B5BF-4BA53939662C/ThaliTest.app/www/index.html
,2016-08-29 13:10:54.697 ThaliTest[1244:2361146] JXcore Cordova plugin initializing
,2016-08-29 13:10:54.698 ThaliTest[1244:2361400] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-29 13:10:54.874 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:10:54.877 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:10:54.877 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 13:10:55.879 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:10:55.880 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:55.880 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:56.881 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:10:56.881 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:56.882 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:57.883 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:10:57.884 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:57.884 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:58.885 ThaliTest[1244:2361146] BTM: attaching to BTServer
2016-08-29 13:10:58.886 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:58.886 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:59.887 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:10:59.888 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:59.888 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:00.889 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:00.890 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:00.892 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 13:11:02.242 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:02.245 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:02.246 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:03.247 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:03.249 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:03.250 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:04.251 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:04.253 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:04.253 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:05.255 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:05.258 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:05.258 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:06.260 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:06.262 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:06.263 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:07.264 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:07.267 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:07.267 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:08.269 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:08.271 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:08.271 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:09.273 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:09.275 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:09.275 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:10.277 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:10.279 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:10.280 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:11.281 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:11.284 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:11.285 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:13.342 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:13.344 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:13.345 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:14.346 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:14.349 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:14.349 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:15.351 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:15.353 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:15.353 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:16.355 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:16.357 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:16.357 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:17.359 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:17.361 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:17.362 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:18.363 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:18.366 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:18.366 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:19.368 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:19.370 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:19.370 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:20.372 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:20.374 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 13:11:20.375 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:21.376 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:21.378 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:21.379 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:22.380 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:22.383 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:22.383 ThaliTest[1244:2361146] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:24.359 ThaliTest[1244:2361146] BTM: attaching to BTServer
,2016-08-29 13:11:24.362 ThaliTest[1244:2361146] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,* thread #1: tid = 0x24073a, 0x344fa124 libsystem_notify.dylib`_nc_table_find_64 + 28, queue = 'com.apple.main-thread'
  * frame #0: 0x344fa124 libsystem_notify.dylib`_nc_table_find_64 + 28
    frame #1: 0x344f7c82 libsystem_notify.dylib`<redacted> + 42
    frame #2: 0x344f8c40 libsystem_notify.dylib`notify_check + 96
    frame #3: 0x343b5cb8 libsystem_c.dylib`<redacted> + 20
    frame #4: 0x343b5b84 libsystem_c.dylib`<redacted> + 52
    frame #5: 0x343b58da libsystem_c.dylib`localtime_r + 30
    frame #6: 0x22132be0 CoreFoundation`<redacted> + 128
    frame #7: 0x22132b3c CoreFoundation`_CFLogvEx2 + 212
    frame #8: 0x22132f1e CoreFoundation`_CFLogvEx3 + 118
    frame #9: 0x22f0d536 Foundation`<redacted> + 126
    frame #10: 0x22e5487c Foundation`NSLog + 28
    frame #11: 0x27e2f0ea BluetoothManager`<redacted> + 54
    frame #12: 0x27e31074 BluetoothManager`<redacted> + 436
    frame #13: 0x2c839b10 MobileBluetooth`<redacted> + 36
    frame #14: 0x3436be2e libdispatch.dylib`<redacted> + 10
    frame #15: 0x3436be1a libdispatch.dylib`<redacted> + 22
    frame #16: 0x343706c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #17: 0x2210c534 CoreFoundation`<redacted> + 8
    frame #18: 0x2210aa2e CoreFoundation`<redacted> + 1590
    frame #19: 0x2205d0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #20: 0x2205cecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #21: 0x2b204af8 GraphicsServices`GSEventRunModal + 160
    frame #22: 0x262e62dc UIKit`UIApplicationMain + 144
    frame #23: 0x00104c82 ThaliTest`main + 50
    frame #24: 0x34394872 libdyld.dylib`<redacted> + 2

```
