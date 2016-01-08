#### Test 5497026140aeaf4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/89B8FBC3-17A0-43D3-8FF8-5966643F6966/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/89B8FBC3-17A0-43D3-8FF8-5966643F6966/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/67F3E58A-E9A1-47B3-9095-D8E88C02CEB8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51024"
,(lldb)     command script import "/tmp/89B8FBC3-17A0-43D3-8FF8-5966643F6966/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 19:36:46.447 ThaliTest[1565:3273033] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A16C1D6D-326C-463B-9E86-AD54B761FA1F/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:36:46.767 ThaliTest[1565:3273033] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:36:46.768 ThaliTest[1565:3273033] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:36:46.777 ThaliTest[1565:3273033] Unlimited access to network resources
,2016-01-08 19:36:46.788 ThaliTest[1565:3273033] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:36:54.962 ThaliTest[1565:3273033] Resetting plugins due to page load.
,2016-01-08 19:36:58.213 ThaliTest[1565:3273033] Finished load of: file:///var/mobile/Containers/Bundle/Application/67F3E58A-E9A1-47B3-9095-D8E88C02CEB8/ThaliTest.app/www/index.html
,2016-01-08 19:36:58.395 ThaliTest[1565:3273033] JXcore Cordova plugin initializing
,2016-01-08 19:36:58.397 ThaliTest[1565:3273234] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
