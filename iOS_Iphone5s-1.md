#### Test 757892685345aa0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C2CC7668-2405-479C-998A-0B05FE6C0D9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C2CC7668-2405-479C-998A-0B05FE6C0D9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1AB04393-6E28-4A97-9EE1-290F3A3CC06E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51409"
,(lldb)     command script import "/tmp/C2CC7668-2405-479C-998A-0B05FE6C0D9C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:44:09.287 ThaliTest[6540:19675152] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30ACB70D-FBCB-406E-809A-5F8A019021DE/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:44:09.551 ThaliTest[6540:19675152] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:44:09.553 ThaliTest[6540:19675152] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:44:09.571 ThaliTest[6540:19675152] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:44:10.389 ThaliTest[6540:19675152] Using UIWebView
2016-07-07 15:44:10.392 ThaliTest[6540:19675152] [CDVTimer][handleopenurl] 0.153959ms
,2016-07-07 15:44:10.396 ThaliTest[6540:19675152] [CDVTimer][intentandnavigationfilter] 3.750980ms
2016-07-07 15:44:10.396 ThaliTest[6540:19675152] [CDVTimer][gesturehandler] 0.147998ms
2016-07-07 15:44:10.396 ThaliTest[6540:19675152] [CDVTimer][TotalPlug,inStartup] 4.667997ms
,2016-07-07 15:44:13.688 ThaliTest[6540:19675152] Resetting plugins due to page load.
,2016-07-07 15:44:15.220 ThaliTest[6540:19675152] Finished load of: file:///var/mobile/Containers/Bundle/Application/1AB04393-6E28-4A97-9EE1-290F3A3CC06E/ThaliTest.app/www/index.html
,2016-07-07 15:44:15.406 ThaliTest[6540:19675152] JXcore Cordova plugin initializing
,2016-07-07 15:44:15.409 ThaliTest[6540:19675307] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
