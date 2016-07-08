#### Test 75789268d2ecd3a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/DD2EB80C-DC71-42CF-9C86-9FF7864A7B5D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DD2EB80C-DC71-42CF-9C86-9FF7864A7B5D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E78AE64D-976F-42C7-B485-77C6A5289340/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51892"
,(lldb)     command script import "/tmp/DD2EB80C-DC71-42CF-9C86-9FF7864A7B5D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-08 13:59:18.452 ThaliTest[3879:14073927] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0D15A7C-CB2F-42C4-98EC-ABDF1E56F96C/Library/Cookies/Cookies.binarycookies
,2016-07-08 13:59:18.679 ThaliTest[3879:14073927] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-08 13:59:18.679 ThaliTest[3879:14073927] Multi-tasking -> Device: YES, App: YES
,2016-07-08 13:59:18.692 ThaliTest[3879:14073927] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-08 13:59:19.501 ThaliTest[3879:14073927] Using UIWebView
,2016-07-08 13:59:19.503 ThaliTest[3879:14073927] [CDVTimer][handleopenurl] 0.108004ms
,2016-07-08 13:59:19.505 ThaliTest[3879:14073927] [CDVTimer][intentandnavigationfilter] 1.842976ms
2016-07-08 13:59:19.505 ThaliTest[3879:14073927] [CDVTimer][gesturehandler] 0.081003ms
2016-07-08 13:59:19.505 ThaliTest[3879:14073927] [CDVTimer][TotalPluginStartup] 2.461016ms
,2016-07-08 13:59:22.753 ThaliTest[3879:14073927] Resetting plugins due to page load.
,2016-07-08 13:59:24.177 ThaliTest[3879:14073927] Finished load of: file:///var/mobile/Containers/Bundle/Application/E78AE64D-976F-42C7-B485-77C6A5289340/ThaliTest.app/www/index.html
,2016-07-08 13:59:24.314 ThaliTest[3879:14073927] JXcore Cordova plugin initializing
,2016-07-08 13:59:24.315 ThaliTest[3879:14074096] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
