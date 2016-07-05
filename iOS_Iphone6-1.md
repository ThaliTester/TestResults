#### Test 757892685fc4836_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0ED94235-0377-46FD-9514-EEF72115494F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0ED94235-0377-46FD-9514-EEF72115494F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A294DE8-8146-4D1C-90FC-B5A4478CC796/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50431"
,(lldb)     command script import "/tmp/0ED94235-0377-46FD-9514-EEF72115494F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 15:35:05.258 ThaliTest[6334:19707800] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6ABE8BC2-7E7C-49B1-9B56-7E2F1D76709D/Library/Cookies/Cookies.binarycookies
,2016-07-05 15:35:05.488 ThaliTest[6334:19707800] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 15:35:05.489 ThaliTest[6334:19707800] Multi-tasking -> Device: YES, App: YES
,2016-07-05 15:35:05.504 ThaliTest[6334:19707800] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 15:35:06.297 ThaliTest[6334:19707800] Using UIWebView
2016-07-05 15:35:06.299 ThaliTest[6334:19707800] [CDVTimer][handleopenurl] 0.127017ms
2016-07-05 15:35:06.302 ThaliTest[6334:19707800] [CDVTimer][intentandnavigationfilter] 2.274990ms
2016-07-05 15:35:06.302 ThaliTest[6334:19707800] [CDVTimer][gesturehandler] 0.104010ms
2016-07-05 15:35:06.302 ThaliTest[6334:19707800] [CDVTimer][TotalPluginStartup] 2.940059ms
,2016-07-05 15:35:09.442 ThaliTest[6334:19707800] Resetting plugins due to page load.
,2016-07-05 15:35:10.874 ThaliTest[6334:19707800] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A294DE8-8146-4D1C-90FC-B5A4478CC796/ThaliTest.app/www/index.html
,2016-07-05 15:35:11.032 ThaliTest[6334:19707800] JXcore Cordova plugin initializing
2016-07-05 15:35:11.033 ThaliTest[6334:19707959] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
