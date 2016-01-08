#### Test 549702613245198_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C77D1649-D237-4712-9484-F9037BA30694/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C77D1649-D237-4712-9484-F9037BA30694/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69A5553E-69E2-45EA-B09A-044D0D5C911D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51268"
,(lldb)     command script import "/tmp/C77D1649-D237-4712-9484-F9037BA30694/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 21:06:45.904 ThaliTest[1614:3375979] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14CD8528-613A-4CDE-BF44-35CF065B0A36/Library/Cookies/Cookies.binarycookies
,2016-01-08 21:06:46.273 ThaliTest[1614:3375979] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 21:06:46.274 ThaliTest[1614:3375979] Multi-tasking -> Device: YES, App: YES
,2016-01-08 21:06:46.283 ThaliTest[1614:3375979] Unlimited access to network resources
,2016-01-08 21:06:46.292 ThaliTest[1614:3375979] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 21:06:56.007 ThaliTest[1614:3375979] Resetting plugins due to page load.
,2016-01-08 21:06:59.666 ThaliTest[1614:3375979] Finished load of: file:///var/mobile/Containers/Bundle/Application/69A5553E-69E2-45EA-B09A-044D0D5C911D/ThaliTest.app/www/index.html
,2016-01-08 21:06:59.824 ThaliTest[1614:3375979] JXcore Cordova plugin initializing
,2016-01-08 21:06:59.825 ThaliTest[1614:3376225] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
