#### Test 50650278dbf8a2a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/00B633A9-16D4-4AEB-AD67-FC1F56C636D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/00B633A9-16D4-4AEB-AD67-FC1F56C636D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CBC2C346-BBC4-442C-9CBC-863054E28143/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57946"
,(lldb)     command script import "/tmp/00B633A9-16D4-4AEB-AD67-FC1F56C636D0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 01:37:59.825 ThaliTest[232:23279] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8EE871DD-C04A-4541-A0F7-663FE0386C15/Library/Cookies/Cookies.binarycookies
,2015-12-16 01:38:00.225 ThaliTest[232:23279] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 01:38:00.227 ThaliTest[232:23279] Multi-tasking -> Device: YES, App: YES
,2015-12-16 01:38:00.236 ThaliTest[232:23279] Unlimited access to network resources
,2015-12-16 01:38:00.248 ThaliTest[232:23279] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 01:38:09.668 ThaliTest[232:23279] Resetting plugins due to page load.
,2015-12-16 01:38:13.431 ThaliTest[232:23279] Finished load of: file:///var/mobile/Containers/Bundle/Application/CBC2C346-BBC4-442C-9CBC-863054E28143/ThaliTest.app/www/index.html
,2015-12-16 01:38:13.619 ThaliTest[232:23279] JXcore Cordova plugin initializing
,2015-12-16 01:38:13.621 ThaliTest[232:23491] JXcore instance initializing
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
,2015-12-16 01:38:14.722 ThaliTest[232:23279] THREAD WARNING: ['JXcore'] took '77.966309' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 01:44:52.817 ThaliTest[232:23491] jxcore: startBroadcasting
,2015-12-16 01:44:52.839 ThaliTest[232:23491] server: starting Apple-Iphone6-1_PT7083.9zFWcw==
,2015-12-16 01:44:52.842 ThaliTest[232:23491] multipeer session: start timer: 0x193ca5e0
2015-12-16 01:44:52.843 ThaliTest[232:23491] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7083
2015-12-16 01:44:52.843 ThaliTest[232:23491] jxcore: startBro,adcasting: success
StartBroadcasting started ok
,2015-12-16 01:45:22.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:45:52.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:46:22.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:46:52.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:47:22.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:47:52.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:48:22.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:48:52.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:49:22.843 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:49:52.844 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:50:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:50:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:51:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:51:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:52:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:52:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:53:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:53:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:54:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:54:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:55:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:55:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:56:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:56:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:57:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:57:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:58:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:58:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:59:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 01:59:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:00:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:00:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:01:22.790 ThaliTest[232:23279] multipeer session: restart
,timeout now
,weAreDoneNow
,done, now sending data to server
,2015-12-16 02:01:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:02:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:02:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:03:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:03:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:04:22.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:04:52.790 ThaliTest[232:23279] multipeer session: restart
,2015-12-16 02:05:22.790 ThaliTest[232:23279] multipeer session: restart

```
