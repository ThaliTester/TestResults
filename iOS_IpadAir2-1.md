#### Test 757892685041341_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B2459503-CEE0-4BC1-99C5-5621E814567D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B2459503-CEE0-4BC1-99C5-5621E814567D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685041341/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E1CEC040-2DAB-4226-B6EA-191D83A76517/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50933"
,(lldb)     command script import "/tmp/B2459503-CEE0-4BC1-99C5-5621E814567D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-06 14:31:07.151 ThaliTest[3773:13761278] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/48AB1859-3598-4F61-AAFA-70417EB5AABE/Library/Cookies/Cookies.binarycookies
,2016-07-06 14:31:07.374 ThaliTest[3773:13761278] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-06 14:31:07.375 ThaliTest[3773:13761278] Multi-tasking -> Device: YES, App: YES
,2016-07-06 14:31:07.387 ThaliTest[3773:13761278] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-06 14:31:08.191 ThaliTest[3773:13761278] Using UIWebView
,2016-07-06 14:31:08.193 ThaliTest[3773:13761278] [CDVTimer][handleopenurl] 0.100970ms
,2016-07-06 14:31:08.195 ThaliTest[3773:13761278] [CDVTimer][intentandnavigationfilter] 1.821995ms
,2016-07-06 14:31:08.195 ThaliTest[3773:13761278] [CDVTimer][gesturehandler] 0.090003ms
,2016-07-06 14:31:08.195 ThaliTest[3773:13761278] [CDVTimer][TotalPluginStartup] 2.426982ms
,2016-07-06 14:31:11.456 ThaliTest[3773:13761278] Resetting plugins due to page load.
,2016-07-06 14:31:12.919 ThaliTest[3773:13761278] Finished load of: file:///var/mobile/Containers/Bundle/Application/E1CEC040-2DAB-4226-B6EA-191D83A76517/ThaliTest.app/www/index.html
,2016-07-06 14:31:13.050 ThaliTest[3773:13761278] JXcore Cordova plugin initializing
2016-07-06 14:31:13.051 ThaliTest[3773:13761437] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
