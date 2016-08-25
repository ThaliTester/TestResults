#### Test 797638306764640_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B9FDE973-B9E3-4B87-800F-90994FB8BCBA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B9FDE973-B9E3-4B87-800F-90994FB8BCBA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8AE26747-1FBE-4849-90DF-E7A1DEB970EF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50643"
,(lldb)     command script import "/tmp/B9FDE973-B9E3-4B87-800F-90994FB8BCBA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 15:23:42.551 ThaliTest[421:438486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DEDE2ECF-1ACA-4039-B2F4-A91FE078ED33/Library/Cookies/Cookies.binarycookies
,2016-08-25 15:23:42.983 ThaliTest[421:438486] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 15:23:42.985 ThaliTest[421:438486] Multi-tasking -> Device: YES, App: YES
,2016-08-25 15:23:43.009 ThaliTest[421:438486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 15:23:44.718 ThaliTest[421:438486] Using UIWebView
,2016-08-25 15:23:44.725 ThaliTest[421:438486] [CDVTimer][handleopenurl] 0.618994ms
,2016-08-25 15:23:44.733 ThaliTest[421:438486] [CDVTimer][intentandnavigationfilter] 7.286966ms
2016-08-25 15:23:44.734 ThaliTest[421:438486] [CDVTimer][gesturehandler] 0.320017ms
2016-08-25 15:23:44.734 ThaliTest[421:438486] [CDVTimer][TotalPluginStartup,] 9.836972ms
,2016-08-25 15:23:51.072 ThaliTest[421:438486] Resetting plugins due to page load.
,2016-08-25 15:23:54.087 ThaliTest[421:438486] Finished load of: file:///var/mobile/Containers/Bundle/Application/8AE26747-1FBE-4849-90DF-E7A1DEB970EF/ThaliTest.app/www/index.html
,2016-08-25 15:23:54.318 ThaliTest[421:438486] JXcore Cordova plugin initializing
,2016-08-25 15:23:54.319 ThaliTest[421:438738] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 15:24:01.188 ThaliTest[421:438738] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-25 15:24:01.188 ThaliTest[421:438738] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-25 15:24:01.189 ThaliTest[421:438738] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 15:24:01.190 ThaliTest[421:438738] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 15:24:01.544 ThaliTest[421:438738] jxcore: executeNativeTests: success
Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01164400577545166
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
