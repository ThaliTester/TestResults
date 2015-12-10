#### Test 50650278c17c777_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/41BF34C6-8C2D-4E04-9304-EBE13DC72F05/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/41BF34C6-8C2D-4E04-9304-EBE13DC72F05/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/34B95E17-BA42-4B6B-9D39-66CC324C96A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52907"
,(lldb)     command script import "/tmp/41BF34C6-8C2D-4E04-9304-EBE13DC72F05/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 12:14:18.778 ThaliTest[566:631198] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0E2EB593-06D2-4245-8AA0-9D68DED9B0E3/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:14:19.300 ThaliTest[566:631198] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:14:19.301 ThaliTest[566:631198] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:14:19.308 ThaliTest[566:631198] Unlimited access to network resources
,2015-12-10 12:14:19.321 ThaliTest[566:631198] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:14:29.757 ThaliTest[566:631198] Resetting plugins due to page load.
,2015-12-10 12:14:33.402 ThaliTest[566:631198] Finished load of: file:///var/mobile/Containers/Bundle/Application/34B95E17-BA42-4B6B-9D39-66CC324C96A0/ThaliTest.app/www/index.html
,2015-12-10 12:14:33.610 ThaliTest[566:631198] JXcore Cordova plugin initializing
,2015-12-10 12:14:33.613 ThaliTest[566:631540] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
