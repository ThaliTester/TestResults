#### Test 83627337941f206_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D1E4B72-D014-4538-9727-8658E5FA254D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6D1E4B72-D014-4538-9727-8658E5FA254D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D0A3BEC6-9D29-4A69-A569-D5529E4755E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51047"
,(lldb)     command script import "/tmp/6D1E4B72-D014-4538-9727-8658E5FA254D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 12:31:56.826 ThaliTest[1377:2298613] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3A8B7443-AD45-45B0-8554-7AAAC44DE67B/Library/Cookies/Cookies.binarycookies
,2016-09-07 12:31:57.366 ThaliTest[1377:2298613] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 12:31:57.368 ThaliTest[1377:2298613] Multi-tasking -> Device: YES, App: YES
,2016-09-07 12:31:57.390 ThaliTest[1377:2298613] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 12:31:59.717 ThaliTest[1377:2298613] Using UIWebView
,2016-09-07 12:31:59.727 ThaliTest[1377:2298613] [CDVTimer][handleopenurl] 0.431001ms
,2016-09-07 12:31:59.736 ThaliTest[1377:2298613] [CDVTimer][intentandnavigationfilter] 8.104026ms
2016-09-07 12:31:59.737 ThaliTest[1377:2298613] [CDVTimer][gesturehandler] 0.404954ms
2016-09-07 12:31:59.737 ThaliTest[1377:2298613] [CDVTimer][TotalPluginStartup] 10.670006ms
,2016-09-07 12:32:07.108 ThaliTest[1377:2298613] Resetting plugins due to page load.
,2016-09-07 12:32:10.951 ThaliTest[1377:2298613] Finished load of: file:///var/mobile/Containers/Bundle/Application/D0A3BEC6-9D29-4A69-A569-D5529E4755E1/ThaliTest.app/www/index.html
,2016-09-07 12:32:11.251 ThaliTest[1377:2298613] JXcore Cordova plugin initializing
,2016-09-07 12:32:11.252 ThaliTest[1377:2298874] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 12:32:18.218 ThaliTest[1377:2298874] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 12:32:18.219 ThaliTest[1377:2298874] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 12:32:18.219 ThaliTest[1377:2,298874] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 12:32:18.221 ThaliTest[1377:2298874] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
