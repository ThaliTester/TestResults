#### Test 828946820542738_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C6F2B3DD-5E11-4A97-B3E3-79422EB296EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C6F2B3DD-5E11-4A97-B3E3-79422EB296EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/76EF9E7D-A906-4DF2-A1D4-A7AE7B1C20A7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57382"
,(lldb)     command script import "/tmp/C6F2B3DD-5E11-4A97-B3E3-79422EB296EB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:08:04.735 ThaliTest[1793:3396852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F380FC67-2E0D-4552-B616-928F43D29E71/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:08:04.967 ThaliTest[1793:3396852] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:08:04.968 ThaliTest[1793:3396852] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:08:04.981 ThaliTest[1793:3396852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:08:05.775 ThaliTest[1793:3396852] Using UIWebView
,2016-09-06 19:08:05.778 ThaliTest[1793:3396852] [CDVTimer][handleopenurl] 0.119984ms
,2016-09-06 19:08:05.780 ThaliTest[1793:3396852] [CDVTimer][intentandnavigationfilter] 1.924992ms
2016-09-06 19:08:05.780 ThaliTest[1793:3396852] [CDVTimer][gesturehandler] 0.086010ms
2016-09-06 19:08:05.780 ThaliTest[1793:3396852] [CDVTimer][TotalPluginS,tartup] 2.578974ms
,2016-09-06 19:08:08.787 ThaliTest[1793:3396852] Resetting plugins due to page load.
,2016-09-06 19:08:10.166 ThaliTest[1793:3396852] Finished load of: file:///var/mobile/Containers/Bundle/Application/76EF9E7D-A906-4DF2-A1D4-A7AE7B1C20A7/ThaliTest.app/www/index.html
,2016-09-06 19:08:10.301 ThaliTest[1793:3396852] JXcore Cordova plugin initializing
,2016-09-06 19:08:10.301 ThaliTest[1793:3397033] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-09-06 19:08:10.410 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:10.411 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:10.411 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:08:11.412 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:11.413 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:11.413 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:12.414 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:12.415 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:12.415 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:13.416 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:13.417 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:13.417 ThaliTest[1793:3396852] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:14.418 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:14.419 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:14.419 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:15.420 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:15.421 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:15.421 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:08:16.422 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:16.423 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:16.423 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:17.424 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:17.425 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:17.425 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:18.426 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:18.427 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:18.427 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:19.428 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:19.429 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:19.429 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:20.430 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:20.431 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:20.431 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:21.432 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:21.433 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:21.433 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:22.434 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:22.435 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:22.435 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:23.436 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:23.437 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:23.437 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:24.438 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:24.439 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:24.439 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:25.440 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:25.441 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:25.441 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:26.442 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:26.443 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:26.443 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:27.444 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:27.445 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:27.445 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:28.446 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:28.447 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:28.447 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:29.447 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:29.448 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:29.448 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:30.449 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:30.450 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:30.450 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:31.451 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:31.452 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:31.452 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:32.456 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:32.457 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:32.457 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:33.458 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:33.459 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:33.459 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:34.460 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:34.461 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:34.461 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:35.462 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:35.463 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:35.463 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:36.464 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:36.464 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:36.465 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:37.466 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:37.466 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:37.467 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:38.467 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:38.468 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:38.468 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:39.469 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:39.470 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:39.470 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:40.471 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:40.471 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:40.472 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:41.473 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:41.473 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:41.473 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:42.475 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:42.475 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:42.475 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:43.477 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:43.477 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:43.477 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:44.479 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:44.479 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:44.479 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:45.481 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:45.481 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:45.481 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:46.482 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:46.483 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:46.483 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:47.484 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:47.485 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:47.485 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:48.487 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:48.487 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:48.487 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:49.488 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:49.489 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:49.489 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:50.491 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:50.491 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:50.491 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:51.493 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:51.493 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:51.493 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:52.495 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:52.495 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:52.495 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:53.497 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:53.497 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:53.497 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:54.499 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:54.499 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:54.499 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:55.041 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:55.042 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:55.042 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:55.501 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:55.501 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:55.501 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:56.043 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:08:56.044 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:56.044 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:56.503 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:56.503 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:56.503 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:57.045 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:57.046 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:57.046 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:57.504 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:57.505 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:57.505 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:58.047 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:58.048 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:58.048 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:58.506 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:58.506 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:58.506 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:59.049 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:59.050 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:59.050 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:59.507 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:08:59.508 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:59.508 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:00.051 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:00.052 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:00.052 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:00.509 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:00.510 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:00.510 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:01.053 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:01.054 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:01.054 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:01.511 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:01.512 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:01.512 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:02.055 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:02.055 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:02.056 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:02.513 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:02.514 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:02.514 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:03.057 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:03.057 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:03.058 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:03.515 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:03.516 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:03.516 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:04.059 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:04.059 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:04.060 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:04.517 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:04.518 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:04.518 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:05.073 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:09:05.073 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:05.073 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:05.519 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:05.520 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:05.520 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:06.075 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:06.075 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:06.075 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:06.521 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:06.521 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:06.522 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:07.076 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:07.077 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:07.077 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:07.523 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:07.523 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:07.524 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:08.078 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:08.079 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:08.079 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:08.525 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:08.525 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:08.525 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:09.080 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:09.081 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:09.081 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:09.527 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:09.527 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:09.527 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:10.082 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:10.083 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:10.083 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:10.528 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:10.529 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:10.529 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:11.084 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:11.085 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:11.085 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:11.530 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:11.531 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:11.531 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:12.086 ThaliTest[1793:3396852] BTM: attaching to BTServer
2016-09-06 19:09:12.087 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:12.087 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:12.532 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:12.533 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:12.533 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:13.088 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:13.089 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:13.089 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:13.534 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:13.535 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:13.535 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:14.090 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:14.091 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:14.091 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:14.536 ThaliTest[1793:3396852] BTM: attaching to BTServer
,2016-09-06 19:09:14.537 ThaliTest[1793:3396852] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:14.537 ThaliTest[1793:3396852] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:15.077 ThaliTest[1793:3396852] BTM: attaching to BTServer
,* thread #1: tid = 0x33d4f4, 0x3444ffbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x3444ffbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x3444fdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2210c48c CoreFoundation`<redacted> + 136
    frame #3: 0x2210a812 CoreFoundation`<redacted> + 1050
    frame #4: 0x2205d0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x2205cecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2b204af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x262e62dc UIKit`UIApplicationMain + 144
    frame #8: 0x000f64f2 ThaliTest`main + 50
    frame #9: 0x34394872 libdyld.dylib`<redacted> + 2

```
