#### Test 757892685fc4836_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F20673B1-DE70-4F64-A775-A0E931216EE2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F20673B1-DE70-4F64-A775-A0E931216EE2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892685fc4836/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C66108FA-379C-4616-B5DA-B7E4A2485183/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50433"
,(lldb)     command script import "/tmp/F20673B1-DE70-4F64-A775-A0E931216EE2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 15:35:06.963 ThaliTest[6416:19366338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1B3E8B8-6898-4814-8C85-2B9182072F93/Library/Cookies/Cookies.binarycookies
,2016-07-05 15:35:07.222 ThaliTest[6416:19366338] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 15:35:07.223 ThaliTest[6416:19366338] Multi-tasking -> Device: YES, App: YES
,2016-07-05 15:35:07.240 ThaliTest[6416:19366338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 15:35:08.065 ThaliTest[6416:19366338] Using UIWebView
2016-07-05 15:35:08.068 ThaliTest[6416:19366338] [CDVTimer][handleopenurl] 0.176013ms
,2016-07-05 15:35:08.071 ThaliTest[6416:19366338] [CDVTimer][intentandnavigationfilter] 3.789961ms
2016-07-05 15:35:08.072 ThaliTest[6416:19366338] [CDVTimer][gesturehandler] 0.140011ms
2016-07-05 15:35:08.072 ThaliTest[6416:19366338] [CDVTimer][TotalPlug,inStartup] 4.711032ms
,2016-07-05 15:35:11.330 ThaliTest[6416:19366338] Resetting plugins due to page load.
,2016-07-05 15:35:12.841 ThaliTest[6416:19366338] Finished load of: file:///var/mobile/Containers/Bundle/Application/C66108FA-379C-4616-B5DA-B7E4A2485183/ThaliTest.app/www/index.html
,2016-07-05 15:35:13.024 ThaliTest[6416:19366338] JXcore Cordova plugin initializing
,2016-07-05 15:35:13.026 ThaliTest[6416:19366479] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
