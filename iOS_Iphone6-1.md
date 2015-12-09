#### Test 506502789252e15_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A5A4AF13-F126-4F30-9AFC-3B52AF7EED57/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A5A4AF13-F126-4F30-9AFC-3B52AF7EED57/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/531A370A-8B1F-4B8B-9A7F-7FBC080DCA0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52565"
,(lldb)     command script import "/tmp/A5A4AF13-F126-4F30-9AFC-3B52AF7EED57/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-09 18:52:22.474 ThaliTest[616:456367] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2034C281-4AB5-4431-88CC-8D05C595FE91/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:52:22.860 ThaliTest[616:456367] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:52:22.862 ThaliTest[616:456367] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:52:22.872 ThaliTest[616:456367] Unlimited access to network resources
,2015-12-09 18:52:22.887 ThaliTest[616:456367] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:52:32.154 ThaliTest[616:456367] Resetting plugins due to page load.
,2015-12-09 18:52:35.804 ThaliTest[616:456367] Finished load of: file:///var/mobile/Containers/Bundle/Application/531A370A-8B1F-4B8B-9A7F-7FBC080DCA0B/ThaliTest.app/www/index.html
,2015-12-09 18:52:35.984 ThaliTest[616:456367] JXcore Cordova plugin initializing
,2015-12-09 18:52:35.985 ThaliTest[616:456571] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
