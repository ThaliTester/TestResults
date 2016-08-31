#### Test 82894682929afb6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9E76EB72-E34A-4AE7-9F5A-1313651EB1AA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9E76EB72-E34A-4AE7-9F5A-1313651EB1AA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682929afb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E2CB1828-7476-41D6-9C90-9F0BC12382E0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52933"
,(lldb)     command script import "/tmp/9E76EB72-E34A-4AE7-9F5A-1313651EB1AA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 08:50:30.119 ThaliTest[1325:2665911] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1ED88FA7-84CB-4B58-8447-BD759FB7A1D3/Library/Cookies/Cookies.binarycookies
,2016-08-31 08:50:30.547 ThaliTest[1325:2665911] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 08:50:30.549 ThaliTest[1325:2665911] Multi-tasking -> Device: YES, App: YES
,2016-08-31 08:50:30.573 ThaliTest[1325:2665911] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 08:50:32.531 ThaliTest[1325:2665911] Using UIWebView
,2016-08-31 08:50:32.542 ThaliTest[1325:2665911] [CDVTimer][handleopenurl] 0.446975ms
,2016-08-31 08:50:32.552 ThaliTest[1325:2665911] [CDVTimer][intentandnavigationfilter] 9.420037ms
2016-08-31 08:50:32.553 ThaliTest[1325:2665911] [CDVTimer][gesturehandler] 0.376999ms
2016-08-31 08:50:32.554 ThaliTest[1325:2665911] [CDVTimer][TotalPluginS,tartup] 12.127995ms
,2016-08-31 08:50:38.749 ThaliTest[1325:2665911] Resetting plugins due to page load.
,2016-08-31 08:50:42.275 ThaliTest[1325:2665911] Finished load of: file:///var/mobile/Containers/Bundle/Application/E2CB1828-7476-41D6-9C90-9F0BC12382E0/ThaliTest.app/www/index.html
,2016-08-31 08:50:42.521 ThaliTest[1325:2665911] JXcore Cordova plugin initializing
,2016-08-31 08:50:42.522 ThaliTest[1325:2666142] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,2016-08-31 08:50:42.683 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:42.685 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:42.685 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 08:50:43.687 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:43.688 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:43.688 ThaliTest[1325:2665911] BTM: attemping ,to re-attach in 1 seconds
,2016-08-31 08:50:44.689 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:44.690 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:44.690 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:45.692 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:45.693 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:45.693 ThaliTest[1325:2665911] BTM: attemping ,to re-attach in 1 seconds
,2016-08-31 08:50:46.694 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:46.695 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:46.695 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:47.696 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:47.697 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:47.698 ThaliTest[1325:2665911] BTM: attemping ,to re-attach in 1 seconds
,2016-08-31 08:50:48.699 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:48.700 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:48.700 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:49.701 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:49.703 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:49.703 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:50.704 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:50.710 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:50.711 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-08-31 08:50:51.169 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:51.184 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:51.184 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:51.712 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:51.715 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:51.715 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:52.186 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:52.188 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:52.189 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:52.717 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:52.719 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:52.720 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:53.190 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:53.192 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.193 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:53.721 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:53.724 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:53.724 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.194 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:54.197 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.198 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:54.726 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:54.729 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:54.729 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.199 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:55.202 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 08:50:55.202 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:55.731 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:55.734 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:55.734 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.204 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:56.207 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.207 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:56.736 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:56.738 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:56.739 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.209 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:57.211 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.212 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:57.740 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:57.743 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:57.743 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.213 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:58.216 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.217 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:58.745 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:58.748 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:58.749 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.218 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:50:59.220 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.221 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:50:59.750 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:50:59.753 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:50:59.753 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.222 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:00.225 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.226 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:00.755 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:00.758 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:00.758 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.288 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:51:01.289 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.289 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:01.760 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:01.761 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:01.761 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.290 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:02.293 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.293 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:02.762 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:02.765 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:02.765 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.295 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:03.298 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.298 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:03.767 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:03.770 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:03.770 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.300 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:51:04.302 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:04.303 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:04.772 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:04.774 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
,2016-08-31 08:51:04.775 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.304 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:05.307 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.307 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:05.776 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:05.779 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:05.780 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.309 ThaliTest[1325:2665911] BTM: attaching to BTServer
2016-08-31 08:51:06.311 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.312 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:06.781 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:06.784 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:06.784 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.313 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:07.316 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.317 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:07.786 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:07.789 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:07.789 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.318 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:08.321 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:08.321 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:08.791 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:08.793 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:08.794 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:09.323 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:09.326 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:09.326 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:09.796 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:09.798 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:09.798 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:10.328 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:10.330 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:10.331 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:10.800 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:10.803 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:10.803 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,2016-08-31 08:51:11.304 ThaliTest[1325:2665911] BTM: attaching to BTServer
,2016-08-31 08:51:11.308 ThaliTest[1325:2665911] BTM: session attach called back with BT_SESSION_ATTACHED (fffffed0)
2016-08-31 08:51:11.308 ThaliTest[1325:2665911] BTM: attemping to re-attach in 1 seconds
,Process 1325 stopped
* thread #16: tid = 0x28ae9e, 0x007b6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x007b6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String>:
->  0x7b6998 <+1188>: trap   
    0x7b699c <+1192>: trap   

