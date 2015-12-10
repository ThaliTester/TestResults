#### Test 50650278b86327b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/590FB037-52D9-450F-B5DF-92639D9D17E9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/590FB037-52D9-450F-B5DF-92639D9D17E9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D747A76A-0BE9-4E45-9D67-E33F345983FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53609"
,(lldb)     command script import "/tmp/590FB037-52D9-450F-B5DF-92639D9D17E9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 15:09:53.124 ThaliTest[714:581597] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91609761-2D0A-493C-867C-6C1B480D01C9/Library/Cookies/Cookies.binarycookies
,2015-12-10 15:09:53.581 ThaliTest[714:581597] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 15:09:53.584 ThaliTest[714:581597] Multi-tasking -> Device: YES, App: YES
,2015-12-10 15:09:53.594 ThaliTest[714:581597] Unlimited access to network resources
,2015-12-10 15:09:53.612 ThaliTest[714:581597] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 15:10:02.856 ThaliTest[714:581597] Resetting plugins due to page load.
,2015-12-10 15:10:06.829 ThaliTest[714:581597] Finished load of: file:///var/mobile/Containers/Bundle/Application/D747A76A-0BE9-4E45-9D67-E33F345983FB/ThaliTest.app/www/index.html
,2015-12-10 15:10:07.051 ThaliTest[714:581597] JXcore Cordova plugin initializing
2015-12-10 15:10:07.052 ThaliTest[714:581809] JXcore instance initializing
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
,2015-12-10 15:10:08.362 ThaliTest[714:581597] THREAD WARNING: ['JXcore'] took '92.666992' ms. Plugin should use a background thread.
,Connected to the server!

```
