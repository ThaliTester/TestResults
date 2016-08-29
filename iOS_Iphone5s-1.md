#### Test 8289468293e136b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B40B2198-D163-4AFA-B503-B7D7317A8CF6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B40B2198-D163-4AFA-B503-B7D7317A8CF6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD085229-170C-4F59-8001-63DB7497E374/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59257"
,(lldb)     command script import "/tmp/B40B2198-D163-4AFA-B503-B7D7317A8CF6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:10:40.518 ThaliTest[1142:2389071] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B591A442-75E7-45A4-85E5-D44E7A6B3FD1/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:10:40.948 ThaliTest[1142:2389071] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:10:40.949 ThaliTest[1142:2389071] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:10:40.974 ThaliTest[1142:2389071] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:10:42.655 ThaliTest[1142:2389071] Using UIWebView
,2016-08-29 13:10:42.665 ThaliTest[1142:2389071] [CDVTimer][handleopenurl] 0.505984ms
,2016-08-29 13:10:42.674 ThaliTest[1142:2389071] [CDVTimer][intentandnavigationfilter] 8.525968ms
2016-08-29 13:10:42.675 ThaliTest[1142:2389071] [CDVTimer][gesturehandler] 0.412047ms
2016-08-29 13:10:42.676 ThaliTest[1142:2389071] [CDVTimer][TotalPluginS,tartup] 11.362970ms
,2016-08-29 13:10:48.287 ThaliTest[1142:2389071] Resetting plugins due to page load.
,2016-08-29 13:10:51.067 ThaliTest[1142:2389071] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD085229-170C-4F59-8001-63DB7497E374/ThaliTest.app/www/index.html
,2016-08-29 13:10:51.082 ThaliTest[1142:2389071] JXcore Cordova plugin initializing
,2016-08-29 13:10:51.084 ThaliTest[1142:2389282] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-29 13:10:51.320 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:51.326 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:51.327 ThaliTest[1142:2389071] BTM: attemping ,to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 13:10:52.328 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:52.329 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:52.329 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:53.331 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:53.332 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:53.332 ThaliTest[1142:2389071] BTM: attemping ,to re-attach in 1 seconds
,2016-08-29 13:10:54.333 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:54.334 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:54.334 ThaliTest[1142:2389071] BTM: attemping ,to re-attach in 1 seconds
,2016-08-29 13:10:55.335 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:55.336 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:55.336 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:56.338 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:56.339 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:56.339 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:57.340 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:10:57.342 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:57.342 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:58.344 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:58.345 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:58.345 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:59.346 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:10:59.347 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:59.347 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 13:11:00.990 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:01.003 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:01.003 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:02.005 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:02.008 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:02.008 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:03.010 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:03.013 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:03.013 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:04.015 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:04.017 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:04.018 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:05.019 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:05.022 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:05.023 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:06.024 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:06.027 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:06.027 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:07.029 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:07.032 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:07.032 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:08.034 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:08.037 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:08.037 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:09.039 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:09.042 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:09.042 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:10.044 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:10.046 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:10.047 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:12.144 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:11:12.147 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:12.147 ThaliTest[1142:2389071] BTM: attemping ,to re-attach in 1 seconds
,2016-08-29 13:11:13.149 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:13.152 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:13.152 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:14.154 ThaliTest[1142:2389071] BTM: attaching to BTServer
2016-08-29 13:11:14.156 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:14.156 ThaliTest[1142:2389071] BTM: attemping ,to re-attach in 1 seconds
,2016-08-29 13:11:15.157 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:15.160 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:15.161 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:16.162 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:16.165 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:16.166 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:17.167 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:17.171 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:17.171 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:18.173 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:18.175 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:18.176 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:19.177 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:19.180 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:19.181 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:20.181 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:20.184 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:20.184 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:21.186 ThaliTest[1142:2389071] BTM: attaching to BTServer
,2016-08-29 13:11:21.189 ThaliTest[1142:2389071] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:21.189 ThaliTest[1142:2389071] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:23.166 ThaliTest[1142:2389071] BTM: attaching to BTServer
,* thread #1: tid = 0x24744f, 0x374240ec libsystem_kernel.dylib`syscall_thread_switch + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x374240ec libsystem_kernel.dylib`syscall_thread_switch + 8
    frame #1: 0x374d34e6 libsystem_platform.dylib`<redacted> + 78
    frame #2: 0x3745e8f8 libsystem_malloc.dylib`<redacted> + 60
    frame #3: 0x37461f38 libsystem_malloc.dylib`malloc_zone_calloc + 92
    frame #4: 0x37461eca libsystem_malloc.dylib`calloc + 50
    frame #5: 0x373727f0 libsystem_asl.dylib`<redacted> + 16
    frame #6: 0x3737ed4e libsystem_asl.dylib`<redacted> + 10
    frame #7: 0x373727be libsystem_asl.dylib`asl_new + 50
    frame #8: 0x252a5d38 CoreFoundation`<redacted> + 472
    frame #9: 0x252a5b3c CoreFoundation`_CFLogvEx2 + 212
    frame #10: 0x252a5f1e CoreFoundation`_CFLogvEx3 + 118
    frame #11: 0x26080536 Foundation`<redacted> + 126
    frame #12: 0x25fc787c Foundation`NSLog + 28
    frame #13: 0x2afe0fda BluetoothManager`<redacted> + 282
    frame #14: 0x2fb3ab10 MobileBluetooth`<redacted> + 36
    frame #15: 0x3733fe2e libdispatch.dylib`<redacted> + 10
    frame #16: 0x3733fe1a libdispatch.dylib`<redacted> + 22
    frame #17: 0x373446c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #18: 0x2527f534 CoreFoundation`<redacted> + 8
    frame #19: 0x2527da2e CoreFoundation`<redacted> + 1590
    frame #20: 0x251d00d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #21: 0x251cfecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #22: 0x2e505af8 GraphicsServices`GSEventRunModal + 160
    frame #23: 0x294592dc UIKit`UIApplicationMain + 144
    frame #24: 0x00074c82 ThaliTest`main + 50
    frame #25: 0x37368872 libdyld.dylib`<redacted> + 2

```
