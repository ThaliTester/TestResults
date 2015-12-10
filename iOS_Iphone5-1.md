#### Test 506502784dae475_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/365ECC1F-E8D8-43A2-AD11-6301E599E348/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/365ECC1F-E8D8-43A2-AD11-6301E599E348/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B9BFF18-7B3F-4F1E-A428-9BC962CC070A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53207"
,(lldb)     command script import "/tmp/365ECC1F-E8D8-43A2-AD11-6301E599E348/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 13:34:06.066 ThaliTest[580:642344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2A35664A-17E3-4EB0-B80B-3294AA019D3A/Library/Cookies/Cookies.binarycookies
,2015-12-10 13:34:06.180 ThaliTest[580:642344] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 13:34:06.182 ThaliTest[580:642344] Multi-tasking -> Device: YES, App: YES
,2015-12-10 13:34:06.187 ThaliTest[580:642344] Unlimited access to network resources
,2015-12-10 13:34:06.199 ThaliTest[580:642344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 13:34:16.540 ThaliTest[580:642344] Resetting plugins due to page load.
,2015-12-10 13:34:20.747 ThaliTest[580:642344] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B9BFF18-7B3F-4F1E-A428-9BC962CC070A/ThaliTest.app/www/index.html
,2015-12-10 13:34:20.971 ThaliTest[580:642344] JXcore Cordova plugin initializing
,2015-12-10 13:34:20.972 ThaliTest[580:642531] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
