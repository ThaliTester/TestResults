#### Test 50650278ec2c976_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BFF8CD78-4E46-45D5-80D2-CE96EF4BC8F3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BFF8CD78-4E46-45D5-80D2-CE96EF4BC8F3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74BEC8A2-98BD-4FFB-9231-4A49E6B2EF96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55517"
,(lldb)     command script import "/tmp/BFF8CD78-4E46-45D5-80D2-CE96EF4BC8F3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 17:07:37.740 ThaliTest[918:1172388] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0AB2B19E-9DB4-4909-B366-E8B4790F60B8/Library/Cookies/Cookies.binarycookies
,2015-12-14 17:07:38.168 ThaliTest[918:1172388] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 17:07:38.170 ThaliTest[918:1172388] Multi-tasking -> Device: YES, App: YES
,2015-12-14 17:07:38.181 ThaliTest[918:1172388] Unlimited access to network resources
,2015-12-14 17:07:38.196 ThaliTest[918:1172388] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 17:07:47.109 ThaliTest[918:1172388] Resetting plugins due to page load.
,2015-12-14 17:07:50.746 ThaliTest[918:1172388] Finished load of: file:///var/mobile/Containers/Bundle/Application/74BEC8A2-98BD-4FFB-9231-4A49E6B2EF96/ThaliTest.app/www/index.html
,2015-12-14 17:07:50.947 ThaliTest[918:1172388] JXcore Cordova plugin initializing
2015-12-14 17:07:50.949 ThaliTest[918:1172604] JXcore instance initializing
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
,2015-12-14 17:07:52.025 ThaliTest[918:1172388] THREAD WARNING: ['JXcore'] took '81.292725' ms. Plugin should use a background thread.

```
