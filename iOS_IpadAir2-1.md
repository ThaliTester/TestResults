#### Test 828946826925cd3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7A7A5A6C-0323-45F5-9320-409BFC1C64A1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7A7A5A6C-0323-45F5-9320-409BFC1C64A1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/858CE97C-7531-44CD-A012-0C5A1DB2DC82/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51465"
,(lldb)     command script import "/tmp/7A7A5A6C-0323-45F5-9320-409BFC1C64A1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 17:05:37.081 ThaliTest[1480:2644871] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F79338D2-F700-406F-B5C7-A9CB270A85C0/Library/Cookies/Cookies.binarycookies
,2016-08-31 17:05:37.474 ThaliTest[1480:2644871] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 17:05:37.476 ThaliTest[1480:2644871] Multi-tasking -> Device: YES, App: YES
,2016-08-31 17:05:37.494 ThaliTest[1480:2644871] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 17:05:39.569 ThaliTest[1480:2644871] Using UIWebView
,2016-08-31 17:05:39.579 ThaliTest[1480:2644871] [CDVTimer][handleopenurl] 0.375032ms
,2016-08-31 17:05:39.587 ThaliTest[1480:2644871] [CDVTimer][intentandnavigationfilter] 6.655037ms
,2016-08-31 17:05:39.588 ThaliTest[1480:2644871] [CDVTimer][gesturehandler] 0.885010ms
2016-08-31 17:05:39.588 ThaliTest[1480:2644871] [CDVTimer][TotalPluginStartup] 9.644985ms
,2016-08-31 17:05:46.712 ThaliTest[1480:2644871] Resetting plugins due to page load.
,2016-08-31 17:05:50.687 ThaliTest[1480:2644871] Finished load of: file:///var/mobile/Containers/Bundle/Application/858CE97C-7531-44CD-A012-0C5A1DB2DC82/ThaliTest.app/www/index.html
,2016-08-31 17:05:50.897 ThaliTest[1480:2644871] JXcore Cordova plugin initializing
,2016-08-31 17:05:50.898 ThaliTest[1480:2645128] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 17:05:51.108 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:51.111 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:51.111 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 17:05:52.113 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:52.114 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:52.114 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:53.115 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:53.116 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:53.116 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:54.117 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:54.118 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:54.118 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:55.119 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:55.120 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:55.120 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:56.121 ThaliTest[1480:2644871] BTM: attaching to BTServer
2016-08-31 17:05:56.121 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:56.121 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:57.122 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:57.123 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:57.123 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 17:05:57.429 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:57.436 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:57.437 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:58.124 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:58.126 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.127 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:58.438 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:58.440 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.441 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.128 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:59.131 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.131 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.442 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:05:59.444 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.444 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.133 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:00.135 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.135 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.446 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:00.448 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.449 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.137 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:01.139 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 17:06:01.140 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.450 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:01.453 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:01.453 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.142 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:02.144 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.144 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.455 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:02.457 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.457 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.146 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:03.148 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.148 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.459 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:03.462 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.462 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.150 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:04.152 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.153 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.464 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:04.466 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.466 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.154 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:05.156 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.157 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.468 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:05.470 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.471 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.158 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:06.161 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.161 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.472 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:06.474 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.475 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.163 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:07.165 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 17:06:07.166 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.515 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:07.516 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:07.516 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.167 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:08.169 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.170 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.518 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:08.520 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.521 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.171 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:09.174 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.174 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.522 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:09.525 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.525 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.176 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:10.178 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.178 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.527 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:10.529 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.529 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.180 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:11.182 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.183 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.531 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:11.533 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.534 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.184 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:12.187 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:12.187 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.535 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:12.537 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 17:06:12.538 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.189 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:13.191 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.191 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.539 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:13.541 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.542 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.193 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:14.195 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.196 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.543 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:14.546 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.546 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.197 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:15.199 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.199 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.548 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:15.550 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.550 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.201 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:16.203 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:16.204 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.552 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:16.554 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:16.555 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:17.205 ThaliTest[1480:2644871] BTM: attaching to BTServer
,2016-08-31 17:06:17.208 ThaliTest[1480:2644871] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:17.208 ThaliTest[1480:2644871] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:17.530 ThaliTest[1480:2644871] BTM: attaching to BTServer
,* thread #1: tid = 0x285b87, 0x3444ffbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x3444ffbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x3444fdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2210c48c CoreFoundation`<redacted> + 136
    frame #3: 0x2210a812 CoreFoundation`<redacted> + 1050
    frame #4: 0x2205d0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x2205cecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2b204af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x262e62dc UIKit`UIApplicationMain + 144
    frame #8: 0x000adf02 ThaliTest`main + 50
    frame #9: 0x34394872 libdyld.dylib`<redacted> + 2

```
