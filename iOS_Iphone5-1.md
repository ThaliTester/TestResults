#### Test 549702617d40def_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6B8F2B1C-C409-482B-886D-85D12A1DCE20/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6B8F2B1C-C409-482B-886D-85D12A1DCE20/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702617d40def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB6336E3-85E6-4364-8CB6-8559D578FB16/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64706"
,(lldb)     command script import "/tmp/6B8F2B1C-C409-482B-886D-85D12A1DCE20/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 02:17:56.775 ThaliTest[934:3024688] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5435EA27-C02C-40EC-A510-3B619B562D49/Library/Cookies/Cookies.binarycookies
,2016-01-05 02:17:56.909 ThaliTest[934:3024688] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 02:17:56.910 ThaliTest[934:3024688] Multi-tasking -> Device: YES, App: YES
,2016-01-05 02:17:56.917 ThaliTest[934:3024688] Unlimited access to network resources
,2016-01-05 02:17:56.931 ThaliTest[934:3024688] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 02:18:08.115 ThaliTest[934:3024688] Resetting plugins due to page load.
,2016-01-05 02:18:11.772 ThaliTest[934:3024688] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB6336E3-85E6-4364-8CB6-8559D578FB16/ThaliTest.app/www/index.html
,2016-01-05 02:18:11.982 ThaliTest[934:3024688] JXcore Cordova plugin initializing
2016-01-05 02:18:11.985 ThaliTest[934:3024873] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
