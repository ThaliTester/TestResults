#### Test 50650278c0f6ec2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/26A959B6-EB51-4487-A05F-4F5FD813D414/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/26A959B6-EB51-4487-A05F-4F5FD813D414/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FDB0EE9B-97EB-445B-A0D5-0874CF22CB25/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53120"
,(lldb)     command script import "/tmp/26A959B6-EB51-4487-A05F-4F5FD813D414/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-10 12:55:43.717 ThaliTest[671:563119] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A61E29B1-6BEB-4206-9FEC-AE9D08C48533/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:55:44.115 ThaliTest[671:563119] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:55:44.117 ThaliTest[671:563119] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:55:44.127 ThaliTest[671:563119] Unlimited access to network resources
,2015-12-10 12:55:44.138 ThaliTest[671:563119] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:55:52.442 ThaliTest[671:563119] Resetting plugins due to page load.
,2015-12-10 12:55:55.284 ThaliTest[671:563119] Finished load of: file:///var/mobile/Containers/Bundle/Application/FDB0EE9B-97EB-445B-A0D5-0874CF22CB25/ThaliTest.app/www/index.html
,2015-12-10 12:55:55.465 ThaliTest[671:563119] JXcore Cordova plugin initializing
2015-12-10 12:55:55.468 ThaliTest[671:563302] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
