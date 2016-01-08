#### Test 54970261ac9928f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4223E836-0354-4864-8C50-1D2FFB418EC9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4223E836-0354-4864-8C50-1D2FFB418EC9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261ac9928f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD4A934D-DCB3-4D06-8236-92EFDCAECBA4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50535"
,(lldb)     command script import "/tmp/4223E836-0354-4864-8C50-1D2FFB418EC9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:09:43.358 ThaliTest[1104:3596331] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/597EE73A-4C70-4226-99AC-1990C531677E/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:09:43.494 ThaliTest[1104:3596331] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:09:43.496 ThaliTest[1104:3596331] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:09:43.503 ThaliTest[1104:3596331] Unlimited access to network resources
,2016-01-08 17:09:43.517 ThaliTest[1104:3596331] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:09:54.242 ThaliTest[1104:3596331] Resetting plugins due to page load.
,2016-01-08 17:09:58.421 ThaliTest[1104:3596331] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD4A934D-DCB3-4D06-8236-92EFDCAECBA4/ThaliTest.app/www/index.html
,2016-01-08 17:09:58.638 ThaliTest[1104:3596331] JXcore Cordova plugin initializing
,2016-01-08 17:09:58.640 ThaliTest[1104:3596525] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
