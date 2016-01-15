#### Test 56151093f3290d6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B4619D88-7812-4936-B3DA-3503C759B0BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B4619D88-7812-4936-B3DA-3503C759B0BE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D82D9559-C66E-4C8E-B343-32C47A0B38A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56358"
,(lldb)     command script import "/tmp/B4619D88-7812-4936-B3DA-3503C759B0BE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 13:58:28.582 ThaliTest[1421:4628641] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9108046C-48A6-47BD-A7D0-285B5D8D98A5/Library/Cookies/Cookies.binarycookies
,2016-01-15 13:58:28.687 ThaliTest[1421:4628641] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 13:58:28.689 ThaliTest[1421:4628641] Multi-tasking -> Device: YES, App: YES
,2016-01-15 13:58:28.693 ThaliTest[1421:4628641] Unlimited access to network resources
,2016-01-15 13:58:28.705 ThaliTest[1421:4628641] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 13:58:34.857 ThaliTest[1421:4628641] Resetting plugins due to page load.
,2016-01-15 13:58:37.016 ThaliTest[1421:4628641] Finished load of: file:///var/mobile/Containers/Bundle/Application/D82D9559-C66E-4C8E-B343-32C47A0B38A2/ThaliTest.app/www/index.html
,2016-01-15 13:58:37.217 ThaliTest[1421:4628641] JXcore Cordova plugin initializing
2016-01-15 13:58:37.220 ThaliTest[1421:4628768] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1

```
