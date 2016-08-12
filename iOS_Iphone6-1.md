#### Test 81095569a7966ce_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E7628A90-4C90-4460-A5B4-42DA21F52D32/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E7628A90-4C90-4460-A5B4-42DA21F52D32/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569a7966ce/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4168B6D-08B6-4CF1-A82D-220A1A5A8489/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49225"
,(lldb)     command script import "/tmp/E7628A90-4C90-4460-A5B4-42DA21F52D32/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 14:10:03.180 ThaliTest[255:28189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69B75EF4-6BA6-4B31-B1E7-7E2595545764/Library/Cookies/Cookies.binarycookies
,2016-08-12 14:10:03.597 ThaliTest[255:28189] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 14:10:03.599 ThaliTest[255:28189] Multi-tasking -> Device: YES, App: YES
,2016-08-12 14:10:03.621 ThaliTest[255:28189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 14:10:05.494 ThaliTest[255:28189] Using UIWebView
,2016-08-12 14:10:05.501 ThaliTest[255:28189] [CDVTimer][handleopenurl] 0.445008ms
,2016-08-12 14:10:05.509 ThaliTest[255:28189] [CDVTimer][intentandnavigationfilter] 7.781982ms
2016-08-12 14:10:05.510 ThaliTest[255:28189] [CDVTimer][gesturehandler] 0.369966ms
2016-08-12 14:10:05.510 ThaliTest[255:28189] [CDVTimer][TotalPluginStartup] 10.338962ms
,2016-08-12 14:10:12.845 ThaliTest[255:28189] Resetting plugins due to page load.
,2016-08-12 14:10:16.168 ThaliTest[255:28189] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4168B6D-08B6-4CF1-A82D-220A1A5A8489/ThaliTest.app/www/index.html
,2016-08-12 14:10:16.415 ThaliTest[255:28189] JXcore Cordova plugin initializing
,2016-08-12 14:10:16.416 ThaliTest[255:28411] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 14:10:23.973 ThaliTest[255:28411] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-12 14:10:23.974 ThaliTest[255:28411] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-12 14:10:23.974 ThaliTest[255:28411] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-12 14:10:23.976 ThaliTest[255:28411] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-12 14:10:24.277 ThaliTest[255:28411] Native method ExecuteNativeTests not found.
,Is Android:  false
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
