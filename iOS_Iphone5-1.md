#### Test 50650278ec2c976_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7FA336E5-9904-42AB-A050-07268EEEAEBD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7FA336E5-9904-42AB-A050-07268EEEAEBD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ec2c976/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D170FE13-5342-4EF0-9694-ECE08B7C5564/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55489"
,(lldb)     command script import "/tmp/7FA336E5-9904-42AB-A050-07268EEEAEBD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 17:06:09.471 ThaliTest[795:1281129] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6471540E-28B4-4140-A776-16E5745B0ED6/Library/Cookies/Cookies.binarycookies
,2015-12-14 17:06:10.024 ThaliTest[795:1281129] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 17:06:10.025 ThaliTest[795:1281129] Multi-tasking -> Device: YES, App: YES
,2015-12-14 17:06:10.030 ThaliTest[795:1281129] Unlimited access to network resources
,2015-12-14 17:06:10.045 ThaliTest[795:1281129] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 17:06:20.399 ThaliTest[795:1281129] Resetting plugins due to page load.
,2015-12-14 17:06:23.969 ThaliTest[795:1281129] Finished load of: file:///var/mobile/Containers/Bundle/Application/D170FE13-5342-4EF0-9694-ECE08B7C5564/ThaliTest.app/www/index.html
,2015-12-14 17:06:24.175 ThaliTest[795:1281129] JXcore Cordova plugin initializing
,2015-12-14 17:06:24.176 ThaliTest[795:1281313] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-14 17:06:26.608 ThaliTest[795:1281129] THREAD WARNING: ['JXcore'] took '151.563232' ms. Plugin should use a background thread.

```
