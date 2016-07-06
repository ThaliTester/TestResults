#### Test 757892685041341_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0DD2264A-6FD8-4B8C-9DD0-1E45C4A6F73B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0DD2264A-6FD8-4B8C-9DD0-1E45C4A6F73B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3B4824BE-E86F-43C5-9B5D-A828F09EC838/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50937"
,(lldb)     command script import "/tmp/0DD2264A-6FD8-4B8C-9DD0-1E45C4A6F73B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 14:31:07.239 ThaliTest[6484:19515955] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C4689A1A-D880-4F9D-ACEB-ABEBD5D2CB8E/Library/Cookies/Cookies.binarycookies
,2016-07-06 14:31:07.497 ThaliTest[6484:19515955] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 14:31:07.498 ThaliTest[6484:19515955] Multi-tasking -> Device: YES, App: YES
,2016-07-06 14:31:07.518 ThaliTest[6484:19515955] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 14:31:08.345 ThaliTest[6484:19515955] Using UIWebView
,2016-07-06 14:31:08.349 ThaliTest[6484:19515955] [CDVTimer][handleopenurl] 0.187993ms
2016-07-06 14:31:08.352 ThaliTest[6484:19515955] [CDVTimer][intentandnavigationfilter] 2.653956ms
2016-07-06 14:31:08.352 ThaliTest[6484:19515955] [CDVTimer][gesturehandler] 0.129998ms
2016-07-06 14:31:08.352 ThaliTest[6484:19515955] [CDVTimer][TotalPluginStartup] 3.566980ms
,2016-07-06 14:31:11.648 ThaliTest[6484:19515955] Resetting plugins due to page load.
,2016-07-06 14:31:13.002 ThaliTest[6484:19515955] Finished load of: file:///var/mobile/Containers/Bundle/Application/3B4824BE-E86F-43C5-9B5D-A828F09EC838/ThaliTest.app/www/index.html
,2016-07-06 14:31:13.190 ThaliTest[6484:19515955] JXcore Cordova plugin initializing
2016-07-06 14:31:13.191 ThaliTest[6484:19516111] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
