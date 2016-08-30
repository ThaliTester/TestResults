#### Test 7976383051d2164_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/42C792A4-7A56-45C1-B767-0E1E836261E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/42C792A4-7A56-45C1-B767-0E1E836261E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4964405D-17FD-42B6-9C3A-C289F18EA37F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50528"
,(lldb)     command script import "/tmp/42C792A4-7A56-45C1-B767-0E1E836261E3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 11:35:25.769 ThaliTest[807:1119670] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/022C22F0-C3B1-42B1-A221-4D46D796A34B/Library/Cookies/Cookies.binarycookies
,2016-08-30 11:35:26.196 ThaliTest[807:1119670] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 11:35:26.198 ThaliTest[807:1119670] Multi-tasking -> Device: YES, App: YES
,2016-08-30 11:35:26.222 ThaliTest[807:1119670] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 11:35:27.986 ThaliTest[807:1119670] Using UIWebView
,2016-08-30 11:35:27.993 ThaliTest[807:1119670] [CDVTimer][handleopenurl] 0.419021ms
,2016-08-30 11:35:28.001 ThaliTest[807:1119670] [CDVTimer][intentandnavigationfilter] 7.391989ms
2016-08-30 11:35:28.002 ThaliTest[807:1119670] [CDVTimer][gesturehandler] 0.356972ms
2016-08-30 11:35:28.002 ThaliTest[807:1119670] [CDVTimer][TotalPluginStartup] 9.847999ms
,2016-08-30 11:35:33.984 ThaliTest[807:1119670] Resetting plugins due to page load.
,2016-08-30 11:35:36.943 ThaliTest[807:1119670] Finished load of: file:///var/mobile/Containers/Bundle/Application/4964405D-17FD-42B6-9C3A-C289F18EA37F/ThaliTest.app/www/index.html
,2016-08-30 11:35:37.172 ThaliTest[807:1119670] JXcore Cordova plugin initializing
2016-08-30 11:35:37.173 ThaliTest[807:1119922] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 11:35:44.064 ThaliTest[807:1119922] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 11:35:44.064 ThaliTest[807:1119922] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 11:35:44.064 ThaliTest[807:1119,922] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 11:35:44.066 ThaliTest[807:1119922] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 11:35:44.391 ThaliTest[807:1119922] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003652989864349365
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
