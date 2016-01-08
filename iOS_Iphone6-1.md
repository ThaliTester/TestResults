#### Test 54970261ac9928f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A97EBCA4-FE23-4CD3-9398-7817FBC57707/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A97EBCA4-FE23-4CD3-9398-7817FBC57707/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DC8E7AB5-C411-4FB9-9FC9-E6EF067510B8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50570"
,(lldb)     command script import "/tmp/A97EBCA4-FE23-4CD3-9398-7817FBC57707/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:11:09.606 ThaliTest[1529:3254025] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CFC4E763-CCF0-4410-A46B-37D627117C9C/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:11:10.007 ThaliTest[1529:3254025] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:11:10.009 ThaliTest[1529:3254025] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:11:10.018 ThaliTest[1529:3254025] Unlimited access to network resources
,2016-01-08 17:11:10.031 ThaliTest[1529:3254025] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:11:19.298 ThaliTest[1529:3254025] Resetting plugins due to page load.
,2016-01-08 17:11:22.860 ThaliTest[1529:3254025] Finished load of: file:///var/mobile/Containers/Bundle/Application/DC8E7AB5-C411-4FB9-9FC9-E6EF067510B8/ThaliTest.app/www/index.html
,2016-01-08 17:11:23.040 ThaliTest[1529:3254025] JXcore Cordova plugin initializing
2016-01-08 17:11:23.042 ThaliTest[1529:3254234] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
