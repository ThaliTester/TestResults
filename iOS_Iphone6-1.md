#### Test 7578926821ef376_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/609A904F-7D7B-46CF-A72E-99C0834BCA20/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/609A904F-7D7B-46CF-A72E-99C0834BCA20/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2EDA05AF-CF2C-4B5B-9859-5C386073B066/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51493"
,(lldb)     command script import "/tmp/609A904F-7D7B-46CF-A72E-99C0834BCA20/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 20:24:20.092 ThaliTest[6472:20056996] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/00A1CD35-5537-4088-B00D-560299F7B00F/Library/Cookies/Cookies.binarycookies
,2016-07-07 20:24:20.317 ThaliTest[6472:20056996] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 20:24:20.318 ThaliTest[6472:20056996] Multi-tasking -> Device: YES, App: YES
,2016-07-07 20:24:20.334 ThaliTest[6472:20056996] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 20:24:21.102 ThaliTest[6472:20056996] Using UIWebView
2016-07-07 20:24:21.104 ThaliTest[6472:20056996] [CDVTimer][handleopenurl] 0.133991ms
2016-07-07 20:24:21.106 ThaliTest[6472:20056996] [CDVTimer][intentandnavigationfilter] 2.129018ms
2016,-07-07 20:24:21.107 ThaliTest[6472:20056996] [CDVTimer][gesturehandler] 0.093997ms
2016-07-07 20:24:21.107 ThaliTest[6472:20056996] [CDVTimer][TotalPluginStartup] 2.775967ms
,2016-07-07 20:24:24.289 ThaliTest[6472:20056996] Resetting plugins due to page load.
,2016-07-07 20:24:25.675 ThaliTest[6472:20056996] Finished load of: file:///var/mobile/Containers/Bundle/Application/2EDA05AF-CF2C-4B5B-9859-5C386073B066/ThaliTest.app/www/index.html
,2016-07-07 20:24:25.819 ThaliTest[6472:20056996] JXcore Cordova plugin initializing
,2016-07-07 20:24:25.820 ThaliTest[6472:20057131] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
