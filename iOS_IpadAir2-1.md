#### Test 757892681403989_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/07DA1E7C-9354-4EAC-8265-29C9A43755BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/07DA1E7C-9354-4EAC-8265-29C9A43755BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892681403989/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9C4AF3ED-2033-484C-A2B4-48C3210D2EA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49924"
,(lldb)     command script import "/tmp/07DA1E7C-9354-4EAC-8265-29C9A43755BF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:57:54.528 ThaliTest[3651:13581716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F8783B36-D2FD-47CC-8CB9-1C363CB45693/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:57:54.759 ThaliTest[3651:13581716] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 11:57:54.760 ThaliTest[3651:13581716] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:57:54.772 ThaliTest[3651:13581716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:57:55.577 ThaliTest[3651:13581716] Using UIWebView
,2016-07-05 11:57:55.579 ThaliTest[3651:13581716] [CDVTimer][handleopenurl] 0.103951ms
,2016-07-05 11:57:55.581 ThaliTest[3651:13581716] [CDVTimer][intentandnavigationfilter] 1.798987ms
2016-07-05 11:57:55.581 ThaliTest[3651:13581716] [CDVTimer][gesturehandler] 0.082970ms
2016-07-05 11:57:55.581 ThaliTest[3651:13581716] [CDVTimer][TotalPlug,inStartup] 2.398014ms
,2016-07-05 11:57:58.757 ThaliTest[3651:13581716] Resetting plugins due to page load.
,2016-07-05 11:58:00.182 ThaliTest[3651:13581716] Finished load of: file:///var/mobile/Containers/Bundle/Application/9C4AF3ED-2033-484C-A2B4-48C3210D2EA1/ThaliTest.app/www/index.html
,2016-07-05 11:58:00.318 ThaliTest[3651:13581716] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2016-07-05 11:58:00.319 ThaliTest[3651:13581878] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).

```
