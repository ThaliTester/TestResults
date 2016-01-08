#### Test 5497026140aeaf4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/68FE6C97-7F0C-4728-BCAB-51C2D5907605/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/68FE6C97-7F0C-4728-BCAB-51C2D5907605/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/09FD35C3-B97E-49FF-A342-474182C34A7F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50989"
,(lldb)     command script import "/tmp/68FE6C97-7F0C-4728-BCAB-51C2D5907605/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 19:35:17.364 ThaliTest[1130:3615988] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46F2EC8D-8648-4C94-8E8E-31F61F6BA29F/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:35:17.503 ThaliTest[1130:3615988] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:35:17.505 ThaliTest[1130:3615988] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:35:17.513 ThaliTest[1130:3615988] Unlimited access to network resources
,2016-01-08 19:35:17.526 ThaliTest[1130:3615988] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:35:27.054 ThaliTest[1130:3615988] Resetting plugins due to page load.
,2016-01-08 19:35:30.916 ThaliTest[1130:3615988] Finished load of: file:///var/mobile/Containers/Bundle/Application/09FD35C3-B97E-49FF-A342-474182C34A7F/ThaliTest.app/www/index.html
,2016-01-08 19:35:31.132 ThaliTest[1130:3615988] JXcore Cordova plugin initializing
,2016-01-08 19:35:31.134 ThaliTest[1130:3616161] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
