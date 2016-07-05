#### Test 757892681403989_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F8E3DB4E-24AA-4878-A034-E7A312B091F6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F8E3DB4E-24AA-4878-A034-E7A312B091F6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/76E437B6-1D3B-42CE-A290-D788DC550B36/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49926"
,(lldb)     command script import "/tmp/F8E3DB4E-24AA-4878-A034-E7A312B091F6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:57:54.165 ThaliTest[6290:19674164] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/73A50841-FB03-44CF-AAB3-06EE2D35275E/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:57:54.397 ThaliTest[6290:19674164] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 11:57:54.398 ThaliTest[6290:19674164] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:57:54.412 ThaliTest[6290:19674164] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:57:55.202 ThaliTest[6290:19674164] Using UIWebView
,2016-07-05 11:57:55.204 ThaliTest[6290:19674164] [CDVTimer][handleopenurl] 0.143051ms
2016-07-05 11:57:55.207 ThaliTest[6290:19674164] [CDVTimer][intentandnavigationfilter] 2.192974ms
2016-07-05 11:57:55.207 ThaliTest[6290:19674164] [CDVTimer][gesturehandler] 0.099003ms
2016-07-05 11:57:55.207 ThaliTest[6290:19674164] [CDVTimer][TotalPluginStartup] 3.518999ms
,2016-07-05 11:57:58.382 ThaliTest[6290:19674164] Resetting plugins due to page load.
,2016-07-05 11:57:59.820 ThaliTest[6290:19674164] Finished load of: file:///var/mobile/Containers/Bundle/Application/76E437B6-1D3B-42CE-A290-D788DC550B36/ThaliTest.app/www/index.html
,2016-07-05 11:57:59.980 ThaliTest[6290:19674164] JXcore Cordova plugin initializing
,2016-07-05 11:57:59.981 ThaliTest[6290:19674338] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).

```
