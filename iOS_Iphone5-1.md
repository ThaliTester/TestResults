#### Test 54970261e0c50c1_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261e0c50c1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6D0F7770-B0EA-40E4-93FB-E3CD8E4243F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6D0F7770-B0EA-40E4-93FB-E3CD8E4243F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261e0c50c1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261e0c50c1/build_ios/ThaliTest.app' (armv7).
,(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0AC6060C-03B8-45B2-B101-9290B033569F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50761"
,(lldb)     command script import "/tmp/6D0F7770-B0EA-40E4-93FB-E3CD8E4243F7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 18:31:22.468 ThaliTest[1118:3607274] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7AA8FC15-AB76-4270-901D-44C7101C0E95/Library/Cookies/Cookies.binarycookies
,2016-01-08 18:31:22.592 ThaliTest[1118:3607274] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 18:31:22.594 ThaliTest[1118:3607274] Multi-tasking -> Device: YES, App: YES
,2016-01-08 18:31:22.601 ThaliTest[1118:3607274] Unlimited access to network resources
,2016-01-08 18:31:22.615 ThaliTest[1118:3607274] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 18:31:33.277 ThaliTest[1118:3607274] Resetting plugins due to page load.
,2016-01-08 18:31:37.399 ThaliTest[1118:3607274] Finished load of: file:///var/mobile/Containers/Bundle/Application/0AC6060C-03B8-45B2-B101-9290B033569F/ThaliTest.app/www/index.html
,2016-01-08 18:31:37.617 ThaliTest[1118:3607274] JXcore Cordova plugin initializing
,2016-01-08 18:31:37.619 ThaliTest[1118:3607454] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
