#### Test 8289468223f5822_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/558B3B81-0FFE-49B9-9090-41B2833935C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/558B3B81-0FFE-49B9-9090-41B2833935C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468223f5822/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EBD4D33F-60F7-4441-AE1F-606BB37DB170/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51885"
,(lldb)     command script import "/tmp/558B3B81-0FFE-49B9-9090-41B2833935C2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-29 15:09:55.722 ThaliTest[1280:2375607] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/09652B0B-87CF-4DE3-A4A3-3E2F6B9A9F5E/Library/Cookies/Cookies.binarycookies
,2016-08-29 15:09:56.153 ThaliTest[1280:2375607] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 15:09:56.154 ThaliTest[1280:2375607] Multi-tasking -> Device: YES, App: YES
,2016-08-29 15:09:56.173 ThaliTest[1280:2375607] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 15:09:58.041 ThaliTest[1280:2375607] Using UIWebView
,2016-08-29 15:09:58.051 ThaliTest[1280:2375607] [CDVTimer][handleopenurl] 0.544965ms
,2016-08-29 15:09:58.058 ThaliTest[1280:2375607] [CDVTimer][intentandnavigationfilter] 6.947041ms
,2016-08-29 15:09:58.059 ThaliTest[1280:2375607] [CDVTimer][gesturehandler] 0.311017ms
,2016-08-29 15:09:58.060 ThaliTest[1280:2375607] [CDVTimer][TotalPluginStartup] 9.725034ms
,2016-08-29 15:10:04.748 ThaliTest[1280:2375607] Resetting plugins due to page load.
,2016-08-29 15:10:08.221 ThaliTest[1280:2375607] Finished load of: file:///var/mobile/Containers/Bundle/Application/EBD4D33F-60F7-4441-AE1F-606BB37DB170/ThaliTest.app/www/index.html
,2016-08-29 15:10:08.446 ThaliTest[1280:2375607] JXcore Cordova plugin initializing
,2016-08-29 15:10:08.447 ThaliTest[1280:2375835] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,2016-08-29 15:10:08.624 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:08.626 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:08.626 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 15:10:09.628 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:09.629 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:09.629 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:10.630 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:10.631 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:10.631 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:11.632 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:11.633 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:11.633 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:12.633 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:12.634 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:12.634 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:13.635 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:13.636 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:13.636 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:14.637 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:14.641 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:14.641 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 15:10:15.995 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:15.998 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 15:10:15.999 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:17.000 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:17.002 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:17.003 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:18.004 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:18.006 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:18.007 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:19.009 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:19.011 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:19.011 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:20.013 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:20.015 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:20.016 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:21.017 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:21.019 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:21.020 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:22.021 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:22.024 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:22.024 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:23.026 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:23.028 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:23.028 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:24.030 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:24.032 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:24.033 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:25.035 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:25.037 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 15:10:25.037 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:27.077 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:27.080 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:27.080 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:28.082 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:28.084 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:28.085 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:29.086 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:29.089 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:29.089 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:30.091 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:30.093 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-29 15:10:30.093 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:31.095 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:31.097 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:31.098 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:32.099 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:32.101 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:32.102 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:33.104 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:33.106 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:33.106 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:34.108 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:34.110 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:34.110 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:35.112 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:35.114 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:35.114 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:36.116 ThaliTest[1280:2375607] BTM: attaching to BTServer
,2016-08-29 15:10:36.118 ThaliTest[1280:2375607] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 15:10:36.119 ThaliTest[1280:2375607] BTM: attemping to re-attach in 1 seconds
,2016-08-29 15:10:38.095 ThaliTest[1280:2375607] BTM: attaching to BTServer
,* thread #1: tid = 0x243fb7, 0x344500ec libsystem_kernel.dylib`syscall_thread_switch + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x344500ec libsystem_kernel.dylib`syscall_thread_switch + 8
    frame #1: 0x344ff4e6 libsystem_platform.dylib`<redacted> + 78
    frame #2: 0x3448d350 libsystem_malloc.dylib`<redacted> + 548
    frame #3: 0x2211d618 CoreFoundation`<redacted> + 11832
    frame #4: 0x2211a7c4 CoreFoundation`_CFStringCreateWithFormatAndArgumentsAux2 + 80
    frame #5: 0x22132ac8 CoreFoundation`_CFLogvEx2 + 96
    frame #6: 0x22132f1e CoreFoundation`_CFLogvEx3 + 118
    frame #7: 0x22f0d536 Foundation`<redacted> + 126
    frame #8: 0x22e5487c Foundation`NSLog + 28
    frame #9: 0x27e30fda BluetoothManager`<redacted> + 282
    frame #10: 0x2c839b10 MobileBluetooth`<redacted> + 36
    frame #11: 0x3436be2e libdispatch.dylib`<redacted> + 10
    frame #12: 0x3436be1a libdispatch.dylib`<redacted> + 22
    frame #13: 0x343706c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #14: 0x2210c534 CoreFoundation`<redacted> + 8
    frame #15: 0x2210aa2e CoreFoundation`<redacted> + 1590
    frame #16: 0x2205d0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #17: 0x2205cecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #18: 0x2b204af8 GraphicsServices`GSEventRunModal + 160
    frame #19: 0x262e62dc UIKit`UIApplicationMain + 144
    frame #20: 0x00034c82 ThaliTest`main + 50
    frame #21: 0x34394872 libdyld.dylib`<redacted> + 2

```
