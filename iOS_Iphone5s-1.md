#### Test 757892681403989_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8549D5CE-5A66-44F9-A1EB-BEF89F096C25/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8549D5CE-5A66-44F9-A1EB-BEF89F096C25/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/93D2BF1E-A892-4FA4-8606-5A88FA35463B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49928"
,(lldb)     command script import "/tmp/8549D5CE-5A66-44F9-A1EB-BEF89F096C25/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:57:55.409 ThaliTest[6376:19337514] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96D7258E-70FC-49B0-95D5-2BA721F77F27/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:57:55.689 ThaliTest[6376:19337514] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 11:57:55.690 ThaliTest[6376:19337514] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:57:55.706 ThaliTest[6376:19337514] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:57:56.535 ThaliTest[6376:19337514] Using UIWebView
2016-07-05 11:57:56.538 ThaliTest[6376:19337514] [CDVTimer][handleopenurl] 0.153005ms
,2016-07-05 11:57:56.542 ThaliTest[6376:19337514] [CDVTimer][intentandnavigationfilter] 3.776014ms
2016-07-05 11:57:56.542 ThaliTest[6376:19337514] [CDVTimer][gesturehandler] 0.166953ms
2016-07-05 11:57:56.542 ThaliTest[6376:19337514] [CDVTimer][TotalPlug,inStartup] 4.736006ms
,2016-07-05 11:57:59.782 ThaliTest[6376:19337514] Resetting plugins due to page load.
,2016-07-05 11:58:01.294 ThaliTest[6376:19337514] Finished load of: file:///var/mobile/Containers/Bundle/Application/93D2BF1E-A892-4FA4-8606-5A88FA35463B/ThaliTest.app/www/index.html
,2016-07-05 11:58:01.483 ThaliTest[6376:19337514] JXcore Cordova plugin initializing
2016-07-05 11:58:01.483 ThaliTest[6376:19337675] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).

```
