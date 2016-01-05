#### Test 549702617d40def_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/55501185-1628-462F-ADD7-53234433B485/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/55501185-1628-462F-ADD7-53234433B485/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BF710821-DDBE-43C9-954D-2348496F5BE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64741"
,(lldb)     command script import "/tmp/55501185-1628-462F-ADD7-53234433B485/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 02:19:24.984 ThaliTest[1278:2731589] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/505B0BFE-A6D3-4259-9725-6F01CE20C557/Library/Cookies/Cookies.binarycookies
,2016-01-05 02:19:25.347 ThaliTest[1278:2731589] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 02:19:25.349 ThaliTest[1278:2731589] Multi-tasking -> Device: YES, App: YES
,2016-01-05 02:19:25.358 ThaliTest[1278:2731589] Unlimited access to network resources
,2016-01-05 02:19:25.367 ThaliTest[1278:2731589] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 02:19:34.767 ThaliTest[1278:2731589] Resetting plugins due to page load.
,2016-01-05 02:19:38.151 ThaliTest[1278:2731589] Finished load of: file:///var/mobile/Containers/Bundle/Application/BF710821-DDBE-43C9-954D-2348496F5BE7/ThaliTest.app/www/index.html
,2016-01-05 02:19:38.337 ThaliTest[1278:2731589] JXcore Cordova plugin initializing
,2016-01-05 02:19:38.339 ThaliTest[1278:2731787] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
