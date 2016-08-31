#### Test 828946826925cd3_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7DF79CDF-60A6-45AB-9600-BEFC7EB7EB12/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7DF79CDF-60A6-45AB-9600-BEFC7EB7EB12/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8599725F-61BF-45B5-9BA5-42F9FDB83835/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51466"
,(lldb)     command script import "/tmp/7DF79CDF-60A6-45AB-9600-BEFC7EB7EB12/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 17:05:36.274 ThaliTest[950:1304355] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FDB4C736-2112-44FF-93C5-B1B7055AC5B7/Library/Cookies/Cookies.binarycookies
,2016-08-31 17:05:36.717 ThaliTest[950:1304355] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 17:05:36.719 ThaliTest[950:1304355] Multi-tasking -> Device: YES, App: YES
,2016-08-31 17:05:36.743 ThaliTest[950:1304355] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 17:05:38.707 ThaliTest[950:1304355] Using UIWebView
,2016-08-31 17:05:38.717 ThaliTest[950:1304355] [CDVTimer][handleopenurl] 0.404000ms
,2016-08-31 17:05:38.727 ThaliTest[950:1304355] [CDVTimer][intentandnavigationfilter] 9.036005ms
2016-08-31 17:05:38.727 ThaliTest[950:1304355] [CDVTimer][gesturehandler] 0.373006ms
2016-08-31 17:05:38.728 ThaliTest[950:1304355] [CDVTimer][TotalPluginStartup] 11.504948ms
,2016-08-31 17:05:45.253 ThaliTest[950:1304355] Resetting plugins due to page load.
,2016-08-31 17:05:48.890 ThaliTest[950:1304355] Finished load of: file:///var/mobile/Containers/Bundle/Application/8599725F-61BF-45B5-9BA5-42F9FDB83835/ThaliTest.app/www/index.html
,2016-08-31 17:05:49.124 ThaliTest[950:1304355] JXcore Cordova plugin initializing
,2016-08-31 17:05:49.126 ThaliTest[950:1304586] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 17:05:49.276 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:05:49.277 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:49.278 ThaliTest[950:1304355] BTM: attemping to ,re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 17:05:50.279 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:05:50.280 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:50.280 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:51.281 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:51.282 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:51.283 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:52.284 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:52.285 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:52.285 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:53.286 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:05:53.287 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:53.287 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:54.288 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:05:54.290 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:54.290 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:55.291 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:05:55.292 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:55.292 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 17:05:56.293 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:56.295 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:56.295 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:56.443 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:56.451 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:56.451 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:57.297 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:57.299 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:57.300 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:57.453 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:57.455 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:57.456 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:58.301 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:58.304 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.304 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:58.457 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:58.460 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.460 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.306 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:59.308 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.308 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.461 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:05:59.464 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.464 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.310 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:00.312 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.313 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.466 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:00.468 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.469 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.314 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:01.317 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:01.317 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.470 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:01.473 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 17:06:01.473 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.318 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:02.321 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.321 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.475 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:02.477 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.477 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.323 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:03.325 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.325 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.479 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:03.482 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.482 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.327 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:04.330 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.330 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.484 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:04.486 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.486 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.331 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:05.334 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.334 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.488 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:05.490 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.491 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.336 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:06.338 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.339 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.543 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:06.544 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.544 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.340 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:07.343 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:07.343 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.545 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:07.548 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:07.548 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.345 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:08.347 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.347 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.549 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:08.552 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.552 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.349 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:09.352 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.352 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.554 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:09.556 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.557 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.353 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:10.356 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.356 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.558 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:06:10.560 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.561 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.358 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:11.360 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.361 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.562 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:11.565 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.565 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.362 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:12.365 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:12.365 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.567 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:12.569 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:12.569 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.367 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:13.369 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.370 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.571 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:13.574 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.574 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.371 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:14.374 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.374 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.575 ThaliTest[950:1304355] BTM: attaching to BTServer
2016-08-31 17:06:14.578 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.578 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.375 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:15.378 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.378 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.579 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:15.582 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.582 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.380 ThaliTest[950:1304355] BTM: attaching to BTServer
,2016-08-31 17:06:16.382 ThaliTest[950:1304355] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:16.383 ThaliTest[950:1304355] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.560 ThaliTest[950:1304355] BTM: attaching to BTServer
,* thread #1: tid = 0x13e723, 0x3762b258 libsystem_c.dylib`<redacted> + 120, queue = 'com.apple.main-thread'
  * frame #0: 0x3762b258 libsystem_c.dylib`<redacted> + 120
    frame #1: 0x37641964 libsystem_c.dylib`<redacted> + 516
    frame #2: 0x375eec4c libsystem_c.dylib`<redacted> + 332
    frame #3: 0x375eeaf8 libsystem_c.dylib`vsnprintf + 72
    frame #4: 0x37647b36 libsystem_c.dylib`__snprintf_chk + 22
    frame #5: 0x375ddf0e libsystem_asl.dylib`asl_base_msg + 154
    frame #6: 0x375db784 libsystem_asl.dylib`<redacted> + 320
    frame #7: 0x375db5e4 libsystem_asl.dylib`asl_send + 8
    frame #8: 0x2543dda8 CoreFoundation`<redacted> + 584
    frame #9: 0x2543db3c CoreFoundation`_CFLogvEx2 + 212
    frame #10: 0x2543df1e CoreFoundation`_CFLogvEx3 + 118
    frame #11: 0x26218536 Foundation`<redacted> + 126
    frame #12: 0x2615f87c Foundation`NSLog + 28
    frame #13: 0x2b178fda BluetoothManager`<redacted> + 282
    frame #14: 0x2fcd2b10 MobileBluetooth`<redacted> + 36
    frame #15: 0x375a7e2e libdispatch.dylib`<redacted> + 10
    frame #16: 0x375a7e1a libdispatch.dylib`<redacted> + 22
    frame #17: 0x375ac6c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #18: 0x25417534 CoreFoundation`<redacted> + 8
    frame #19: 0x25415a2e CoreFoundation`<redacted> + 1590
    frame #20: 0x253680d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #21: 0x25367ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #22: 0x2e69daf8 GraphicsServices`GSEventRunModal + 160
    frame #23: 0x295f12dc UIKit`UIApplicationMain + 144
    frame #24: 0x00065f02 ThaliTest`main + 50
    frame #25: 0x375d0872 libdyld.dylib`<redacted> + 2

```
