#### Test 81095569d4ae196_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/32789356-C9EA-4539-8EF9-95C528CF9384/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
Executing commands in '/tmp/32789356-C9EA-4539-8EF9-95C528CF9384/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FF579959-C745-49F6-8E8D-DA04170A66BC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61459"
,(lldb)     command script import "/tmp/32789356-C9EA-4539-8EF9-95C528CF9384/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 12:47:53.680 ThaliTest[240:18625] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A983CE84-4B6C-4565-BBE3-43EC235270B0/Library/Cookies/Cookies.binarycookies
,2016-08-12 12:47:54.133 ThaliTest[240:18625] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 12:47:54.135 ThaliTest[240:18625] Multi-tasking -> Device: YES, App: YES
,2016-08-12 12:47:54.170 ThaliTest[240:18625] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 12:47:56.050 ThaliTest[240:18625] Using UIWebView
,2016-08-12 12:47:56.056 ThaliTest[240:18625] [CDVTimer][handleopenurl] 0.292003ms
,2016-08-12 12:47:56.062 ThaliTest[240:18625] [CDVTimer][intentandnavigationfilter] 5.433977ms
2016-08-12 12:47:56.063 ThaliTest[240:18625] [CDVTimer][gesturehandler] 0.214040ms
2016-08-12 12:47:56.063 ThaliTest[240:18625] [CDVTimer][TotalPluginStartup] 7.036984ms
,2016-08-12 12:48:02.855 ThaliTest[240:18625] Resetting plugins due to page load.
,2016-08-12 12:48:05.834 ThaliTest[240:18625] Finished load of: file:///var/mobile/Containers/Bundle/Application/FF579959-C745-49F6-8E8D-DA04170A66BC/ThaliTest.app/www/index.html
,2016-08-12 12:48:06.109 ThaliTest[240:18625] JXcore Cordova plugin initializing
,2016-08-12 12:48:06.110 ThaliTest[240:18844] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 12:48:13.672 ThaliTest[240:18844] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-12 12:48:13.672 ThaliTest[240:18844] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-12 12:48:13.673 ThaliTest[240:18844] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-12 12:48:13.674 ThaliTest[240:18844] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-12 12:48:13.976 ThaliTest[240:18844] Native method ExecuteNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
