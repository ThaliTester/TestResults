#### Test 549702617d40def_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/82A57178-2362-4355-9FA2-39283734FEE6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/82A57178-2362-4355-9FA2-39283734FEE6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/37BE8353-AA6E-479B-83FA-81B436FF2F70/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64739"
,(lldb)     command script import "/tmp/82A57178-2362-4355-9FA2-39283734FEE6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 02:19:26.724 ThaliTest[1287:2801716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D0456ED8-7E95-488E-9254-0755AAC9310B/Library/Cookies/Cookies.binarycookies
,2016-01-05 02:19:27.046 ThaliTest[1287:2801716] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 02:19:27.047 ThaliTest[1287:2801716] Multi-tasking -> Device: YES, App: YES
,2016-01-05 02:19:27.055 ThaliTest[1287:2801716] Unlimited access to network resources
,2016-01-05 02:19:27.062 ThaliTest[1287:2801716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 02:19:35.970 ThaliTest[1287:2801716] Resetting plugins due to page load.
,2016-01-05 02:19:39.245 ThaliTest[1287:2801716] Finished load of: file:///var/mobile/Containers/Bundle/Application/37BE8353-AA6E-479B-83FA-81B436FF2F70/ThaliTest.app/www/index.html
,2016-01-05 02:19:39.462 ThaliTest[1287:2801716] JXcore Cordova plugin initializing
,2016-01-05 02:19:39.463 ThaliTest[1287:2801961] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
