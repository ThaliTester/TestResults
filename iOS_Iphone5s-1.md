#### Test 82894682e70646c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A980FEC1-1F4D-4118-BF1B-9E429D9D27E5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A980FEC1-1F4D-4118-BF1B-9E429D9D27E5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682e70646c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A84564E7-6044-4FFE-AED5-5E3741047BFA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57317"
,(lldb)     command script import "/tmp/A980FEC1-1F4D-4118-BF1B-9E429D9D27E5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:01:44.720 ThaliTest[1703:3618006] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0053EC85-A275-4656-B31C-DC6F7C07C15F/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:01:44.974 ThaliTest[1703:3618006] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:01:44.975 ThaliTest[1703:3618006] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:01:44.993 ThaliTest[1703:3618006] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:01:45.769 ThaliTest[1703:3618006] Using UIWebView
2016-09-06 19:01:45.771 ThaliTest[1703:3618006] [CDVTimer][handleopenurl] 0.145018ms
2016-09-06 19:01:45.774 ThaliTest[1703:3618006] [CDVTimer][intentandnavigationfilter] 2.611995ms
2016-09,-06 19:01:45.775 ThaliTest[1703:3618006] [CDVTimer][gesturehandler] 0.132024ms
2016-09-06 19:01:45.775 ThaliTest[1703:3618006] [CDVTimer][TotalPluginStartup] 3.440022ms
,2016-09-06 19:01:48.746 ThaliTest[1703:3618006] Resetting plugins due to page load.
,2016-09-06 19:01:50.007 ThaliTest[1703:3618006] Finished load of: file:///var/mobile/Containers/Bundle/Application/A84564E7-6044-4FFE-AED5-5E3741047BFA/ThaliTest.app/www/index.html
,2016-09-06 19:01:50.189 ThaliTest[1703:3618006] JXcore Cordova plugin initializing
,2016-09-06 19:01:50.190 ThaliTest[1703:3618176] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,2016-09-06 19:01:50.304 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:50.305 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:50.305 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-06 19:01:51.307 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:51.308 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:51.308 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:52.309 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:52.310 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:52.310 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:01:53.312 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:53.313 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:53.313 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:54.314 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:54.315 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:54.315 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:55.317 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:55.318 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:55.318 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:56.319 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:56.320 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:56.320 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:01:57.321 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:57.322 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:57.323 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-06 19:01:58.324 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:58.325 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:58.325 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:01:59.326 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:01:59.327 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:01:59.328 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:00.329 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:00.330 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:00.330 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:01.331 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:01.332 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:01.332 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:02.334 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:02.335 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:02.335 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:03.336 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:03.337 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:03.337 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:04.338 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:04.340 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:04.340 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:05.341 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:05.342 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:05.342 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:06.343 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:06.344 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:06.344 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:07.345 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:07.346 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:07.346 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:08.347 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:08.349 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:08.349 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:09.350 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:09.351 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:09.351 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:10.353 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:10.354 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:10.354 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:11.355 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:11.356 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:11.356 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:12.357 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:12.358 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:12.359 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:13.360 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:13.361 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:13.361 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:14.362 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:14.363 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:14.363 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:15.365 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:15.366 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:15.366 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:16.367 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:16.368 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:16.368 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:17.369 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:17.370 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:17.371 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:18.371 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:18.372 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:18.372 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:19.373 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:19.374 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:19.374 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:20.375 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:20.376 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:20.376 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:21.377 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:21.378 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:21.378 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:22.379 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:22.380 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:22.380 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:23.381 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:23.382 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:23.382 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:24.383 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:24.384 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:24.384 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:25.385 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:25.386 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:25.386 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:26.387 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:26.388 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:26.388 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:27.389 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:27.390 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:27.390 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:28.391 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:28.392 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:28.392 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:29.393 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:29.394 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:29.394 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:30.395 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:30.396 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:30.396 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:31.397 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:31.398 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:31.398 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:32.399 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:32.400 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:32.401 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:33.401 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:33.402 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:33.402 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:34.403 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:34.404 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:34.404 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:35.405 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:35.406 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:35.406 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:36.407 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:36.408 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:36.408 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:36.769 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:36.770 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:36.770 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:37.409 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:37.410 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:37.410 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:37.772 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:37.773 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:37.773 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:38.411 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:38.412 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:38.412 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:38.774 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:38.775 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:38.775 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:39.413 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:39.414 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:39.414 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:39.776 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:39.777 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:39.778 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:40.415 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:40.416 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:40.416 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:40.779 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:40.780 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:40.780 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:41.417 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:41.418 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:41.418 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:41.781 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:41.782 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:41.782 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:42.419 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:42.420 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:42.420 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:42.783 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:42.784 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:42.784 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:43.421 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:43.422 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:43.422 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:43.786 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:43.787 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:43.787 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:44.423 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:44.425 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:44.425 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:44.788 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:44.789 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:44.789 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:45.426 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:45.427 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:45.427 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:45.790 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:45.791 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:45.791 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:46.429 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:46.430 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:46.430 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:46.816 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:46.817 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:46.817 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:47.431 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:47.432 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:47.432 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:47.818 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:47.819 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:47.820 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:48.433 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:48.435 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:48.435 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:48.820 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:48.821 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:48.821 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:49.436 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:49.437 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:49.437 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:49.822 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:49.823 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:49.823 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:50.438 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:50.440 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:50.440 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:50.825 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:50.826 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:50.826 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:51.441 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:51.442 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:51.442 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:51.827 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:51.828 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:51.828 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:52.444 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:52.445 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:52.445 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:52.829 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:52.830 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:52.831 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:53.446 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:53.447 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:53.447 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:53.832 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:53.833 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:53.833 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:54.448 ThaliTest[1703:3618006] BTM: attaching to BTServer
,2016-09-06 19:02:54.450 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:54.450 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:54.834 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:54.835 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:54.836 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:55.451 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:55.452 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:55.452 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:55.837 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:55.838 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:55.838 ThaliTest[1703:3618006] BTM: attemping ,to re-attach in 1 seconds
,2016-09-06 19:02:56.453 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:56.454 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:56.454 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,2016-09-06 19:02:56.824 ThaliTest[1703:3618006] BTM: attaching to BTServer
2016-09-06 19:02:56.825 ThaliTest[1703:3618006] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-09-06 19:02:56.825 ThaliTest[1703:3618006] BTM: attemping to re-attach in 1 seconds
,Process 1703 stopped
* thread #15: tid = 0x373580, 0x008657e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x008657e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x8657e0 <+1188>: trap   
    0x8657e4 <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x8657e8 <+0>:    push   {r4, r5, r6, r7, lr}
    0x8657ec <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x373580, 0x008657e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x008657e0 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x000f8a90 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000f6aba ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000f1322 ThaliTest`callJXcoreNative + 660
    frame #4: 0x0015857a ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x00296b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x002310a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x00296b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00294118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #9: 0x0028fbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x00296bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x002310a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x00296b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00294118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #14: 0x0028fbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x00296bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x002310a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x00296b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00294118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #19: 0x0028fbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x00296bd2 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x002310a8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x00296b36 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00294118 ThaliTest`___lldb_unnamed_function991$$ThaliTest + 17664
    frame #24: 0x0028fbfc ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0029725a ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x00297372 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x00219d82 ThaliTest`___lldb_unnamed_function613$$ThaliTest + 20
    frame #28: 0x00172ae4 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x00172b38 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x00159ebc ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x00158a3e ThaliTest`JX_Evaluate + 40
    frame #32: 0x000f3a2c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000f18b8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2609336c Foundation`<redacted> + 1144
    frame #35: 0x374d6c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x374d6bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x374d4a08 libsystem_pthread.dylib`thread_start + 8

```
