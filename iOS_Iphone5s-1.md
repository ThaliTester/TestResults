#### Test 506502784dae475_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/09EA917A-848F-45F4-87D6-CA44E5AE83C6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/09EA917A-848F-45F4-87D6-CA44E5AE83C6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FD0D084-70B0-4D0E-822C-727C61D56A98/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53246"
,(lldb)     command script import "/tmp/09EA917A-848F-45F4-87D6-CA44E5AE83C6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-10 13:35:31.015 ThaliTest[686:568468] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9664160B-D095-4EC2-A3BF-BF5CC52A375B/Library/Cookies/Cookies.binarycookies
,2015-12-10 13:35:31.432 ThaliTest[686:568468] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 13:35:31.433 ThaliTest[686:568468] Multi-tasking -> Device: YES, App: YES
,2015-12-10 13:35:31.444 ThaliTest[686:568468] Unlimited access to network resources
,2015-12-10 13:35:31.461 ThaliTest[686:568468] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 13:35:40.980 ThaliTest[686:568468] Resetting plugins due to page load.
,2015-12-10 13:35:45.146 ThaliTest[686:568468] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FD0D084-70B0-4D0E-822C-727C61D56A98/ThaliTest.app/www/index.html
,2015-12-10 13:35:45.360 ThaliTest[686:568468] JXcore Cordova plugin initializing
,2015-12-10 13:35:45.361 ThaliTest[686:568703] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
