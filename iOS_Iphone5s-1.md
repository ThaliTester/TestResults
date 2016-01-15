#### Test 561510938d3c4f5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/561510938d3c4f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EB7007BF-FC05-45FB-8E0C-3DD989AAE18F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EB7007BF-FC05-45FB-8E0C-3DD989AAE18F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/561510938d3c4f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/561510938d3c4f5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B319741F-E40C-40EF-B18F-FAAEBFE0EC9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56279"
,(lldb)     command script import "/tmp/EB7007BF-FC05-45FB-8E0C-3DD989AAE18F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 13:18:44.230 ThaliTest[1977:4659941] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C35C7222-4BFE-4D6F-B2C6-6E82D06EAC9E/Library/Cookies/Cookies.binarycookies
,2016-01-15 13:18:44.480 ThaliTest[1977:4659941] Apache Cordova native platform version 3.9.2 is starting.
2016-01-15 13:18:44.481 ThaliTest[1977:4659941] Multi-tasking -> Device: YES, App: YES
,2016-01-15 13:18:44.487 ThaliTest[1977:4659941] Unlimited access to network resources
2016-01-15 13:18:44.495 ThaliTest[1977:4659941] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.,
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 13:18:48.409 ThaliTest[1977:4659941] Resetting plugins due to page load.
,2016-01-15 13:18:49.617 ThaliTest[1977:4659941] Finished load of: file:///var/mobile/Containers/Bundle/Application/B319741F-E40C-40EF-B18F-FAAEBFE0EC9C/ThaliTest.app/www/index.html
,2016-01-15 13:18:49.844 ThaliTest[1977:4659941] JXcore Cordova plugin initializing
,2016-01-15 13:18:49.846 ThaliTest[1977:4660095] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1

```
