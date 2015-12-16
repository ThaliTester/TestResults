#### Test 506502783fcf234_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/195814A8-6A53-4BE0-9EA3-FD97C8BD811D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/195814A8-6A53-4BE0-9EA3-FD97C8BD811D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FE8EEA2-5694-4E58-A009-E49B756C77A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58354"
,(lldb)     command script import "/tmp/195814A8-6A53-4BE0-9EA3-FD97C8BD811D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 04:56:07.984 ThaliTest[262:46003] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1D3AF828-D63F-44EB-BDD1-10EEE29B518D/Library/Cookies/Cookies.binarycookies
,2015-12-16 04:56:08.348 ThaliTest[262:46003] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 04:56:08.350 ThaliTest[262:46003] Multi-tasking -> Device: YES, App: YES
,2015-12-16 04:56:08.359 ThaliTest[262:46003] Unlimited access to network resources
,2015-12-16 04:56:08.369 ThaliTest[262:46003] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 04:56:16.664 ThaliTest[262:46003] Resetting plugins due to page load.
,2015-12-16 04:56:19.828 ThaliTest[262:46003] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FE8EEA2-5694-4E58-A009-E49B756C77A9/ThaliTest.app/www/index.html
,2015-12-16 04:56:20.006 ThaliTest[262:46003] JXcore Cordova plugin initializing
,2015-12-16 04:56:20.008 ThaliTest[262:46209] JXcore instance initializing
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
,2015-12-16 04:56:21.086 ThaliTest[262:46003] THREAD WARNING: ['JXcore'] took '78.629883' ms. Plugin should use a background thread.
,Connected to the server!

```
