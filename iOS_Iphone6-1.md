#### Test 82894682929afb6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D4F501FA-D17D-4D31-8111-480811F109A3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D4F501FA-D17D-4D31-8111-480811F109A3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/822606ED-C632-4CD4-A256-7664B2280F5E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52930"
,(lldb)     command script import "/tmp/D4F501FA-D17D-4D31-8111-480811F109A3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 08:50:28.537 ThaliTest[900:1252161] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C93DB2A-A69D-4BB3-93BD-19B72D3091B7/Library/Cookies/Cookies.binarycookies
,2016-08-31 08:50:29.023 ThaliTest[900:1252161] Apache Cordova native platform version 4.1.1 is starting.
2016-08-31 08:50:29.025 ThaliTest[900:1252161] Multi-tasking -> Device: YES, App: YES
,2016-08-31 08:50:29.047 ThaliTest[900:1252161] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 08:50:30.906 ThaliTest[900:1252161] Using UIWebView
,2016-08-31 08:50:30.914 ThaliTest[900:1252161] [CDVTimer][handleopenurl] 0.607014ms
,2016-08-31 08:50:30.922 ThaliTest[900:1252161] [CDVTimer][intentandnavigationfilter] 8.120000ms
2016-08-31 08:50:30.923 ThaliTest[900:1252161] [CDVTimer][gesturehandler] 0.329971ms
2016-08-31 08:50:30.923 ThaliTest[900:1252161] [CDVTimer][TotalPluginStar,tup] 10.701001ms
,2016-08-31 08:50:37.421 ThaliTest[900:1252161] Resetting plugins due to page load.
,2016-08-31 08:50:40.812 ThaliTest[900:1252161] Finished load of: file:///var/mobile/Containers/Bundle/Application/822606ED-C632-4CD4-A256-7664B2280F5E/ThaliTest.app/www/index.html
,2016-08-31 08:50:41.045 ThaliTest[900:1252161] JXcore Cordova plugin initializing
,2016-08-31 08:50:41.046 ThaliTest[900:1252417] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 08:50:41.201 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:41.203 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:41.203 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 08:50:42.204 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:42.205 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:42.205 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:43.207 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:43.207 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:43.208 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:44.208 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:44.210 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:44.210 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:45.211 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:45.212 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:45.212 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:46.213 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:46.215 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:46.215 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:47.216 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:47.217 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:47.217 ThaliTest[900:1252161] BTM: attemping to ,re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 08:50:48.218 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:48.219 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:48.219 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:48.328 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:48.336 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:48.337 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:49.220 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:49.223 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:49.223 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:49.338 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:49.340 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:49.341 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:50.225 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:50.227 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:50.227 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:50.342 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:50.344 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:50.344 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:51.229 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:51.231 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:51.232 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:51.346 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:51.348 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:51.348 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:52.233 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:52.236 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:52.236 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:52.350 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:52.352 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:52.353 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:53.238 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:53.240 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.240 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:53.354 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:53.357 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.357 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.242 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:54.244 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.244 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.358 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:54.360 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.360 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.246 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:55.248 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:55.249 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.362 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:55.365 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:55.365 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.250 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:56.253 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.253 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.367 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:56.369 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.369 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.255 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:57.257 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.257 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.371 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:57.374 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.374 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.259 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:58.261 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.262 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.435 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:50:58.436 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.436 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.263 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:59.266 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.266 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.438 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:50:59.440 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.440 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.268 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:00.270 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.271 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.442 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:00.444 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.445 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.272 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:01.275 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.275 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.446 ThaliTest[900:1252161] BTM: attaching to BTServer
2016-08-31 08:51:01.448 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.449 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.277 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:02.279 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.279 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.450 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:02.453 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.453 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.281 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:03.283 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.284 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.455 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:03.457 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.458 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.285 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:04.288 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:04.288 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.459 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:04.462 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:04.462 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.290 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:05.292 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.292 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.463 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:05.466 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.466 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.294 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:06.296 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.296 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.468 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:06.471 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.471 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.298 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:07.301 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.301 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.472 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:07.475 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.475 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.302 ThaliTest[900:1252161] BTM: attaching to BTServer
,2016-08-31 08:51:08.305 ThaliTest[900:1252161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:08.305 ThaliTest[900:1252161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.451 ThaliTest[900:1252161] BTM: attaching to BTServer
,* thread #1: tid = 0x131b41, 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x3768bfbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x3768bdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2541748c CoreFoundation`<redacted> + 136
    frame #3: 0x25415812 CoreFoundation`<redacted> + 1050
    frame #4: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #8: 0x00021f02 ThaliTest`main + 50
    frame #9: 0x375d0872 libdyld.dylib`<redacted> + 2

```
