#### Test 828946826174a68_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6190E21F-88E1-4845-9B77-7AFBBDFEB11F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6190E21F-88E1-4845-9B77-7AFBBDFEB11F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826174a68/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D2F3C7F-F7EC-43F8-988A-EA6E9F69A7AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57758"
,(lldb)     command script import "/tmp/6190E21F-88E1-4845-9B77-7AFBBDFEB11F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-30 17:06:52.696 ThaliTest[863:1158287] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/509E946B-0184-47B4-B584-4FD6161EB5DA/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:06:53.076 ThaliTest[863:1158287] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 17:06:53.077 ThaliTest[863:1158287] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:06:53.099 ThaliTest[863:1158287] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:06:54.807 ThaliTest[863:1158287] Using UIWebView
,2016-08-30 17:06:54.814 ThaliTest[863:1158287] [CDVTimer][handleopenurl] 0.569046ms
,2016-08-30 17:06:54.822 ThaliTest[863:1158287] [CDVTimer][intentandnavigationfilter] 7.237017ms
2016-08-30 17:06:54.822 ThaliTest[863:1158287] [CDVTimer][gesturehandler] 0.330985ms
2016-08-30 17:06:54.823 ThaliTest[863:1158287] [CDVTimer][TotalPluginStartup] 9.680986ms
,2016-08-30 17:07:00.526 ThaliTest[863:1158287] Resetting plugins due to page load.
,2016-08-30 17:07:03.480 ThaliTest[863:1158287] Finished load of: file:///var/mobile/Containers/Bundle/Application/1D2F3C7F-F7EC-43F8-988A-EA6E9F69A7AD/ThaliTest.app/www/index.html
,2016-08-30 17:07:03.709 ThaliTest[863:1158287] JXcore Cordova plugin initializing
,2016-08-30 17:07:03.710 ThaliTest[863:1158508] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-30 17:07:12.075 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:12.080 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:12.080 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:13.082 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:13.084 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:13.085 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:14.086 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:14.088 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:14.089 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:15.090 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:15.093 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:15.093 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:16.095 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:16.097 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:16.097 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:17.099 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:17.101 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:17.102 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:18.103 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:18.106 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:18.106 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:19.108 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:19.110 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:19.111 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:20.112 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:20.115 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:20.115 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:21.117 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:21.119 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:21.120 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:23.173 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:23.175 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:23.175 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:24.177 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:24.180 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:24.180 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:25.182 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:25.184 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:25.184 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:26.186 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:26.188 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:26.189 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:27.190 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:27.193 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:27.193 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:28.195 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:28.197 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:28.198 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:29.199 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:29.202 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:29.202 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:30.204 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:30.206 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:30.207 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:31.208 ThaliTest[863:1158287] BTM: attaching to BTServer
,2016-08-30 17:07:31.211 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:31.211 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:32.213 ThaliTest[863:1158287] BTM: attaching to BTServer
2016-08-30 17:07:32.215 ThaliTest[863:1158287] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-30 17:07:32.215 ThaliTest[863:1158287] BTM: attemping to re-attach in 1 seconds
,2016-08-30 17:07:34.191 ThaliTest[863:1158287] BTM: attaching to BTServer
,* thread #1: tid = 0x11ac8f, 0x3768c0ec libsystem_kernel.dylib`syscall_thread_switch + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x3768c0ec libsystem_kernel.dylib`syscall_thread_switch + 8
    frame #1: 0x3773b4e6 libsystem_platform.dylib`<redacted> + 78
    frame #2: 0x376c81dc libsystem_malloc.dylib`<redacted> + 512
    frame #3: 0x253649e4 CoreFoundation`CFRelease + 1268
    frame #4: 0x254183a6 CoreFoundation`<redacted> + 26
    frame #5: 0x2536469c CoreFoundation`CFRelease + 428
    frame #6: 0x253e86f0 CoreFoundation`<redacted> + 164
    frame #7: 0x2536469c CoreFoundation`CFRelease + 428
    frame #8: 0x254159ec CoreFoundation`<redacted> + 1524
    frame #9: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #10: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #11: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #12: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #13: 0x00037552 ThaliTest`main + 50
    frame #14: 0x375d0872 libdyld.dylib`<redacted> + 2

```
