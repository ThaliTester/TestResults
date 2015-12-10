#### Test 50650278d6c551a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1A8930ED-11DA-48C2-8FE7-189B3152808C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1A8930ED-11DA-48C2-8FE7-189B3152808C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d6c551a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1C8ED69D-C636-4FA4-8A63-717AB6DBA2B1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53434"
,(lldb)     command script import "/tmp/1A8930ED-11DA-48C2-8FE7-189B3152808C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 14:37:00.241 ThaliTest[593:651719] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/06F7BAB7-A0C4-4B10-94F9-91EDD33AFD51/Library/Cookies/Cookies.binarycookies
,2015-12-10 14:37:00.379 ThaliTest[593:651719] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 14:37:00.381 ThaliTest[593:651719] Multi-tasking -> Device: YES, App: YES
,2015-12-10 14:37:00.388 ThaliTest[593:651719] Unlimited access to network resources
,2015-12-10 14:37:00.402 ThaliTest[593:651719] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 14:37:11.156 ThaliTest[593:651719] Resetting plugins due to page load.
,2015-12-10 14:37:15.322 ThaliTest[593:651719] Finished load of: file:///var/mobile/Containers/Bundle/Application/1C8ED69D-C636-4FA4-8A63-717AB6DBA2B1/ThaliTest.app/www/index.html
,2015-12-10 14:37:15.537 ThaliTest[593:651719] JXcore Cordova plugin initializing
,2015-12-10 14:37:15.539 ThaliTest[593:651915] JXcore instance initializing
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
,2015-12-10 14:37:17.963 ThaliTest[593:651719] THREAD WARNING: ['JXcore'] took '153.602051' ms. Plugin should use a background thread.

```
