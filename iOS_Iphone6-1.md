#### Test 56151093f3290d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/46ABEACD-DA53-4304-AFDC-75A0286A25E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/46ABEACD-DA53-4304-AFDC-75A0286A25E3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093f3290d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF7969ED-0426-4B81-8DC1-5B7C5F25B880/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56373"
,(lldb)     command script import "/tmp/46ABEACD-DA53-4304-AFDC-75A0286A25E3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 13:59:26.972 ThaliTest[2012:4226497] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BAE7AF97-D837-4A5D-A913-303E3CA5B2C0/Library/Cookies/Cookies.binarycookies
,2016-01-15 13:59:27.215 ThaliTest[2012:4226497] Apache Cordova native platform version 3.9.2 is starting.
2016-01-15 13:59:27.215 ThaliTest[2012:4226497] Multi-tasking -> Device: YES, App: YES
,2016-01-15 13:59:27.222 ThaliTest[2012:4226497] Unlimited access to network resources
2016-01-15 13:59:27.228 ThaliTest[2012:4226497] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.,
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 13:59:31.418 ThaliTest[2012:4226497] Resetting plugins due to page load.
,2016-01-15 13:59:32.938 ThaliTest[2012:4226497] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF7969ED-0426-4B81-8DC1-5B7C5F25B880/ThaliTest.app/www/index.html
,2016-01-15 13:59:33.097 ThaliTest[2012:4226497] JXcore Cordova plugin initializing
2016-01-15 13:59:33.098 ThaliTest[2012:4226651] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1

```