ThaliCore`ThaliCore.TestRunner.runResult.getter : ThaliCore.TestRunner.RunResult:
    0x7b69a0 <+0>:    push   {r4, r5, r6, r7, lr}
    0x7b69a4 <+4>:    add    r7, sp, #12
,* thread #16: tid = 0x28ae9e, 0x007b6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x007b6998 ThaliCore`ThaliCore.TestRunner.resultDescription.getter : Swift.Optional<Swift.String> + 1188
    frame #1: 0x00054548 ThaliTest`@objc ThaliTest.AppContext.executeNativeTests () -> Swift.String + 60
    frame #2: 0x000524b6 ThaliTest`__44-[JXcoreExtension defineExecuteNativeTests:]_block_invoke + 250
    frame #3: 0x0004cd32 ThaliTest`callJXcoreNative + 660
    frame #4: 0x000b0dfa ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 268
    frame #5: 0x001ef3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #6: 0x00189928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #7: 0x001ef3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #8: 0x001ec998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #9: 0x001e847c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #10: 0x001ef452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #11: 0x00189928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #12: 0x001ef3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #13: 0x001ec998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #14: 0x001e847c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #15: 0x001ef452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #16: 0x00189928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #17: 0x001ef3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #18: 0x001ec998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #19: 0x001e847c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #20: 0x001ef452 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 384
    frame #21: 0x00189928 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 620
    frame #22: 0x001ef3b6 ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 228
    frame #23: 0x001ec998 ThaliTest`___lldb_unnamed_function987$$ThaliTest + 17664
    frame #24: 0x001e847c ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #25: 0x001efada ThaliTest`js::ExecuteKernel(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value const&, js::ExecuteType, js::AbstractFramePtr, JS::Value*) + 402
    frame #26: 0x001efbf2 ThaliTest`js::Execute(JSContext*, JS::Handle<JSScript*>, JSObject&, JS::Value*) + 136
    frame #27: 0x00172602 ThaliTest`___lldb_unnamed_function609$$ThaliTest + 20
    frame #28: 0x000cb364 ThaliTest`MozJS::Script::Run(MozJS::Value const&) + 88
    frame #29: 0x000cb3b8 ThaliTest`MozJS::Script::Run() + 44
    frame #30: 0x000b273c ThaliTest`jxcore::Evaluate_(char const*, char const*, _JXValue*, node::commons*) + 166
    frame #31: 0x000b12be ThaliTest`JX_Evaluate + 40
    frame #32: 0x0004f43c ThaliTest`__19+[JXcore Evaluate:]_block_invoke + 440
    frame #33: 0x0004d2c8 ThaliTest`+[JXcore threadMain] + 712
    frame #34: 0x2609336c Foundation`<redacted> + 1144
    frame #35: 0x374d6c7e libsystem_pthread.dylib`<redacted> + 138
    frame #36: 0x374d6bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #37: 0x374d4a08 libsystem_pthread.dylib`thread_start + 8

```
