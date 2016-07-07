#### Test 7578926821ef376_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5A74E2C7-9A98-4F27-A4A5-866E47717A72/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5A74E2C7-9A98-4F27-A4A5-866E47717A72/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/44120C09-2211-469A-B543-22FF79525139/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51491"
,(lldb)     command script import "/tmp/5A74E2C7-9A98-4F27-A4A5-866E47717A72/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 20:24:20.675 ThaliTest[3846:13961133] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB51C755-84D1-4233-B2C3-553B2AA83693/Library/Cookies/Cookies.binarycookies
,2016-07-07 20:24:20.907 ThaliTest[3846:13961133] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 20:24:20.908 ThaliTest[3846:13961133] Multi-tasking -> Device: YES, App: YES
,2016-07-07 20:24:20.921 ThaliTest[3846:13961133] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 20:24:21.748 ThaliTest[3846:13961133] Using UIWebView
,2016-07-07 20:24:21.750 ThaliTest[3846:13961133] [CDVTimer][handleopenurl] 0.155985ms
,2016-07-07 20:24:21.752 ThaliTest[3846:13961133] [CDVTimer][intentandnavigationfilter] 1.847029ms
2016-07-07 20:24:21.752 ThaliTest[3846:13961133] [CDVTimer][gesturehandler] 0.083983ms
2016-07-07 20:24:21.752 ThaliTest[3846:13961133] [CDVTimer][TotalPlug,inStartup] 2.512991ms
,2016-07-07 20:24:25.059 ThaliTest[3846:13961133] Resetting plugins due to page load.
,2016-07-07 20:24:26.471 ThaliTest[3846:13961133] Finished load of: file:///var/mobile/Containers/Bundle/Application/44120C09-2211-469A-B543-22FF79525139/ThaliTest.app/www/index.html
,2016-07-07 20:24:26.606 ThaliTest[3846:13961133] JXcore Cordova plugin initializing
,2016-07-07 20:24:26.607 ThaliTest[3846:13961306] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
