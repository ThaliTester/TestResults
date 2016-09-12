#### Test 8362733705cfec3_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6FD15B7A-7E7D-4E9F-A4BC-FBD67847099D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6FD15B7A-7E7D-4E9F-A4BC-FBD67847099D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B1FAFC9D-BD39-44CF-A144-758B813ED5A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56692"
,(lldb)     command script import "/tmp/6FD15B7A-7E7D-4E9F-A4BC-FBD67847099D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-12 13:55:36.503 ThaliTest[397:476595] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B4F70D9E-15C5-404A-857D-FE905F69DAFD/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:55:36.811 ThaliTest[397:476595] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:55:36.813 ThaliTest[397:476595] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:55:36.838 ThaliTest[397:476595] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:55:37.340 ThaliTest[397:476595] Using UIWebView
,2016-09-12 13:55:37.346 ThaliTest[397:476595] [CDVTimer][handleopenurl] 0.517011ms
,2016-09-12 13:55:37.354 ThaliTest[397:476595] [CDVTimer][intentandnavigationfilter] 7.201016ms
2016-09-12 13:55:37.355 ThaliTest[397:476595] [CDVTimer][gesturehandler] 0.328004ms
2016-09-12 13:55:37.355 ThaliTest[397:476595] [CDVTimer][TotalPluginStartup] 9.598970ms
,2016-09-12 13:55:43.224 ThaliTest[397:476595] Resetting plugins due to page load.
,2016-09-12 13:55:43.674 ThaliTest[397:476595] Finished load of: file:///var/containers/Bundle/Application/B1FAFC9D-BD39-44CF-A144-758B813ED5A4/ThaliTest.app/www/index.html
,2016-09-12 13:55:44.067 ThaliTest[397:476595] JXcore Cordova plugin initializing
,2016-09-12 13:55:44.067 ThaliTest[397:476783] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 13:55:50.788 ThaliTest[397:476783] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-12 13:55:50.788 ThaliTest[397:476783] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-12 13:55:50.789 ThaliTest[397:476783] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-12 13:55:50.791 ThaliTest[397:476783] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
