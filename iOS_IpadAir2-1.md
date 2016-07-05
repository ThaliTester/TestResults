#### Test 757892685fc4836_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B3411A08-C7BA-4F46-99F4-4068C9D18066/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B3411A08-C7BA-4F46-99F4-4068C9D18066/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AF4A9743-26E7-41FC-9CFA-E3B3A4647BC8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50429"
,(lldb)     command script import "/tmp/B3411A08-C7BA-4F46-99F4-4068C9D18066/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 15:35:06.022 ThaliTest[3698:13611685] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE8FB4B3-C19F-4557-84DB-C35E4A28BACD/Library/Cookies/Cookies.binarycookies
,2016-07-05 15:35:06.251 ThaliTest[3698:13611685] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 15:35:06.252 ThaliTest[3698:13611685] Multi-tasking -> Device: YES, App: YES
,2016-07-05 15:35:06.264 ThaliTest[3698:13611685] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 15:35:07.073 ThaliTest[3698:13611685] Using UIWebView
,2016-07-05 15:35:07.075 ThaliTest[3698:13611685] [CDVTimer][handleopenurl] 0.106990ms
,2016-07-05 15:35:07.077 ThaliTest[3698:13611685] [CDVTimer][intentandnavigationfilter] 1.841962ms
2016-07-05 15:35:07.077 ThaliTest[3698:13611685] [CDVTimer][gesturehandler] 0.081003ms
2016-07-05 15:35:07.077 ThaliTest[3698:13611685] [CDVTimer][TotalPlug,inStartup] 2.460003ms
,2016-07-05 15:35:10.360 ThaliTest[3698:13611685] Resetting plugins due to page load.
,2016-07-05 15:35:11.799 ThaliTest[3698:13611685] Finished load of: file:///var/mobile/Containers/Bundle/Application/AF4A9743-26E7-41FC-9CFA-E3B3A4647BC8/ThaliTest.app/www/index.html
,2016-07-05 15:35:11.936 ThaliTest[3698:13611685] JXcore Cordova plugin initializing
2016-07-05 15:35:11.936 ThaliTest[3698:13611852] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
