#### Test 75789268eab05ed_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5D036DC8-B4B8-4617-9376-07D1AADC855B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5D036DC8-B4B8-4617-9376-07D1AADC855B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1BDA28A6-7E01-4698-8FA0-37C0CDACEC8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49829"
,(lldb)     command script import "/tmp/5D036DC8-B4B8-4617-9376-07D1AADC855B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:05:42.720 ThaliTest[3642:13574717] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D6DE30B-D10F-41AD-9F19-F1738F1AE4AD/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:05:42.952 ThaliTest[3642:13574717] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 11:05:42.953 ThaliTest[3642:13574717] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:05:42.965 ThaliTest[3642:13574717] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:05:43.773 ThaliTest[3642:13574717] Using UIWebView
,2016-07-05 11:05:43.775 ThaliTest[3642:13574717] [CDVTimer][handleopenurl] 0.136018ms
,2016-07-05 11:05:43.777 ThaliTest[3642:13574717] [CDVTimer][intentandnavigationfilter] 1.857042ms
2016-07-05 11:05:43.778 ThaliTest[3642:13574717] [CDVTimer][gesturehandler] 0.086010ms
,2016-07-05 11:05:43.778 ThaliTest[3642:13574717] [CDVTimer][TotalPluginStartup] 2.514958ms
,2016-07-05 11:05:46.956 ThaliTest[3642:13574717] Resetting plugins due to page load.
,2016-07-05 11:05:48.186 ThaliTest[3642:13574717] Finished load of: file:///var/mobile/Containers/Bundle/Application/1BDA28A6-7E01-4698-8FA0-37C0CDACEC8A/ThaliTest.app/www/index.html
,2016-07-05 11:05:48.322 ThaliTest[3642:13574717] JXcore Cordova plugin initializing
,2016-07-05 11:05:48.322 ThaliTest[3642:13574904] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
