#### Test 82894682e70646c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B401FE72-6B8F-4EBC-A1F9-52369A748EB4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B401FE72-6B8F-4EBC-A1F9-52369A748EB4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B2F700DB-2EE0-4702-9837-552726D339FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57319"
,(lldb)     command script import "/tmp/B401FE72-6B8F-4EBC-A1F9-52369A748EB4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:02:06.978 ThaliTest[1277:2180835] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EEF9906A-6039-4D33-8170-DF35F7E7D134/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:02:07.448 ThaliTest[1277:2180835] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:02:07.450 ThaliTest[1277:2180835] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:02:07.474 ThaliTest[1277:2180835] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:02:09.743 ThaliTest[1277:2180835] Using UIWebView
,2016-09-06 19:02:09.751 ThaliTest[1277:2180835] [CDVTimer][handleopenurl] 0.532031ms
,2016-09-06 19:02:09.758 ThaliTest[1277:2180835] [CDVTimer][intentandnavigationfilter] 7.192016ms
2016-09-06 19:02:09.759 ThaliTest[1277:2180835] [CDVTimer][gesturehandler] 0.429034ms
2016-09-06 19:02:09.760 ThaliTest[1277:2180835] [CDVTimer][TotalPluginStartup] 9.867013ms
,2016-09-06 19:02:17.527 ThaliTest[1277:2180835] Resetting plugins due to page load.
,2016-09-06 19:02:20.974 ThaliTest[1277:2180835] Finished load of: file:///var/mobile/Containers/Bundle/Application/B2F700DB-2EE0-4702-9837-552726D339FF/ThaliTest.app/www/index.html
,2016-09-06 19:02:21.212 ThaliTest[1277:2180835] JXcore Cordova plugin initializing
,2016-09-06 19:02:21.213 ThaliTest[1277:2181099] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-09-06 19:02:21.436 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:21.440 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:21.440 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:02:22.441 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:22.442 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:22.442 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:23.444 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:23.444 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:23.445 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:24.446 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:24.447 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:24.447 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:25.448 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:25.449 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:25.449 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:26.450 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:26.451 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:26.451 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:27.453 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:27.453 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:27.454 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:02:28.455 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:28.456 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:28.456 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:29.457 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:29.460 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:29.460 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:30.462 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:30.464 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:30.464 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:31.466 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:31.469 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:31.469 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:32.471 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:32.473 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:32.474 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:33.475 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:33.478 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:33.479 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:34.480 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:34.483 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:34.483 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:35.485 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:35.487 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:35.487 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:36.488 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:36.491 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:36.491 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:37.493 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:37.495 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:37.496 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:38.497 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:38.500 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:38.500 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:39.502 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:39.505 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:39.505 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:40.507 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:40.509 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:40.510 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:41.511 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:41.514 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:41.514 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:42.515 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:42.518 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:42.518 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:43.520 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:43.522 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:43.523 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:44.524 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:44.527 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:44.527 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:45.529 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:45.532 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-09-06 19:02:45.532 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:46.534 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:46.536 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:46.537 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:47.538 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:47.541 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:47.541 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:48.543 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:48.545 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:48.546 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:49.548 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:49.550 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:49.550 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:50.552 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:50.555 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:50.555 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:51.557 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:51.559 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:51.560 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:52.561 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:52.564 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:52.564 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:53.566 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:53.568 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:53.569 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:54.570 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:54.573 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:54.573 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:55.575 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:55.578 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:55.578 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:56.580 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:56.582 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:56.583 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:57.584 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:57.587 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:57.587 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:58.589 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:02:58.591 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:58.591 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:59.593 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:02:59.596 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:59.596 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:00.598 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:00.601 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:00.601 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:01.603 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:01.611 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:01.612 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:02.612 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:02.615 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:02.615 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:03.617 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:03.619 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:03.620 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:04.621 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:04.624 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:04.624 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:05.626 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:05.628 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:05.629 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:06.630 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:06.633 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:06.634 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:07.083 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:07.086 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:07.086 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:07.635 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:07.638 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:07.638 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:08.088 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:08.090 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:08.091 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:08.640 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:08.642 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:08.643 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:09.092 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:09.095 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:09.095 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:09.644 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:09.647 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:09.647 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:10.097 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:10.099 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:10.100 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:10.649 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:10.651 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:10.652 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:11.101 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:11.104 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:11.104 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:11.653 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:11.656 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:11.656 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:12.106 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:12.108 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:12.109 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:12.658 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:12.660 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:12.661 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:13.110 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:13.113 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:13.113 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:13.662 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:13.665 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:13.665 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:14.115 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:14.117 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:14.118 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:14.667 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:14.670 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:14.670 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:15.119 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:15.122 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:15.122 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:15.671 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:15.674 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:15.674 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:16.124 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:16.127 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:16.127 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:16.676 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:16.679 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:16.679 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:17.191 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:03:17.192 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:17.192 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:17.681 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:03:17.683 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:17.683 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:18.193 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:18.196 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:18.196 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:18.685 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:18.687 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:18.688 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:19.198 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:19.200 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:19.200 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:19.689 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:19.692 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:19.692 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:20.202 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:20.205 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:20.205 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:20.694 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:20.696 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:20.697 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:21.207 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:03:21.209 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:21.209 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:21.698 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:21.701 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:21.701 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:22.211 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:22.213 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:22.214 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:22.703 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:22.706 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:22.706 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:23.215 ThaliTest[1277:2180835] BTM: attaching to BTServer
2016-09-06 19:03:23.217 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:23.218 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:23.707 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:23.710 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:23.710 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:24.219 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:24.222 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:24.222 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:24.712 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:24.715 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-09-06 19:03:24.715 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:25.224 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:25.226 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:25.227 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:25.717 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:25.719 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:25.720 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:26.228 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:26.231 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:26.231 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:26.721 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:26.724 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:26.724 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:03:27.209 ThaliTest[1277:2180835] BTM: attaching to BTServer
,2016-09-06 19:03:27.213 ThaliTest[1277:2180835] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:03:27.213 ThaliTest[1277:2180835] BTM: attemping to re-attach in 1 seconds
,Process 1277 stopped
* thread #16: tid = 0x2147eb, 0x007857e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007857e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7857e0 <+1188>: trap   
    0x7857e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7857e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7857ec <+4>:    add    r7, sp, #12
,* thread #16: tid = 0x2147eb, 0x007857e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007857e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x00018a90 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x00016aba ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x00011322 ThaliTest`callJXcoreNative + 660
    frame #4: 0x0007857a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x001b6b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x001510a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x001b6b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x001b4118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x001afbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x001b6bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x001510a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x001b6b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x001b4118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x001afbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x001b6bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x001510a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x001b6b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x001b4118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x001afbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x001b6bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x001510a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x001b6b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x001b4118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x001afbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x001b725a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x001b7372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x00139d82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x00092ae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x00092b38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x00079ebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x00078a3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x00013a2c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000118b8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2622b36c Foundation`<redacted> + 1144
    frame #35: 0x3773ec7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x3773ebf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x3773ca08 libsystem_pthread.dylib`thread_start + 8

```
