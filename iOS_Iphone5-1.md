#### Test 558973767bac5c9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/32120E42-4EC7-4CFA-B3F9-3BA8DC3E319E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/32120E42-4EC7-4CFA-B3F9-3BA8DC3E319E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/558973767bac5c9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E64A6A7D-F2AC-4F47-87B8-94CEB7711A01/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54816"
,(lldb)     command script import "/tmp/32120E42-4EC7-4CFA-B3F9-3BA8DC3E319E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 14:49:36.180 ThaliTest[1339:4343748] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8E650F54-C339-4FAC-A42F-4803ABA6C5D5/Library/Cookies/Cookies.binarycookies
,2016-01-13 14:49:36.293 ThaliTest[1339:4343748] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 14:49:36.296 ThaliTest[1339:4343748] Multi-tasking -> Device: YES, App: YES
,2016-01-13 14:49:36.302 ThaliTest[1339:4343748] Unlimited access to network resources
,2016-01-13 14:49:36.317 ThaliTest[1339:4343748] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 14:49:42.459 ThaliTest[1339:4343748] Resetting plugins due to page load.
,2016-01-13 14:49:44.859 ThaliTest[1339:4343748] Finished load of: file:///var/mobile/Containers/Bundle/Application/E64A6A7D-F2AC-4F47-87B8-94CEB7711A01/ThaliTest.app/www/index.html
,2016-01-13 14:49:45.065 ThaliTest[1339:4343748] JXcore Cordova plugin initializing
2016-01-13 14:49:45.066 ThaliTest[1339:4344014] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
