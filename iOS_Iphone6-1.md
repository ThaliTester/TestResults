#### Test 75789268eab05ed_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/CF70AF5A-F40B-451D-B25D-2A97CFC843CF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CF70AF5A-F40B-451D-B25D-2A97CFC843CF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/054F22E8-39AA-4479-A891-083127AE6826/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49831"
,(lldb)     command script import "/tmp/CF70AF5A-F40B-451D-B25D-2A97CFC843CF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:05:44.295 ThaliTest[6282:19666065] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1447FF8-0E24-433B-A504-F35A0BB1D3EF/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:05:44.527 ThaliTest[6282:19666065] Apache Cordova native platform version 4.1.1 is starting.
2016-07-05 11:05:44.528 ThaliTest[6282:19666065] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:05:44.544 ThaliTest[6282:19666065] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:05:45.327 ThaliTest[6282:19666065] Using UIWebView
2016-07-05 11:05:45.329 ThaliTest[6282:19666065] [CDVTimer][handleopenurl] 0.127971ms
2016-07-05 11:05:45.332 ThaliTest[6282:19666065] [CDVTimer][intentandnavigationfilter] 2.147019ms
2016-07-05 11:05:45.332 ThaliTest[6282:19666065] [CDVTimer][gesturehandler] 0.097990ms
2016-07-05 11:05:45.332 ThaliTest[6282:19666065] [CDVTimer][TotalPluginStartup] 2.804995ms
,2016-07-05 11:05:48.459 ThaliTest[6282:19666065] Resetting plugins due to page load.
,2016-07-05 11:05:49.874 ThaliTest[6282:19666065] Finished load of: file:///var/mobile/Containers/Bundle/Application/054F22E8-39AA-4479-A891-083127AE6826/ThaliTest.app/www/index.html
,2016-07-05 11:05:50.024 ThaliTest[6282:19666065] JXcore Cordova plugin initializing
,2016-07-05 11:05:50.025 ThaliTest[6282:19666215] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
