#### Test 61432979f791f6f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1E8A5836-82BD-4521-8D6E-D623AA903938/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1E8A5836-82BD-4521-8D6E-D623AA903938/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/89D0E688-8C6E-43B5-A70F-503065C0A10D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49504"
,(lldb)     command script import "/tmp/1E8A5836-82BD-4521-8D6E-D623AA903938/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 09:04:25.500 ThaliTest[611:714971] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DFC3F07-D998-4AA0-81FA-DA2A5D0D41B1/Library/Cookies/Cookies.binarycookies
,2016-03-04 09:04:25.813 ThaliTest[611:714971] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 09:04:25.814 ThaliTest[611:714971] Multi-tasking -> Device: YES, App: YES
,2016-03-04 09:04:25.835 ThaliTest[611:714971] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 09:04:26.748 ThaliTest[611:714971] Using UIWebView
,2016-03-04 09:04:26.752 ThaliTest[611:714971] [CDVTimer][handleopenurl] 0.207961ms
,2016-03-04 09:04:26.756 ThaliTest[611:714971] [CDVTimer][intentandnavigationfilter] 3.556967ms
2016-03-04 09:04:26.756 ThaliTest[611:714971] [CDVTimer][gesturehandler] 0.127971ms
2016-03-04 09:04:26.756 ThaliTest[611:714971] [CDVTimer][TotalPluginStartup,] 4.604995ms
,2016-03-04 09:04:30.411 ThaliTest[611:714971] Resetting plugins due to page load.
,2016-03-04 09:04:31.893 ThaliTest[611:714971] Finished load of: file:///var/mobile/Containers/Bundle/Application/89D0E688-8C6E-43B5-A70F-503065C0A10D/ThaliTest.app/www/index.html
,2016-03-04 09:04:32.127 ThaliTest[611:714971] JXcore Cordova plugin initializing
,2016-03-04 09:04:32.131 ThaliTest[611:715136] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,2016-03-04 09:06:04.595 ThaliTest[611:714971] Received memory warning.
2016-03-04 09:06:04.605 ThaliTest[611:714971] Received memory warning.
,2016-03-04 09:06:06.271 ThaliTest[611:714971] Received memory warning.
,Process 611 exited with status = 0 (0x00000000) Terminated due to memory issue

```
