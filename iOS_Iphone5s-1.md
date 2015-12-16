#### Test 506502789b39735_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D7704BCB-5D5C-4DC1-9BE8-EDEF267194B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D7704BCB-5D5C-4DC1-9BE8-EDEF267194B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3684DAC5-7805-4AE1-90B1-C3B620BB6079/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58077"
,(lldb)     command script import "/tmp/D7704BCB-5D5C-4DC1-9BE8-EDEF267194B0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-16 02:32:44.873 ThaliTest[237:29841] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CE7FC7C1-B063-4B63-A67E-06A2AD4C293F/Library/Cookies/Cookies.binarycookies
,2015-12-16 02:32:45.341 ThaliTest[237:29841] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 02:32:45.343 ThaliTest[237:29841] Multi-tasking -> Device: YES, App: YES
,2015-12-16 02:32:45.353 ThaliTest[237:29841] Unlimited access to network resources
,2015-12-16 02:32:45.369 ThaliTest[237:29841] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 02:32:54.139 ThaliTest[237:29841] Resetting plugins due to page load.
,2015-12-16 02:32:57.785 ThaliTest[237:29841] Finished load of: file:///var/mobile/Containers/Bundle/Application/3684DAC5-7805-4AE1-90B1-C3B620BB6079/ThaliTest.app/www/index.html
,2015-12-16 02:32:57.993 ThaliTest[237:29841] JXcore Cordova plugin initializing
2015-12-16 02:32:57.994 ThaliTest[237:30058] JXcore instance initializing
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
,2015-12-16 02:32:59.300 ThaliTest[237:29841] THREAD WARNING: ['JXcore'] took '91.459961' ms. Plugin should use a background thread.
,Connected to the server!

```
