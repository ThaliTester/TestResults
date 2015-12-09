#### Test 506502789252e15_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7C2B79DE-5126-4DE2-95C3-360D742E4B25/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7C2B79DE-5126-4DE2-95C3-360D742E4B25/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50536B89-6FAC-4303-BCFA-6EE930B2D16E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52527"
,(lldb)     command script import "/tmp/7C2B79DE-5126-4DE2-95C3-360D742E4B25/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 18:51:00.875 ThaliTest[537:522077] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF509B65-AE36-4007-8CBC-9389DA005C70/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:51:01.422 ThaliTest[537:522077] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:51:01.423 ThaliTest[537:522077] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:51:01.428 ThaliTest[537:522077] Unlimited access to network resources
,2015-12-09 18:51:01.440 ThaliTest[537:522077] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:51:11.817 ThaliTest[537:522077] Resetting plugins due to page load.
,2015-12-09 18:51:15.621 ThaliTest[537:522077] Finished load of: file:///var/mobile/Containers/Bundle/Application/50536B89-6FAC-4303-BCFA-6EE930B2D16E/ThaliTest.app/www/index.html
,2015-12-09 18:51:15.831 ThaliTest[537:522077] JXcore Cordova plugin initializing
,2015-12-09 18:51:15.834 ThaliTest[537:522261] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
