#### Test 79763830e2067e4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2EC067FE-FDAE-47C8-A7BC-C8CBD32324E8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2EC067FE-FDAE-47C8-A7BC-C8CBD32324E8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5CF2720C-DA8A-4745-9925-059BE2399A17/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53335"
,(lldb)     command script import "/tmp/2EC067FE-FDAE-47C8-A7BC-C8CBD32324E8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 14:15:51.768 ThaliTest[534:577069] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A8B095D7-21C6-451F-B66B-DE64C3430CAC/Library/Cookies/Cookies.binarycookies
,2016-08-26 14:15:52.163 ThaliTest[534:577069] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 14:15:52.165 ThaliTest[534:577069] Multi-tasking -> Device: YES, App: YES
,2016-08-26 14:15:52.191 ThaliTest[534:577069] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 14:15:54.054 ThaliTest[534:577069] Using UIWebView
,2016-08-26 14:15:54.062 ThaliTest[534:577069] [CDVTimer][handleopenurl] 0.562012ms
,2016-08-26 14:15:54.070 ThaliTest[534:577069] [CDVTimer][intentandnavigationfilter] 7.462978ms
2016-08-26 14:15:54.071 ThaliTest[534:577069] [CDVTimer][gesturehandler] 0.374973ms
2016-08-26 14:15:54.071 ThaliTest[534:577069] [CDVTimer][TotalPluginStartup] 10.204971ms
,2016-08-26 14:16:00.323 ThaliTest[534:577069] Resetting plugins due to page load.
,2016-08-26 14:16:03.221 ThaliTest[534:577069] Finished load of: file:///var/mobile/Containers/Bundle/Application/5CF2720C-DA8A-4745-9925-059BE2399A17/ThaliTest.app/www/index.html
,2016-08-26 14:16:03.455 ThaliTest[534:577069] JXcore Cordova plugin initializing
,2016-08-26 14:16:03.456 ThaliTest[534:577296] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 14:16:10.382 ThaliTest[534:577296] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 14:16:10.383 ThaliTest[534:577296] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 14:16:10.384 ThaliTest[534:577296] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 14:16:10.385 ThaliTest[534:577296] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 14:16:10.713 ThaliTest[534:577296] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  0.01121199131011963
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
