#### Test 82894682e70646c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6685ACD5-1213-4826-8095-6EE4ED3B0681/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6685ACD5-1213-4826-8095-6EE4ED3B0681/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2A0E9904-7FDC-4431-80EE-BE827C103795/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57315"
,(lldb)     command script import "/tmp/6685ACD5-1213-4826-8095-6EE4ED3B0681/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:01:44.907 ThaliTest[1784:3395107] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBC3DBF2-088F-4D67-B108-477BCCE3923B/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:01:45.136 ThaliTest[1784:3395107] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:01:45.137 ThaliTest[1784:3395107] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:01:45.150 ThaliTest[1784:3395107] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:01:45.941 ThaliTest[1784:3395107] Using UIWebView
,2016-09-06 19:01:45.944 ThaliTest[1784:3395107] [CDVTimer][handleopenurl] 0.116944ms
,2016-09-06 19:01:45.946 ThaliTest[1784:3395107] [CDVTimer][intentandnavigationfilter] 1.883984ms
2016-09-06 19:01:45.946 ThaliTest[1784:3395107] [CDVTimer][gesturehandler] 0.096023ms
2016-09-06 19:01:45.946 ThaliTest[1784:3395107] [CDVTimer][TotalPluginStartup] 2.535045ms
,2016-09-06 19:01:48.918 ThaliTest[1784:3395107] Resetting plugins due to page load.
,2016-09-06 19:01:50.145 ThaliTest[1784:3395107] Finished load of: file:///var/mobile/Containers/Bundle/Application/2A0E9904-7FDC-4431-80EE-BE827C103795/ThaliTest.app/www/index.html
,2016-09-06 19:01:50.284 ThaliTest[1784:3395107] JXcore Cordova plugin initializing
,2016-09-06 19:01:50.285 ThaliTest[1784:3395299] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-09-06 19:01:50.400 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:01:50.401 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:50.401 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:01:51.402 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:51.403 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:51.403 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:52.404 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:01:52.405 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:52.405 ThaliTest[1784:3395107] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:01:53.406 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:53.407 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:53.407 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:54.408 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:01:54.409 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:54.409 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:55.410 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:55.411 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:55.412 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:01:56.413 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:01:56.414 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:56.414 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:57.415 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:57.416 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:57.416 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:58.417 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:58.418 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:58.418 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:59.419 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:01:59.420 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:59.420 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:00.421 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:00.422 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:00.422 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:01.423 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:01.424 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:01.424 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:02.425 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:02.426 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:02.426 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:03.427 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:03.428 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:03.428 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:04.429 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:04.430 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:04.430 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:05.431 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:05.432 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:05.432 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:06.433 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:06.434 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:06.434 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:07.435 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:07.436 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:07.436 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:08.437 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:08.438 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:08.438 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:09.439 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:09.440 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:09.440 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:10.441 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:10.442 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:10.442 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:11.443 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:11.444 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-09-06 19:02:11.444 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:12.445 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:12.446 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:12.446 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:13.447 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:13.448 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:13.448 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:14.449 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:14.450 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:14.450 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:15.451 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:15.452 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:15.452 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:16.453 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:16.454 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:16.454 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:17.455 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:17.456 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:17.456 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:18.457 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:18.458 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:18.458 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:19.458 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:19.459 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:19.459 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:20.460 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:20.461 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:20.461 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:21.462 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:21.463 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:21.463 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:22.463 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:22.464 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:22.464 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:23.466 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:23.466 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:23.466 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:24.467 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:24.468 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:24.468 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:25.469 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:25.470 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:25.470 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:26.471 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:26.471 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:26.472 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:27.473 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:27.473 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:27.474 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:28.475 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:28.475 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:28.476 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:29.477 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:29.479 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:29.479 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:30.481 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:30.481 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:30.481 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:31.483 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:31.483 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:31.483 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:32.485 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:32.485 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:32.486 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:33.486 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:33.487 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:33.487 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:34.488 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:34.489 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:34.489 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:34.849 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:34.850 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:34.850 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:35.490 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:35.491 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:35.491 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:35.851 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:35.852 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:35.852 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:36.492 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:36.493 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:36.493 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:36.853 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:36.854 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:36.854 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:37.494 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:37.495 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:37.495 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:37.855 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:37.856 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:37.856 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:38.496 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:38.497 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:38.497 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:38.857 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:38.858 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:38.858 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:39.498 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:39.499 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:39.499 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:39.859 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:39.859 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:39.860 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:40.500 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:40.501 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:40.501 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:40.861 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:40.861 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:40.861 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:41.502 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:41.503 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:41.503 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:41.863 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:41.863 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:41.863 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:42.504 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:42.504 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:42.505 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:42.865 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:42.865 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:42.865 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:43.506 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:43.506 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:43.506 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:43.866 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:43.867 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:43.867 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:44.507 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:44.508 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:44.508 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:44.879 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:44.880 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:44.880 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:45.509 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:45.509 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:45.510 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:45.881 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:45.882 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:45.882 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:46.511 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:46.511 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:46.511 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:46.882 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:46.883 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:46.883 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:47.513 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:47.513 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:47.513 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:47.883 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:47.884 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:47.884 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:48.515 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:48.515 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:48.515 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:48.884 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:48.885 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:48.885 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:49.516 ThaliTest[1784:3395107] BTM: attaching to BTServer
2016-09-06 19:02:49.517 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:49.517 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:49.885 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:49.886 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:49.886 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:50.518 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:50.519 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:50.519 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:50.886 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:50.887 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:50.887 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:51.520 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:51.521 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:51.521 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:51.888 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:51.889 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:51.889 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:52.522 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:52.523 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:52.523 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:52.890 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:52.891 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:52.891 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:53.524 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:53.525 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:53.525 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:53.892 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:53.893 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:53.893 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:54.526 ThaliTest[1784:3395107] BTM: attaching to BTServer
,2016-09-06 19:02:54.527 ThaliTest[1784:3395107] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:54.527 ThaliTest[1784:3395107] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:54.884 ThaliTest[1784:3395107] BTM: attaching to BTServer
,Process 1784 stopped
* thread #16: tid = 0x33cee3, 0x007ed7e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007ed7e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7ed7e0 <+1188>: trap   
    0x7ed7e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7ed7e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7ed7ec <+4>:    add    r7, sp, #12
,* thread #16: tid = 0x33cee3, 0x007ed7e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007ed7e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x00080a90 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x0007eaba ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x00079322 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000e057a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x0021eb36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x001b90a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x0021eb36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x0021c118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x00217bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x0021ebd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x001b90a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x0021eb36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x0021c118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x00217bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x0021ebd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x001b90a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x0021eb36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x0021c118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x00217bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x0021ebd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x001b90a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x0021eb36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x0021c118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x00217bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0021f25a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x0021f372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x001a1d82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x000faae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x000fab38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000e1ebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000e0a3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x0007ba2c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000798b8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x22f2036c Foundation`<redacted> + 1144
    frame #35: 0x34502c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x34502bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x34500a08 libsystem_pthread.dylib`thread_start + 8

```
