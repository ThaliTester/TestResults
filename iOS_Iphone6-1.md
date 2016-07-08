#### Test 75789268d2ecd3a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BF1375B0-70D3-448F-9449-7AA9693F7A29/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BF1375B0-70D3-448F-9449-7AA9693F7A29/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/72906C07-E08B-4A02-991C-1ADCD2FD448C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51894"
,(lldb)     command script import "/tmp/BF1375B0-70D3-448F-9449-7AA9693F7A29/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-08 13:59:16.868 ThaliTest[6505:20173213] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F0DAB0C-FD6F-4EAA-AA3E-186EA124B56C/Library/Cookies/Cookies.binarycookies
,2016-07-08 13:59:17.100 ThaliTest[6505:20173213] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-08 13:59:17.101 ThaliTest[6505:20173213] Multi-tasking -> Device: YES, App: YES
,2016-07-08 13:59:17.116 ThaliTest[6505:20173213] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-08 13:59:17.902 ThaliTest[6505:20173213] Using UIWebView
2016-07-08 13:59:17.904 ThaliTest[6505:20173213] [CDVTimer][handleopenurl] 0.165999ms
2016-07-08 13:59:17.906 ThaliTest[6505:20173213] [CDVTimer][intentandnavigationfilter] 2.319038ms
2016,-07-08 13:59:17.906 ThaliTest[6505:20173213] [CDVTimer][gesturehandler] 0.108004ms
2016-07-08 13:59:17.907 ThaliTest[6505:20173213] [CDVTimer][TotalPluginStartup] 3.035963ms
,2016-07-08 13:59:21.084 ThaliTest[6505:20173213] Resetting plugins due to page load.
,2016-07-08 13:59:22.498 ThaliTest[6505:20173213] Finished load of: file:///var/mobile/Containers/Bundle/Application/72906C07-E08B-4A02-991C-1ADCD2FD448C/ThaliTest.app/www/index.html
,2016-07-08 13:59:22.646 ThaliTest[6505:20173213] JXcore Cordova plugin initializing
,2016-07-08 13:59:22.727 ThaliTest[6505:20173362] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
