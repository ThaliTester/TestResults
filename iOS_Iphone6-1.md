#### Test 83627337140e0c5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/18801876-AE7D-4248-833E-B6F6266A6660/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/18801876-AE7D-4248-833E-B6F6266A6660/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/29A0777D-894B-4F7E-9936-000223B1ED00/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59962"
,(lldb)     command script import "/tmp/18801876-AE7D-4248-833E-B6F6266A6660/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:04:55.892 ThaliTest[1335:2272122] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7A9C2256-A262-48CD-9C8E-E19DF537BB40/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:04:56.327 ThaliTest[1335:2272122] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:04:56.329 ThaliTest[1335:2272122] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:04:56.354 ThaliTest[1335:2272122] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:04:58.285 ThaliTest[1335:2272122] Using UIWebView
,2016-09-07 09:04:58.293 ThaliTest[1335:2272122] [CDVTimer][handleopenurl] 0.548005ms
,2016-09-07 09:04:58.301 ThaliTest[1335:2272122] [CDVTimer][intentandnavigationfilter] 7.454991ms
2016-09-07 09:04:58.302 ThaliTest[1335:2272122] [CDVTimer][gesturehandler] 0.388026ms
2016-09-07 09:04:58.302 ThaliTest[1335:2272122] [CDVTimer][TotalPluginS,tartup] 10.264039ms
,2016-09-07 09:05:04.861 ThaliTest[1335:2272122] Resetting plugins due to page load.
,2016-09-07 09:05:07.373 ThaliTest[1335:2272122] Finished load of: file:///var/mobile/Containers/Bundle/Application/29A0777D-894B-4F7E-9936-000223B1ED00/ThaliTest.app/www/index.html
,2016-09-07 09:05:07.672 ThaliTest[1335:2272122] JXcore Cordova plugin initializing
2016-09-07 09:05:07.673 ThaliTest[1335:2272344] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:05:14.602 ThaliTest[1335:2272344] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 09:05:14.602 ThaliTest[1335:2272344] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:05:14.603 ThaliTest[1335:2272344] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 09:05:14.605 ThaliTest[1335:2272344] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
