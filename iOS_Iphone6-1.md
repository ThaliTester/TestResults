#### Test 8362733795b1a33_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AA89C862-7CD1-4429-A784-42DB297B3C5B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AA89C862-7CD1-4429-A784-42DB297B3C5B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3A596A82-2428-4F0E-9ECF-2B542A855188/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64769"
,(lldb)     command script import "/tmp/AA89C862-7CD1-4429-A784-42DB297B3C5B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-13 16:07:46.559 ThaliTest[506:613968] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7F3C3F1A-8F3F-4FD8-B083-582E4108B0E8/Library/Cookies/Cookies.binarycookies
,2016-09-13 16:07:46.862 ThaliTest[506:613968] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 16:07:46.864 ThaliTest[506:613968] Multi-tasking -> Device: YES, App: YES
,2016-09-13 16:07:46.885 ThaliTest[506:613968] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 16:07:47.376 ThaliTest[506:613968] Using UIWebView
,2016-09-13 16:07:47.383 ThaliTest[506:613968] [CDVTimer][handleopenurl] 0.398040ms
,2016-09-13 16:07:47.391 ThaliTest[506:613968] [CDVTimer][intentandnavigationfilter] 7.335961ms
2016-09-13 16:07:47.392 ThaliTest[506:613968] [CDVTimer][gesturehandler] 0.371993ms
2016-09-13 16:07:47.392 ThaliTest[506:613968] [CDVTimer][TotalPluginStartup,] 9.790957ms
,2016-09-13 16:07:52.565 ThaliTest[506:613968] Resetting plugins due to page load.
,2016-09-13 16:07:52.896 ThaliTest[506:613968] Finished load of: file:///var/containers/Bundle/Application/3A596A82-2428-4F0E-9ECF-2B542A855188/ThaliTest.app/www/index.html
,2016-09-13 16:07:53.234 ThaliTest[506:613968] JXcore Cordova plugin initializing
,2016-09-13 16:07:53.235 ThaliTest[506:614153] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 16:07:59.924 ThaliTest[506:614153] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 16:07:59.925 ThaliTest[506:614153] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 16:07:59.925 ThaliTest[506:614153] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 16:07:59.927 ThaliTest[506:614153] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
