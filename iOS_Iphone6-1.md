#### Test 83276082d331142_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9C4FF271-6738-4687-A796-8AD2DBBD9DF8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9C4FF271-6738-4687-A796-8AD2DBBD9DF8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/20111B8A-4E3C-4497-820B-1DCDE6ED6586/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49927"
,(lldb)     command script import "/tmp/9C4FF271-6738-4687-A796-8AD2DBBD9DF8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 13:29:29.488 ThaliTest[698:859744] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5152C130-9BCF-4362-B5EC-8C6B2DA9162D/Library/Cookies/Cookies.binarycookies
,2016-09-15 13:29:29.811 ThaliTest[698:859744] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 13:29:29.813 ThaliTest[698:859744] Multi-tasking -> Device: YES, App: YES
,2016-09-15 13:29:29.838 ThaliTest[698:859744] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 13:29:30.346 ThaliTest[698:859744] Using UIWebView
,2016-09-15 13:29:30.352 ThaliTest[698:859744] [CDVTimer][handleopenurl] 0.406981ms
,2016-09-15 13:29:30.360 ThaliTest[698:859744] [CDVTimer][intentandnavigationfilter] 7.026970ms
2016-09-15 13:29:30.361 ThaliTest[698:859744] [CDVTimer][gesturehandler] 0.330985ms
2016-09-15 13:29:30.361 ThaliTest[698:859744] [CDVTimer][TotalPluginStartup,] 9.377003ms
,2016-09-15 13:29:35.583 ThaliTest[698:859744] Resetting plugins due to page load.
,2016-09-15 13:29:35.876 ThaliTest[698:859744] Finished load of: file:///var/containers/Bundle/Application/20111B8A-4E3C-4497-820B-1DCDE6ED6586/ThaliTest.app/www/index.html
,2016-09-15 13:29:36.251 ThaliTest[698:859744] JXcore Cordova plugin initializing
2016-09-15 13:29:36.252 ThaliTest[698:859925] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 13:29:42.987 ThaliTest[698:859925] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 13:29:42.988 ThaliTest[698:859925] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 13:29:42.988 ThaliTest[698:859925,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 13:29:42.991 ThaliTest[698:859925] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
