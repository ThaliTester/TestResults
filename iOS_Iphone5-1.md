#### Test 5065027881383b1_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/31AA1585-675B-45AA-8BD4-B5D6B98FC88F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/31AA1585-675B-45AA-8BD4-B5D6B98FC88F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/644EFC21-2789-4668-86CD-0A949E61EBD9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53318"
,(lldb)     command script import "/tmp/31AA1585-675B-45AA-8BD4-B5D6B98FC88F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 14:05:33.276 ThaliTest[588:647302] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4052A8CD-1FC5-49DE-B4BD-965C0DC1ADE5/Library/Cookies/Cookies.binarycookies
,2015-12-10 14:05:33.397 ThaliTest[588:647302] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 14:05:33.399 ThaliTest[588:647302] Multi-tasking -> Device: YES, App: YES
,2015-12-10 14:05:33.404 ThaliTest[588:647302] Unlimited access to network resources
,2015-12-10 14:05:33.416 ThaliTest[588:647302] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 14:05:43.758 ThaliTest[588:647302] Resetting plugins due to page load.
,2015-12-10 14:05:47.878 ThaliTest[588:647302] Finished load of: file:///var/mobile/Containers/Bundle/Application/644EFC21-2789-4668-86CD-0A949E61EBD9/ThaliTest.app/www/index.html
,2015-12-10 14:05:48.096 ThaliTest[588:647302] JXcore Cordova plugin initializing
,2015-12-10 14:05:48.098 ThaliTest[588:647475] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-10 14:05:50.535 ThaliTest[588:647302] THREAD WARNING: ['JXcore'] took '153.561035' ms. Plugin should use a background thread.

```
