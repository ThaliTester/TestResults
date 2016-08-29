#### Test 8289468293e136b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B0667264-7615-4B73-85AD-8E78548DC92C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B0667264-7615-4B73-85AD-8E78548DC92C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8289468293e136b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A15888B3-679D-4A09-A420-AC2BCA22553C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59240"
,(lldb)     command script import "/tmp/B0667264-7615-4B73-85AD-8E78548DC92C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:10:39.418 ThaliTest[727:984487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/07610A22-2565-4CC6-9294-6E869A406CEB/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:10:39.868 ThaliTest[727:984487] Apache Cordova native platform version 4.1.1 is starting.
2016-08-29 13:10:39.869 ThaliTest[727:984487] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:10:39.893 ThaliTest[727:984487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:10:41.621 ThaliTest[727:984487] Using UIWebView
,2016-08-29 13:10:41.628 ThaliTest[727:984487] [CDVTimer][handleopenurl] 0.488997ms
,2016-08-29 13:10:41.636 ThaliTest[727:984487] [CDVTimer][intentandnavigationfilter] 7.480025ms
2016-08-29 13:10:41.637 ThaliTest[727:984487] [CDVTimer][gesturehandler] 0.378013ms
2016-08-29 13:10:41.637 ThaliTest[727:984487] [CDVTimer][TotalPluginStartup] 10.024011ms
,2016-08-29 13:10:47.748 ThaliTest[727:984487] Resetting plugins due to page load.
,2016-08-29 13:10:50.559 ThaliTest[727:984487] Finished load of: file:///var/mobile/Containers/Bundle/Application/A15888B3-679D-4A09-A420-AC2BCA22553C/ThaliTest.app/www/index.html
,2016-08-29 13:10:50.786 ThaliTest[727:984487] JXcore Cordova plugin initializing
,2016-08-29 13:10:50.787 ThaliTest[727:984721] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-29 13:10:50.941 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:50.943 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:50.944 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 13:10:51.945 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:51.946 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:51.946 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:52.946 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:10:52.947 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:52.948 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:53.949 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:53.950 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:53.950 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:54.951 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:54.952 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:54.952 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:55.953 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:55.954 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:55.954 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:56.955 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:56.956 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:56.956 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-29 13:10:57.957 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:10:57.958 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:57.959 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:10:59.100 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:10:59.104 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:10:59.104 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:00.106 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:00.108 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:00.109 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:01.110 ThaliTest[727:984487] BTM: attaching to BTServer
2016-08-29 13:11:01.113 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:01.113 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:02.115 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:02.117 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:02.117 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:03.119 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:03.122 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:03.122 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:04.124 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:04.126 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:04.127 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:05.128 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:05.130 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:05.131 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:06.132 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:06.135 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:06.135 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:07.137 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:07.139 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:07.139 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:08.141 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:08.144 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:08.144 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:10.205 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:10.208 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:10.208 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:11.210 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:11.213 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:11.213 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:12.215 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:12.217 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:12.217 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:13.219 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:13.221 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:13.222 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:14.223 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:14.226 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:14.226 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:15.228 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:15.230 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:15.231 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:16.232 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:16.235 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:16.235 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:17.236 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:17.239 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:17.239 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:18.241 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:18.243 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:18.244 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:19.245 ThaliTest[727:984487] BTM: attaching to BTServer
,2016-08-29 13:11:19.248 ThaliTest[727:984487] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-29 13:11:19.248 ThaliTest[727:984487] BTM: attemping to re-attach in 1 seconds
,2016-08-29 13:11:21.224 ThaliTest[727:984487] BTM: attaching to BTServer
,* thread #1: tid = 0xf05a7, 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x3768bdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x375dcbc0 libsystem_asl.dylib`_asl_server_message + 112
    frame #3: 0x375dba5c libsystem_asl.dylib`<redacted> + 1048
    frame #4: 0x375db5e4 libsystem_asl.dylib`asl_send + 8
    frame #5: 0x2543dda8 CoreFoundation`<redacted> + 584
    frame #6: 0x2543db3c CoreFoundation`_CFLogvEx2 + 212
    frame #7: 0x2543df1e CoreFoundation`_CFLogvEx3 + 118
    frame #8: 0x26218536 Foundation`<redacted> + 126
    frame #9: 0x2615f87c Foundation`NSLog + 28
    frame #10: 0x2b178fda BluetoothManager`<redacted> + 282
    frame #11: 0x2fcd2b10 MobileBluetooth`<redacted> + 36
    frame #12: 0x375a7e2e libdispatch.dylib`<redacted> + 10
    frame #13: 0x375a7e1a libdispatch.dylib`<redacted> + 22
    frame #14: 0x375ac6c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #15: 0x25417534 CoreFoundation`<redacted> + 8
    frame #16: 0x25415a2e CoreFoundation`<redacted> + 1590
    frame #17: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #18: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #19: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #20: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #21: 0x000c4c82 ThaliTest`main + 50
    frame #22: 0x375d0872 libdyld.dylib`<redacted> + 2

```
