#### Test 549702619369e5e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A43675CD-32D4-48FA-B15A-5686BE9C06A3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A43675CD-32D4-48FA-B15A-5686BE9C06A3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702619369e5e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD6A97F4-8198-4CD2-B655-8A048BF0B93C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51360"
,(lldb)     command script import "/tmp/A43675CD-32D4-48FA-B15A-5686BE9C06A3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 23:24:37.991 ThaliTest[1149:3644191] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EEB008DB-66FA-4DDB-8B62-61EE0C7F5D8E/Library/Cookies/Cookies.binarycookies
,2016-01-08 23:24:38.112 ThaliTest[1149:3644191] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 23:24:38.113 ThaliTest[1149:3644191] Multi-tasking -> Device: YES, App: YES
,2016-01-08 23:24:38.118 ThaliTest[1149:3644191] Unlimited access to network resources
,2016-01-08 23:24:38.130 ThaliTest[1149:3644191] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 23:24:48.390 ThaliTest[1149:3644191] Resetting plugins due to page load.
,2016-01-08 23:24:52.466 ThaliTest[1149:3644191] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD6A97F4-8198-4CD2-B655-8A048BF0B93C/ThaliTest.app/www/index.html
,2016-01-08 23:24:52.685 ThaliTest[1149:3644191] JXcore Cordova plugin initializing
,2016-01-08 23:24:52.687 ThaliTest[1149:3644380] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
