#### Test 8289468223f5822_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/74293CD3-B973-4A15-A5FB-308CC0C0CB06/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/74293CD3-B973-4A15-A5FB-308CC0C0CB06/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3DA4CFF2-349C-4C1A-90D3-4FA061F8E08D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51889"
,(lldb)     command script import "/tmp/74293CD3-B973-4A15-A5FB-308CC0C0CB06/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 15:09:54.243 ThaliTest[1175:2405686] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7EC808CF-7760-4E70-B782-B3A670A8A88E/Library/Cookies/Cookies.binarycookies
,2016-08-29 15:09:54.660 ThaliTest[1175:2405686] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 15:09:54.662 ThaliTest[1175:2405686] Multi-tasking -> Device: YES, App: YES
,2016-08-29 15:09:54.688 ThaliTest[1175:2405686] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 15:09:56.372 ThaliTest[1175:2405686] Using UIWebView
,2016-08-29 15:09:56.384 ThaliTest[1175:2405686] [CDVTimer][handleopenurl] 0.595987ms
,2016-08-29 15:09:56.393 ThaliTest[1175:2405686] [CDVTimer][intentandnavigationfilter] 8.526981ms
2016-08-29 15:09:56.394 ThaliTest[1175:2405686] [CDVTimer][gesturehandler] 0.406027ms
2016-08-29 15:09:56.395 ThaliTest[1175:2405686] [CDVTimer][TotalPluginS,tartup] 11.556983ms
,2016-08-29 15:10:02.028 ThaliTest[1175:2405686] Resetting plugins due to page load.
,2016-08-29 15:10:04.893 ThaliTest[1175:2405686] Finished load of: file:///var/mobile/Containers/Bundle/Application/3DA4CFF2-349C-4C1A-90D3-4FA061F8E08D/ThaliTest.app/www/index.html
,2016-08-29 15:10:05.152 ThaliTest[1175:2405686] JXcore Cordova plugin initializing
,2016-08-29 15:10:05.153 ThaliTest[1175:2405909] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,2016-08-29 15:10:05.304 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:05.306 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:05.306 ThaliTest[1175:2405686] BTM: attemping ,to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 15:10:06.308 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:06.309 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:06.309 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:07.310 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:07.311 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:07.311 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:08.313 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:08.314 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:08.314 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:09.315 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:09.316 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:09.316 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:10.317 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:10.319 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:10.319 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:11.320 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:11.321 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:11.321 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:12.323 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:12.324 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:12.324 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:13.325 ThaliTest[1175:2405686] BTM: attaching to BTServer
2016-08-29 15:10:13.326 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:13.326 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 15:10:14.736 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:14.741 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:14.742 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:15.744 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:15.746 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:15.746 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:16.748 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:16.751 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:16.751 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:17.753 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:17.755 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:17.756 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:18.757 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:18.760 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:18.760 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:19.762 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:19.765 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:19.765 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:20.767 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:20.769 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:20.770 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:21.771 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:21.774 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:21.775 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:22.776 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:22.779 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:22.780 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:23.781 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:23.784 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:23.784 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:25.833 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:25.836 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:25.836 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:26.838 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:26.841 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:26.841 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:27.843 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:27.845 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:27.846 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:28.848 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:28.850 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:28.851 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:29.852 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:29.855 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:29.855 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:30.857 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:30.860 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:30.860 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:31.862 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:31.865 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:31.865 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:32.867 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:32.870 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:32.870 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:33.872 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:33.874 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:33.875 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:34.877 ThaliTest[1175:2405686] BTM: attaching to BTServer
,2016-08-29 15:10:34.879 ThaliTest[1175:2405686] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:34.880 ThaliTest[1175:2405686] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:36.853 ThaliTest[1175:2405686] BTM: attaching to BTServer
,* thread #1: tid = 0x24b536, 0x37381428 libsystem_asl.dylib`asl_release + 60, queue = 'com.apple.main-thread'
  * frame #0: 0x37381428 libsystem_asl.dylib`asl_release + 60
    frame #1: 0x37373b34 libsystem_asl.dylib`<redacted> + 1264
    frame #2: 0x373735e4 libsystem_asl.dylib`asl_send + 8
    frame #3: 0x252a5da8 CoreFoundation`<redacted> + 584
    frame #4: 0x252a5b3c CoreFoundation`_CFLogvEx2 + 212
    frame #5: 0x252a5f1e CoreFoundation`_CFLogvEx3 + 118
    frame #6: 0x26080536 Foundation`<redacted> + 126
    frame #7: 0x25fc787c Foundation`NSLog + 28
    frame #8: 0x2afe0fda BluetoothManager`<redacted> + 282
    frame #9: 0x2fb3ab10 MobileBluetooth`<redacted> + 36
    frame #10: 0x3733fe2e libdispatch.dylib`<redacted> + 10
    frame #11: 0x3733fe1a libdispatch.dylib`<redacted> + 22
    frame #12: 0x373446c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #13: 0x2527f534 CoreFoundation`<redacted> + 8
    frame #14: 0x2527da2e CoreFoundation`<redacted> + 1590
    frame #15: 0x251d00d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #16: 0x251cfecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #17: 0x2e505af8 GraphicsServices`GSEventRunModal + 160
    frame #18: 0x294592dc UIKit`UIApplicationMain + 144
    frame #19: 0x000c8c82 ThaliTest`main + 50
    frame #20: 0x37368872 libdyld.dylib`<redacted> + 2

```
