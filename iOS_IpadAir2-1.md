#### Test 84265062e3ffea4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/018173E0-9BCE-40CF-8EB1-39B9BB5B9E42/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/018173E0-9BCE-40CF-8EB1-39B9BB5B9E42/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062e3ffea4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/72B793CD-BEF0-4011-B1E7-0624E2982A6B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49510"
,(lldb)     command script import "/tmp/018173E0-9BCE-40CF-8EB1-39B9BB5B9E42/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 12:03:37.701 ThaliTest[1884:3495010] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65E6598D-E7E6-4F95-B700-6AE1DE23FC15/Library/Cookies/Cookies.binarycookies
,2016-09-07 12:03:37.940 ThaliTest[1884:3495010] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 12:03:37.941 ThaliTest[1884:3495010] Multi-tasking -> Device: YES, App: YES
,2016-09-07 12:03:37.955 ThaliTest[1884:3495010] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 12:03:38.770 ThaliTest[1884:3495010] Using UIWebView
,2016-09-07 12:03:38.773 ThaliTest[1884:3495010] [CDVTimer][handleopenurl] 0.109017ms
,2016-09-07 12:03:38.775 ThaliTest[1884:3495010] [CDVTimer][intentandnavigationfilter] 1.901031ms
2016-09-07 12:03:38.775 ThaliTest[1884:3495010] [CDVTimer][gesturehandler] 0.084996ms
2016-09-07 12:03:38.775 ThaliTest[1884:3495010] [CDVTimer][TotalPluginStartup] 2.533972ms
,2016-09-07 12:03:41.796 ThaliTest[1884:3495010] Resetting plugins due to page load.
,2016-09-07 12:03:43.204 ThaliTest[1884:3495010] Finished load of: file:///var/mobile/Containers/Bundle/Application/72B793CD-BEF0-4011-B1E7-0624E2982A6B/ThaliTest.app/www/index.html
,2016-09-07 12:03:43.341 ThaliTest[1884:3495010] JXcore Cordova plugin initializing
2016-09-07 12:03:43.341 ThaliTest[1884:3495180] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-07 12:03:49.519 ThaliTest[1884:3495010] BTM: attaching to BTServer
2016-09-07 12:03:49.520 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:49.520 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:49.530 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:49.530 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:49.530 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:50.521 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:50.522 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:50.522 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:50.531 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:50.532 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:50.532 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:51.523 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:51.524 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:51.524 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:51.533 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:51.534 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:51.534 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:52.525 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:52.525 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:52.525 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:52.534 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:52.535 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:52.535 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:53.526 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:53.527 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:53.527 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:53.536 ThaliTest[1884:3495010] BTM: attaching to BTServer
2016-09-07 12:03:53.537 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:53.537 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:54.528 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:54.529 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:54.529 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:54.537 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:54.538 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:54.538 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:55.530 ThaliTest[1884:3495010] BTM: attaching to BTServer
2016-09-07 12:03:55.531 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:55.531 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:55.539 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:55.539 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:55.539 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:56.532 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:56.533 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:56.533 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:56.540 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:56.541 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:56.541 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:57.534 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:57.535 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-09-07 12:03:57.535 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:57.542 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:57.543 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:57.543 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:58.536 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:58.537 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:58.537 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:58.544 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:58.544 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:58.544 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:03:59.562 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:03:59.563 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:03:59.563 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:00.564 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:00.565 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:00.565 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:01.567 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:01.567 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:01.567 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:02.568 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:02.569 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:02.569 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:03.571 ThaliTest[1884:3495010] BTM: attaching to BTServer
2016-09-07 12:04:03.571 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:03.571 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:04.573 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:04.573 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:04.573 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:05.575 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:05.575 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:05.575 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:06.576 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:06.577 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:06.577 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:07.578 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:07.579 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:07.579 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:08.580 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:08.581 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:08.581 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:09.567 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:09.579 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:09.579 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:09.581 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:09.582 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:09.582 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:10.580 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:10.581 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:10.581 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:10.583 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:10.583 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:10.583 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:11.581 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:11.582 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:11.582 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:11.584 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:11.584 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:11.585 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:12.583 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:12.584 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:12.584 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:12.585 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:12.585 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:12.585 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:13.585 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:13.586 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:13.586 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
2016-09-07 12:04:13.586 ThaliTest[1884:3495010] B,TM: attaching to BTServer
2016-09-07 12:04:13.586 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:13.586 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:14.587 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:14.588 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:14.588 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:15.589 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:15.590 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:15.590 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:16.591 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:16.591 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:16.591 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:17.593 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:17.593 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:17.594 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:18.595 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:18.596 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:18.596 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:19.597 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:19.597 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:19.598 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:20.599 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:20.599 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:20.599 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:21.601 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:21.601 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:21.601 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:22.603 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:22.603 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:22.603 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:23.604 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:23.605 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:23.605 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:24.607 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:24.607 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:24.607 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:25.609 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:25.609 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:25.609 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:26.610 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:26.611 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:26.611 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:27.612 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:27.613 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:27.613 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:28.614 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:28.615 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:28.615 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:29.616 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:29.617 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:29.617 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:30.618 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:30.619 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:30.619 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:31.620 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:31.621 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:31.621 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:32.622 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:32.623 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:32.623 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:33.624 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:33.625 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:33.625 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:34.626 ThaliTest[1884:3495010] BTM: attaching to BTServer
2016-09-07 12:04:34.627 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:34.627 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:35.628 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:35.629 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:35.629 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:36.630 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:36.631 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:36.631 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:37.632 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:37.633 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:37.633 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:38.634 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:38.635 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:38.635 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:39.636 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:39.637 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:39.637 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:40.638 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:40.639 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:40.639 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:41.640 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:41.640 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:41.640 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:42.642 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:42.642 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:42.643 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:43.644 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:43.644 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:43.645 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:44.645 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:44.646 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:44.646 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:45.647 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:45.648 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:45.648 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:46.649 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:46.650 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:46.650 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,2016-09-07 12:04:47.651 ThaliTest[1884:3495010] BTM: attaching to BTServer
,2016-09-07 12:04:47.652 ThaliTest[1884:3495010] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-07 12:04:47.652 ThaliTest[1884:3495010] BTM: attemping to re-attach in 1 seconds
,Process 1884 stopped
* thread #16: tid = 0x35550c, 0x007d97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007d97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7d97e0 <+1188>: trap   
    0x7d97e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7d97e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7d97ec <+4>:    add    r7, sp, #12
,* thread #16: tid = 0x35550c, 0x007d97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007d97e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x0006ca84 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x0006aaae ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000653b2 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000cc57a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x0020ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x001a50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x0020ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00208118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x00203bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x0020abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x001a50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x0020ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00208118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x00203bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x0020abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x001a50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x0020ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00208118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x00203bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x0020abd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x001a50a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x0020ab36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00208118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x00203bfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0020b25a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x0020b372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x0018dd82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x000e6ae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x000e6b38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000cdebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000cca3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x00067abc ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x00065948 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x22f2036c Foundation`<redacted> + 1144
    frame #35: 0x34502c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x34502bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x34500a08 libsystem_pthread.dylib`thread_start + 8

```
