#### Test 50650278e989a4f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D0349A9F-7C36-432D-B3CC-E71415EAEC4C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D0349A9F-7C36-432D-B3CC-E71415EAEC4C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A24D127F-3848-4F71-B9DE-7521B6A2E2AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58211"
,(lldb)     command script import "/tmp/D0349A9F-7C36-432D-B3CC-E71415EAEC4C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 03:29:06.516 ThaliTest[252:36776] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C8E72260-3EA3-4104-B8C1-CC80643E3616/Library/Cookies/Cookies.binarycookies
,2015-12-16 03:29:06.891 ThaliTest[252:36776] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 03:29:06.892 ThaliTest[252:36776] Multi-tasking -> Device: YES, App: YES
,2015-12-16 03:29:06.902 ThaliTest[252:36776] Unlimited access to network resources
,2015-12-16 03:29:06.913 ThaliTest[252:36776] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 03:29:16.067 ThaliTest[252:36776] Resetting plugins due to page load.
,2015-12-16 03:29:19.498 ThaliTest[252:36776] Finished load of: file:///var/mobile/Containers/Bundle/Application/A24D127F-3848-4F71-B9DE-7521B6A2E2AF/ThaliTest.app/www/index.html
,2015-12-16 03:29:19.678 ThaliTest[252:36776] JXcore Cordova plugin initializing
,2015-12-16 03:29:19.680 ThaliTest[252:36990] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 03:29:20.780 ThaliTest[252:36776] THREAD WARNING: ['JXcore'] took '76.965820' ms. Plugin should use a background thread.
,Connected to the server!

```
