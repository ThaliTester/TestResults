#### Test 50650278d6c551a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/8C4CD14A-EB6B-47C3-8434-1E3DB4C01780/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8C4CD14A-EB6B-47C3-8434-1E3DB4C01780/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D08CD3A5-68A6-49FB-81A5-8D5ED4F39979/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53474"
,(lldb)     command script import "/tmp/8C4CD14A-EB6B-47C3-8434-1E3DB4C01780/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 14:38:24.483 ThaliTest[705:577283] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D51B8703-3E77-4D99-A260-4149AA68921F/Library/Cookies/Cookies.binarycookies
,2015-12-10 14:38:24.893 ThaliTest[705:577283] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 14:38:24.895 ThaliTest[705:577283] Multi-tasking -> Device: YES, App: YES
,2015-12-10 14:38:24.906 ThaliTest[705:577283] Unlimited access to network resources
,2015-12-10 14:38:24.921 ThaliTest[705:577283] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 14:38:34.284 ThaliTest[705:577283] Resetting plugins due to page load.
,2015-12-10 14:38:38.102 ThaliTest[705:577283] Finished load of: file:///var/mobile/Containers/Bundle/Application/D08CD3A5-68A6-49FB-81A5-8D5ED4F39979/ThaliTest.app/www/index.html
,2015-12-10 14:38:38.314 ThaliTest[705:577283] JXcore Cordova plugin initializing
2015-12-10 14:38:38.315 ThaliTest[705:577498] JXcore instance initializing
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
,2015-12-10 14:38:39.623 ThaliTest[705:577283] THREAD WARNING: ['JXcore'] took '91.538086' ms. Plugin should use a background thread.

```
