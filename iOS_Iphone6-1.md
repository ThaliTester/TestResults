#### Test 8504691174f7534_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/94BBB97F-C83C-495F-8BD3-FA8A31A75863/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/94BBB97F-C83C-495F-8BD3-FA8A31A75863/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2510F216-4F34-4A6A-9DED-C014371A1A8E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58588"
,(lldb)     command script import "/tmp/94BBB97F-C83C-495F-8BD3-FA8A31A75863/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 12:00:35.231 ThaliTest[690:851603] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1B992C36-434B-48C6-BB87-A092D5E0E569/Library/Cookies/Cookies.binarycookies
,2016-09-15 12:00:35.416 ThaliTest[690:851603] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 12:00:35.417 ThaliTest[690:851603] Multi-tasking -> Device: YES, App: YES
,2016-09-15 12:00:35.434 ThaliTest[690:851603] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 12:00:35.764 ThaliTest[690:851603] Using UIWebView
,2016-09-15 12:00:35.768 ThaliTest[690:851603] [CDVTimer][handleopenurl] 0.398040ms
,2016-09-15 12:00:35.774 ThaliTest[690:851603] [CDVTimer][intentandnavigationfilter] 5.046010ms
2016-09-15 12:00:35.774 ThaliTest[690:851603] [CDVTimer][gesturehandler] 0.226021ms
2016-09-15 12:00:35.775 ThaliTest[690:851603] [CDVTimer][TotalPluginStartup,] 6.742001ms
,2016-09-15 12:00:40.756 ThaliTest[690:851603] Resetting plugins due to page load.
,2016-09-15 12:00:41.086 ThaliTest[690:851603] Finished load of: file:///var/containers/Bundle/Application/2510F216-4F34-4A6A-9DED-C014371A1A8E/ThaliTest.app/www/index.html
,2016-09-15 12:00:41.430 ThaliTest[690:851603] JXcore Cordova plugin initializing
2016-09-15 12:00:41.431 ThaliTest[690:851787] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 12:00:48.082 ThaliTest[690:851787] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 12:00:48.082 ThaliTest[690:851787] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 12:00:48.082 ThaliTest[690:851787] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 12:00:48.084 ThaliTest[690:851787] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 12:00:48.474 ThaliTest[690:851787] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003643989562988281
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
