#### Test 75789268a22e351_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2F1A4A80-C65A-4F57-8222-4A378C9E122D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2F1A4A80-C65A-4F57-8222-4A378C9E122D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0478CD6E-B26E-4189-9BE9-38B2D95EFD16/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51343"
,(lldb)     command script import "/tmp/2F1A4A80-C65A-4F57-8222-4A378C9E122D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:09:08.044 ThaliTest[6452:20021441] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B0DBD6C-3AF6-4AE1-89BB-C950F92012A2/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:09:08.273 ThaliTest[6452:20021441] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:09:08.274 ThaliTest[6452:20021441] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:09:08.290 ThaliTest[6452:20021441] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:09:09.068 ThaliTest[6452:20021441] Using UIWebView
2016-07-07 15:09:09.070 ThaliTest[6452:20021441] [CDVTimer][handleopenurl] 0.131011ms
2016-07-07 15:09:09.072 ThaliTest[6452:20021441] [CDVTimer][intentandnavigationfilter] 2.161980ms
,2016-07-07 15:09:09.073 ThaliTest[6452:20021441] [CDVTimer][gesturehandler] 1.142025ms
2016-07-07 15:09:09.074 ThaliTest[6452:20021441] [CDVTimer][TotalPluginStartup] 3.922999ms
,2016-07-07 15:09:12.207 ThaliTest[6452:20021441] Resetting plugins due to page load.
,2016-07-07 15:09:13.517 ThaliTest[6452:20021441] Finished load of: file:///var/mobile/Containers/Bundle/Application/0478CD6E-B26E-4189-9BE9-38B2D95EFD16/ThaliTest.app/www/index.html
,2016-07-07 15:09:13.671 ThaliTest[6452:20021441] JXcore Cordova plugin initializing
2016-07-07 15:09:13.672 ThaliTest[6452:20021614] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,appEnteredForeground wasn't registered

```
