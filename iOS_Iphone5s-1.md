#### Test 7578926821ef376_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/ACAB22C5-5A22-4B19-9906-E0C85C43BD0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/ACAB22C5-5A22-4B19-9906-E0C85C43BD0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7578926821ef376/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/94054A3E-62B2-453D-B258-9C07F2761F52/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51495"
,(lldb)     command script import "/tmp/ACAB22C5-5A22-4B19-9906-E0C85C43BD0E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 20:24:21.709 ThaliTest[6553:19705773] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B7B07A0-48D0-4736-97AF-596893FD1B1E/Library/Cookies/Cookies.binarycookies
,2016-07-07 20:24:21.967 ThaliTest[6553:19705773] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 20:24:21.968 ThaliTest[6553:19705773] Multi-tasking -> Device: YES, App: YES
,2016-07-07 20:24:21.986 ThaliTest[6553:19705773] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 20:24:22.818 ThaliTest[6553:19705773] Using UIWebView
2016-07-07 20:24:22.820 ThaliTest[6553:19705773] [CDVTimer][handleopenurl] 0.160992ms
,2016-07-07 20:24:22.824 ThaliTest[6553:19705773] [CDVTimer][intentandnavigationfilter] 3.709018ms
2016-07-07 20:24:22.825 ThaliTest[6553:19705773] [CDVTimer][gesturehandler] 0.161052ms
2016-07-07 20:24:22.825 ThaliTest[6553:19705773] [CDVTimer][TotalPluginStartup] 4.635036ms
,2016-07-07 20:24:26.074 ThaliTest[6553:19705773] Resetting plugins due to page load.
,2016-07-07 20:24:27.554 ThaliTest[6553:19705773] Finished load of: file:///var/mobile/Containers/Bundle/Application/94054A3E-62B2-453D-B258-9C07F2761F52/ThaliTest.app/www/index.html
,2016-07-07 20:24:27.728 ThaliTest[6553:19705773] JXcore Cordova plugin initializing
2016-07-07 20:24:27.729 ThaliTest[6553:19705912] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
