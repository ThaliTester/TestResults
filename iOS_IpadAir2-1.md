#### Test 81095569a7966ce_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/422FA8EA-D401-4F68-9ED7-85C62EE482BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/422FA8EA-D401-4F68-9ED7-85C62EE482BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B9DE3773-8FB0-4919-96BB-BEBF16CAF966/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49223"
,(lldb)     command script import "/tmp/422FA8EA-D401-4F68-9ED7-85C62EE482BF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 14:09:53.302 ThaliTest[227:25839] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41AEAD70-04B3-449A-A442-CE6FB85F9F42/Library/Cookies/Cookies.binarycookies
,2016-08-12 14:09:53.543 ThaliTest[227:25839] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 14:09:53.544 ThaliTest[227:25839] Multi-tasking -> Device: YES, App: YES
,2016-08-12 14:09:53.557 ThaliTest[227:25839] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 14:09:54.383 ThaliTest[227:25839] Using UIWebView
,2016-08-12 14:09:54.386 ThaliTest[227:25839] [CDVTimer][handleopenurl] 0.105977ms
,2016-08-12 14:09:54.388 ThaliTest[227:25839] [CDVTimer][intentandnavigationfilter] 1.827002ms
2016-08-12 14:09:54.388 ThaliTest[227:25839] [CDVTimer][gesturehandler] 0.082970ms
,2016-08-12 14:09:54.388 ThaliTest[227:25839] [CDVTimer][TotalPluginStartup] 2.458990ms
,2016-08-12 14:09:57.682 ThaliTest[227:25839] Resetting plugins due to page load.
,2016-08-12 14:09:58.980 ThaliTest[227:25839] Finished load of: file:///var/mobile/Containers/Bundle/Application/B9DE3773-8FB0-4919-96BB-BEBF16CAF966/ThaliTest.app/www/index.html
,2016-08-12 14:09:59.113 ThaliTest[227:25839] JXcore Cordova plugin initializing
,2016-08-12 14:09:59.113 ThaliTest[227:26007] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 14:10:05.728 ThaliTest[227:26007] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-12 14:10:05.728 ThaliTest[227:26007] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-12 14:10:05.728 ThaliTest[227:26007] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-08-12 14:10:05.730 ThaliTest[227:26007] jxcore: didRegisterToNative incomingCo,nnectionToPortNumberFailed
,2016-08-12 14:10:06.007 ThaliTest[227:26007] Native method ExecuteNativeTests not found.
Is Android:  false
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
