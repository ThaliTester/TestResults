#### Test 50650278cd699a4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7074EA95-678B-4247-B49F-991A95F0D4A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7074EA95-678B-4247-B49F-991A95F0D4A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C706EA8E-54E9-44FA-BF0A-DACF31B57C93/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58482"
,(lldb)     command script import "/tmp/7074EA95-678B-4247-B49F-991A95F0D4A3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 05:36:20.258 ThaliTest[265:49352] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2EEB12DF-B8BB-492C-8987-B7FF9DF2579C/Library/Cookies/Cookies.binarycookies
,2015-12-16 05:36:20.689 ThaliTest[265:49352] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 05:36:20.691 ThaliTest[265:49352] Multi-tasking -> Device: YES, App: YES
,2015-12-16 05:36:20.702 ThaliTest[265:49352] Unlimited access to network resources
,2015-12-16 05:36:20.719 ThaliTest[265:49352] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 05:36:29.725 ThaliTest[265:49352] Resetting plugins due to page load.
,2015-12-16 05:36:33.601 ThaliTest[265:49352] Finished load of: file:///var/mobile/Containers/Bundle/Application/C706EA8E-54E9-44FA-BF0A-DACF31B57C93/ThaliTest.app/www/index.html
,2015-12-16 05:36:33.810 ThaliTest[265:49352] JXcore Cordova plugin initializing
,2015-12-16 05:36:33.812 ThaliTest[265:49560] JXcore instance initializing
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
,2015-12-16 05:36:35.125 ThaliTest[265:49352] THREAD WARNING: ['JXcore'] took '83.366943' ms. Plugin should use a background thread.
,Connected to the server!

```
