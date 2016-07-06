#### Test 757892685041341_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8199C89A-AC5B-401E-9EEC-9C43835EE3BF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8199C89A-AC5B-401E-9EEC-9C43835EE3BF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7AC32E1-B2B5-4159-97E1-7B7E783A3E51/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50935"
,(lldb)     command script import "/tmp/8199C89A-AC5B-401E-9EEC-9C43835EE3BF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 14:31:05.261 ThaliTest[6404:19862959] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD17F1CE-8231-4930-8CA8-579A5C41F795/Library/Cookies/Cookies.binarycookies
,2016-07-06 14:31:05.491 ThaliTest[6404:19862959] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 14:31:05.492 ThaliTest[6404:19862959] Multi-tasking -> Device: YES, App: YES
,2016-07-06 14:31:05.507 ThaliTest[6404:19862959] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 14:31:06.306 ThaliTest[6404:19862959] Using UIWebView
,2016-07-06 14:31:06.309 ThaliTest[6404:19862959] [CDVTimer][handleopenurl] 0.146031ms
,2016-07-06 14:31:06.311 ThaliTest[6404:19862959] [CDVTimer][intentandnavigationfilter] 2.258003ms
2016-07-06 14:31:06.311 ThaliTest[6404:19862959] [CDVTimer][gesturehandler] 0.110030ms
2016-07-06 14:31:06.312 ThaliTest[6404:19862959] [CDVTimer][TotalPluginStartup] 3.028035ms
,2016-07-06 14:31:09.479 ThaliTest[6404:19862959] Resetting plugins due to page load.
,2016-07-06 14:31:10.766 ThaliTest[6404:19862959] Finished load of: file:///var/mobile/Containers/Bundle/Application/E7AC32E1-B2B5-4159-97E1-7B7E783A3E51/ThaliTest.app/www/index.html
,2016-07-06 14:31:10.920 ThaliTest[6404:19862959] JXcore Cordova plugin initializing
,2016-07-06 14:31:10.922 ThaliTest[6404:19863116] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
