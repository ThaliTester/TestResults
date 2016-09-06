#### Test 828946820542738_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D894269C-4AE7-4DA4-B519-83E3A1C26CC5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D894269C-4AE7-4DA4-B519-83E3A1C26CC5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946820542738/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/640DF436-BDA6-42C7-91D4-D170690A14C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57384"
,(lldb)     command script import "/tmp/D894269C-4AE7-4DA4-B519-83E3A1C26CC5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:08:04.530 ThaliTest[1711:3619677] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/60933C21-46BE-4B78-B915-C78CC658BCF6/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:08:04.774 ThaliTest[1711:3619677] Apache Cordova native platform version 4.1.1 is starting.
2016-09-06 19:08:04.776 ThaliTest[1711:3619677] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:08:04.797 ThaliTest[1711:3619677] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:08:05.576 ThaliTest[1711:3619677] Using UIWebView
2016-09-06 19:08:05.578 ThaliTest[1711:3619677] [CDVTimer][handleopenurl] 0.159025ms
,2016-09-06 19:08:05.583 ThaliTest[1711:3619677] [CDVTimer][intentandnavigationfilter] 4.024029ms
2016-09-06 19:08:05.583 ThaliTest[1711:3619677] [CDVTimer][gesturehandler] 0.160992ms
2016-09-06 19:08:05.583 ThaliTest[1711:3619677] [CDVTimer][TotalPluginS,tartup] 4.972994ms
,2016-09-06 19:08:08.536 ThaliTest[1711:3619677] Resetting plugins due to page load.
,2016-09-06 19:08:09.968 ThaliTest[1711:3619677] Finished load of: file:///var/mobile/Containers/Bundle/Application/640DF436-BDA6-42C7-91D4-D170690A14C4/ThaliTest.app/www/index.html
,2016-09-06 19:08:10.153 ThaliTest[1711:3619677] JXcore Cordova plugin initializing
,2016-09-06 19:08:10.154 ThaliTest[1711:3619856] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-09-06 19:08:10.274 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:10.276 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:10.276 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:08:11.277 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:11.278 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:11.278 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:12.280 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:12.281 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:12.281 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:13.282 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:13.283 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:13.283 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:14.285 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:14.286 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:14.286 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:15.287 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:15.288 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:15.288 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:16.290 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:16.291 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:16.291 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:17.292 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:17.293 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:17.293 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:08:18.295 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:18.296 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:18.296 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:19.297 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:19.298 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:19.299 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:20.300 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:20.301 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:20.301 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:21.302 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:21.303 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:21.303 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:22.305 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:22.306 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:22.306 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:23.307 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:23.308 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:23.309 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:24.310 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:24.311 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:24.311 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:25.312 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:25.313 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:25.313 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:26.315 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:26.316 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:26.316 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:27.317 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:27.318 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:27.318 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:28.319 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:28.320 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:28.321 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:29.322 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:29.323 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:29.323 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:30.324 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:30.325 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:30.326 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:31.327 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:31.328 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:31.328 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:32.329 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:32.330 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:32.330 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:33.332 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:33.333 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:33.333 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:34.334 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:34.335 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:34.335 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:35.336 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:35.337 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:35.337 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:36.339 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:36.340 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:36.340 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:37.341 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:37.342 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:37.342 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:38.343 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:38.344 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:38.345 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:39.346 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:39.347 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:39.347 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:40.347 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:40.348 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:40.349 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:41.350 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:41.351 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:41.351 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:42.352 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:42.353 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:42.354 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:43.355 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:43.356 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:43.356 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:44.357 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:44.358 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:44.359 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:45.360 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:45.361 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:45.361 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:46.362 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:46.363 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:46.363 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:47.365 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:47.366 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:47.366 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:48.367 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:48.368 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:48.368 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:49.369 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:49.371 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:49.371 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:50.372 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:50.373 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:50.373 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:51.375 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:51.376 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:51.376 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:52.377 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:52.379 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:52.379 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:53.380 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:53.381 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:53.381 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:54.382 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:54.383 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:54.384 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:55.385 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:55.386 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:55.386 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:08:56.387 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:56.388 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:56.388 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:56.972 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:56.973 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:56.973 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:57.389 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:57.390 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:57.390 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:57.974 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:57.975 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:57.976 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:58.391 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:08:58.392 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:58.393 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:58.977 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:58.978 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:58.978 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:59.394 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:59.395 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:59.395 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:08:59.979 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:08:59.980 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:08:59.980 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:00.396 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:00.397 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:00.397 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:00.981 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:00.982 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:00.983 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:01.399 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:09:01.400 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:01.400 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:01.984 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:01.985 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:01.985 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:09:02.401 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:02.402 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:02.402 ThaliTest[1711:3619677] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:09:02.986 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:09:02.987 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:02.987 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:03.403 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:03.404 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:03.404 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:03.989 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:03.990 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:03.990 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:04.406 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:04.407 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:04.407 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:04.991 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:04.992 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:04.992 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:05.408 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:05.409 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:05.409 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:05.993 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:05.994 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:05.994 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:06.410 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:06.411 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:06.411 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:07.017 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:07.018 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:07.018 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:07.412 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:07.413 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:07.413 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:08.020 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:08.021 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:08.021 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:08.415 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:08.416 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:08.416 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:09.022 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:09.023 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:09.023 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:09.417 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:09.418 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:09.418 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:10.024 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:10.025 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:10.025 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:10.419 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:10.420 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:10.420 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:11.027 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:11.028 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:11.028 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:11.422 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:11.423 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:11.423 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:12.029 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:12.030 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:12.030 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:12.424 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:12.425 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:12.425 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:13.031 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:13.032 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:13.032 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:13.425 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:13.426 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:13.426 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:14.034 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:14.035 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:14.035 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:14.428 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:14.429 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:14.429 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:15.036 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:09:15.037 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:15.037 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:15.430 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:09:15.431 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:15.431 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:16.039 ThaliTest[1711:3619677] BTM: attaching to BTServer
,2016-09-06 19:09:16.040 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:16.040 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:16.432 ThaliTest[1711:3619677] BTM: attaching to BTServer
2016-09-06 19:09:16.433 ThaliTest[1711:3619677] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:09:16.434 ThaliTest[1711:3619677] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:09:17.025 ThaliTest[1711:3619677] BTM: attaching to BTServer
,* thread #1: tid = 0x373b5d, 0x37423fbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x37423fbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x37423dbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2527f48c CoreFoundation`<redacted> + 136
    frame #3: 0x2527d812 CoreFoundation`<redacted> + 1050
    frame #4: 0x251d00d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x251cfecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2e505af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x294592dc UIKit`UIApplicationMain + 144
    frame #8: 0x000124f2 ThaliTest`main + 50
    frame #9: 0x37368872 libdyld.dylib`<redacted> + 2

```
