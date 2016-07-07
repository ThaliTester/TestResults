#### Test 757892685345aa0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/22C872CC-342E-4297-9244-CBA71FA669A5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/22C872CC-342E-4297-9244-CBA71FA669A5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685345aa0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DBC31A43-7F7A-4730-8E6E-9DD0AA162FAF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51407"
,(lldb)     command script import "/tmp/22C872CC-342E-4297-9244-CBA71FA669A5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:44:07.382 ThaliTest[6460:20025600] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05BF2B41-5B45-4579-9423-F02277CB409F/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:44:07.617 ThaliTest[6460:20025600] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:44:07.618 ThaliTest[6460:20025600] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:44:07.634 ThaliTest[6460:20025600] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:44:08.405 ThaliTest[6460:20025600] Using UIWebView
,2016-07-07 15:44:08.408 ThaliTest[6460:20025600] [CDVTimer][handleopenurl] 0.287950ms
,2016-07-07 15:44:08.410 ThaliTest[6460:20025600] [CDVTimer][intentandnavigationfilter] 2.218008ms
2016-07-07 15:44:08.410 ThaliTest[6460:20025600] [CDVTimer][gesturehandler] 0.122011ms
2016-07-07 15:44:08.411 ThaliTest[6460:20025600] [CDVTimer][TotalPluginStartup] 3.151000ms
,2016-07-07 15:44:11.559 ThaliTest[6460:20025600] Resetting plugins due to page load.
,2016-07-07 15:44:12.971 ThaliTest[6460:20025600] Finished load of: file:///var/mobile/Containers/Bundle/Application/DBC31A43-7F7A-4730-8E6E-9DD0AA162FAF/ThaliTest.app/www/index.html
,2016-07-07 15:44:13.125 ThaliTest[6460:20025600] JXcore Cordova plugin initializing
2016-07-07 15:44:13.126 ThaliTest[6460:20025757] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
