#### Test 828946826925cd3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/44002ED5-80F7-4E82-9FA7-7E4588D54407/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/44002ED5-80F7-4E82-9FA7-7E4588D54407/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/828946826925cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9AD9F72D-CBB6-4B65-921C-FE99943054B9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51469"
,(lldb)     command script import "/tmp/44002ED5-80F7-4E82-9FA7-7E4588D54407/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 17:05:37.640 ThaliTest[1373:2720161] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32AFEC99-DD64-4F44-967D-C9C206010B79/Library/Cookies/Cookies.binarycookies
,2016-08-31 17:05:38.026 ThaliTest[1373:2720161] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 17:05:38.027 ThaliTest[1373:2720161] Multi-tasking -> Device: YES, App: YES
,2016-08-31 17:05:38.051 ThaliTest[1373:2720161] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 17:05:40.085 ThaliTest[1373:2720161] Using UIWebView
,2016-08-31 17:05:40.093 ThaliTest[1373:2720161] [CDVTimer][handleopenurl] 0.599980ms
,2016-08-31 17:05:40.103 ThaliTest[1373:2720161] [CDVTimer][intentandnavigationfilter] 9.401023ms
,2016-08-31 17:05:40.104 ThaliTest[1373:2720161] [CDVTimer][gesturehandler] 0.458002ms
,2016-08-31 17:05:40.105 ThaliTest[1373:2720161] [CDVTimer][TotalPluginStartup] 12.374997ms
,2016-08-31 17:05:46.342 ThaliTest[1373:2720161] Resetting plugins due to page load.
,2016-08-31 17:05:49.877 ThaliTest[1373:2720161] Finished load of: file:///var/mobile/Containers/Bundle/Application/9AD9F72D-CBB6-4B65-921C-FE99943054B9/ThaliTest.app/www/index.html
,2016-08-31 17:05:50.117 ThaliTest[1373:2720161] JXcore Cordova plugin initializing
,2016-08-31 17:05:50.118 ThaliTest[1373:2720407] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 17:05:50.293 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:50.297 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:50.297 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 17:05:51.299 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:51.300 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:51.300 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:52.301 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:52.302 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:52.302 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:53.303 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:53.304 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:53.304 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:54.306 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:54.308 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:54.308 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:55.309 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:55.310 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:55.310 ThaliTest[1373:2720161] BTM: attemping ,to re-attach in 1 seconds
,2016-08-31 17:05:56.312 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:56.313 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:56.313 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:57.314 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:05:57.315 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:57.315 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:58.317 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:58.318 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.319 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 17:05:58.764 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:58.776 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:58.776 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.320 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:59.323 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.323 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:05:59.778 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:05:59.781 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:05:59.781 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.325 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:00.327 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.328 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:00.782 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:00.784 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:00.785 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.330 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:01.332 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:01.333 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:01.786 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:06:01.789 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:01.789 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.334 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:02.337 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.338 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:02.791 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:02.793 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:02.794 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.339 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:03.343 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.343 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:03.795 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:03.798 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:03.798 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.345 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:04.347 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.348 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:04.800 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:04.803 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:04.803 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.349 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:05.353 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.353 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:05.805 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:05.807 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:05.808 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.355 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:06.358 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.358 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:06.809 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:06.812 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:06.812 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.360 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:07.363 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:07.363 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:07.814 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:07.817 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:07.817 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.365 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:08.368 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.368 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:08.878 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:06:08.879 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:08.879 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.370 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:09.371 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.371 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:09.880 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:09.883 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:09.884 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.373 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:10.376 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.376 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:10.885 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:10.888 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:10.888 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.378 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:06:11.380 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.380 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:11.890 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:11.893 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:11.893 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.382 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:12.385 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:12.385 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:12.895 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:12.898 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:12.899 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.387 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:13.389 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.390 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:13.900 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:13.903 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:13.903 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.391 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:14.394 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.394 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:14.905 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:14.908 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:14.908 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.396 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:15.398 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.399 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:15.909 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:06:15.911 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:15.912 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.400 ThaliTest[1373:2720161] BTM: attaching to BTServer
2016-08-31 17:06:16.403 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:16.403 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:16.913 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:16.916 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:16.916 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:17.405 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:17.407 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:17.408 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:17.917 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:17.920 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:17.920 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:18.409 ThaliTest[1373:2720161] BTM: attaching to BTServer
,2016-08-31 17:06:18.412 ThaliTest[1373:2720161] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 17:06:18.413 ThaliTest[1373:2720161] BTM: attemping to re-attach in 1 seconds
,2016-08-31 17:06:18.897 ThaliTest[1373:2720161] BTM: attaching to BTServer
,Process 1373 stopped
* thread #15: tid = 0x298297, 0x00832998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x00832998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x832998 <+1188>: trap   
    0x83299c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x8329a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x8329a4 <+4>:    add    r7, sp, #12
,* thread #15: tid = 0x298297, 0x00832998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x00832998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x000d0548 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000ce4b6 ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x000c8d32 ThaliTest`callJXcoreNative + 660
    frame #4: 0x0012cdfa ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x0026b3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x00205928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x0026b3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x00268998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #9: 0x0026447c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x0026b452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x00205928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x0026b3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x00268998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #14: 0x0026447c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x0026b452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x00205928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x0026b3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x00268998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #19: 0x0026447c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x0026b452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x00205928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x0026b3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x00268998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #24: 0x0026447c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x0026bada ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x0026bbf2 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x001ee602 ThaliTest`___lldb_unnamed_function609$$ThaliTest + 20
    frame #28: 0x00147364 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x001473b8 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x0012e73c ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x0012d2be ThaliTest`JX_Evaluate + 40
    frame #32: 0x000cb43c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x000c92c8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2609336c Foundation`<redacted> + 1144
    frame #35: 0x374d6c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x374d6bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x374d4a08 libsystem_pthread.dylib`thread_start + 8

```
