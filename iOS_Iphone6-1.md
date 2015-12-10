#### Test 506502784dae475_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/4CD86FF7-1470-4DCE-A2D8-C37C4F5B56B6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4CD86FF7-1470-4DCE-A2D8-C37C4F5B56B6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/231176C7-0886-4CC6-9AB7-18263D553807/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53244"
,(lldb)     command script import "/tmp/4CD86FF7-1470-4DCE-A2D8-C37C4F5B56B6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 13:35:27.449 ThaliTest[679:567701] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF0E7F3D-5800-4D63-A287-C5D4C0495D99/Library/Cookies/Cookies.binarycookies
,2015-12-10 13:35:27.805 ThaliTest[679:567701] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 13:35:27.806 ThaliTest[679:567701] Multi-tasking -> Device: YES, App: YES
,2015-12-10 13:35:27.815 ThaliTest[679:567701] Unlimited access to network resources
,2015-12-10 13:35:27.824 ThaliTest[679:567701] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 13:35:36.719 ThaliTest[679:567701] Resetting plugins due to page load.
,2015-12-10 13:35:40.141 ThaliTest[679:567701] Finished load of: file:///var/mobile/Containers/Bundle/Application/231176C7-0886-4CC6-9AB7-18263D553807/ThaliTest.app/www/index.html
,2015-12-10 13:35:40.322 ThaliTest[679:567701] JXcore Cordova plugin initializing
,2015-12-10 13:35:40.324 ThaliTest[679:567910] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
