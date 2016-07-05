#### Test 75789268eab05ed_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/DA35C66E-97CA-4F17-AED1-7FB1B3F6805D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DA35C66E-97CA-4F17-AED1-7FB1B3F6805D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268eab05ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/62695439-0AEC-41E2-AB0E-60936E66E65D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49833"
,(lldb)     command script import "/tmp/DA35C66E-97CA-4F17-AED1-7FB1B3F6805D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-05 11:05:47.250 ThaliTest[6369:19332122] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A8BE712A-A95D-445E-8555-15676A65D88E/Library/Cookies/Cookies.binarycookies
,2016-07-05 11:05:47.504 ThaliTest[6369:19332122] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-05 11:05:47.505 ThaliTest[6369:19332122] Multi-tasking -> Device: YES, App: YES
,2016-07-05 11:05:47.524 ThaliTest[6369:19332122] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-05 11:05:48.326 ThaliTest[6369:19332122] Using UIWebView
2016-07-05 11:05:48.329 ThaliTest[6369:19332122] [CDVTimer][handleopenurl] 0.150979ms
,2016-07-05 11:05:48.333 ThaliTest[6369:19332122] [CDVTimer][intentandnavigationfilter] 3.903985ms
2016-07-05 11:05:48.333 ThaliTest[6369:19332122] [CDVTimer][gesturehandler] 0.163972ms
2016-07-05 11:05:48.333 ThaliTest[6369:19332122] [CDVTimer][TotalPluginStartup] 4.853010ms
,2016-07-05 11:05:51.610 ThaliTest[6369:19332122] Resetting plugins due to page load.
,2016-07-05 11:05:53.130 ThaliTest[6369:19332122] Finished load of: file:///var/mobile/Containers/Bundle/Application/62695439-0AEC-41E2-AB0E-60936E66E65D/ThaliTest.app/www/index.html
,2016-07-05 11:05:53.326 ThaliTest[6369:19332122] JXcore Cordova plugin initializing
,2016-07-05 11:05:53.327 ThaliTest[6369:19332292] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started

```
