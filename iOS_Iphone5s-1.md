#### Test 506502783fcf234_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7D7453F9-BECA-4228-9201-AB0DE15A3D0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7D7453F9-BECA-4228-9201-AB0DE15A3D0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15EA5F0F-FBBD-454C-9E58-FCE41BB3C5D1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58356"
,(lldb)     command script import "/tmp/7D7453F9-BECA-4228-9201-AB0DE15A3D0E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 04:56:11.041 ThaliTest[257:44596] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1565773B-5F8E-409D-B3BA-771B220AC1E0/Library/Cookies/Cookies.binarycookies
,2015-12-16 04:56:11.476 ThaliTest[257:44596] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 04:56:11.477 ThaliTest[257:44596] Multi-tasking -> Device: YES, App: YES
,2015-12-16 04:56:11.486 ThaliTest[257:44596] Unlimited access to network resources
,2015-12-16 04:56:11.500 ThaliTest[257:44596] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 04:56:19.254 ThaliTest[257:44596] Resetting plugins due to page load.
,2015-12-16 04:56:22.383 ThaliTest[257:44596] Finished load of: file:///var/mobile/Containers/Bundle/Application/15EA5F0F-FBBD-454C-9E58-FCE41BB3C5D1/ThaliTest.app/www/index.html
,2015-12-16 04:56:22.596 ThaliTest[257:44596] JXcore Cordova plugin initializing
,2015-12-16 04:56:22.597 ThaliTest[257:44800] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 04:56:23.910 ThaliTest[257:44596] THREAD WARNING: ['JXcore'] took '86.848877' ms. Plugin should use a background thread.
,Connected to the server!

```
