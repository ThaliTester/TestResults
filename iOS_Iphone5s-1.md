#### Test 75789268d2ecd3a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/DDEBC3A6-3FD4-4A03-A2E1-6FE8E9A8CB4D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DDEBC3A6-3FD4-4A03-A2E1-6FE8E9A8CB4D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268d2ecd3a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/79256EA8-5438-40FE-9094-23C241D4B2F6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51896"
,(lldb)     command script import "/tmp/DDEBC3A6-3FD4-4A03-A2E1-6FE8E9A8CB4D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-08 13:59:18.589 ThaliTest[6588:19816500] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BDB86C30-4874-4E9E-B7A8-1D74920683EA/Library/Cookies/Cookies.binarycookies
,2016-07-08 13:59:18.841 ThaliTest[6588:19816500] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-08 13:59:18.842 ThaliTest[6588:19816500] Multi-tasking -> Device: YES, App: YES
,2016-07-08 13:59:18.862 ThaliTest[6588:19816500] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-08 13:59:19.688 ThaliTest[6588:19816500] Using UIWebView
,2016-07-08 13:59:19.691 ThaliTest[6588:19816500] [CDVTimer][handleopenurl] 0.176966ms
,2016-07-08 13:59:19.694 ThaliTest[6588:19816500] [CDVTimer][intentandnavigationfilter] 2.803981ms
2016-07-08 13:59:19.695 ThaliTest[6588:19816500] [CDVTimer][gesturehandler] 0.154972ms
2016-07-08 13:59:19.695 ThaliTest[6588:19816500] [CDVTimer][TotalPluginStartup] 3.858984ms
,2016-07-08 13:59:22.914 ThaliTest[6588:19816500] Resetting plugins due to page load.
,2016-07-08 13:59:24.382 ThaliTest[6588:19816500] Finished load of: file:///var/mobile/Containers/Bundle/Application/79256EA8-5438-40FE-9094-23C241D4B2F6/ThaliTest.app/www/index.html
,2016-07-08 13:59:24.567 ThaliTest[6588:19816500] JXcore Cordova plugin initializing
2016-07-08 13:59:24.568 ThaliTest[6588:19816671] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
