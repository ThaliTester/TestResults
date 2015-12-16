#### Test 50650278dbf8a2a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4D3D6086-9C06-4BA4-B226-646E4A8E537C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4D3D6086-9C06-4BA4-B226-646E4A8E537C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B75ACEBC-3FB9-4F39-A280-76DFCCFCA18A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57948"
,(lldb)     command script import "/tmp/4D3D6086-9C06-4BA4-B226-646E4A8E537C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 01:38:02.636 ThaliTest[225:23673] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/81F3DBEE-B187-4BDB-AD6A-D9F0387376F8/Library/Cookies/Cookies.binarycookies
,2015-12-16 01:38:03.038 ThaliTest[225:23673] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 01:38:03.040 ThaliTest[225:23673] Multi-tasking -> Device: YES, App: YES
,2015-12-16 01:38:03.049 ThaliTest[225:23673] Unlimited access to network resources
,2015-12-16 01:38:03.062 ThaliTest[225:23673] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 01:38:12.000 ThaliTest[225:23673] Resetting plugins due to page load.
,2015-12-16 01:38:15.155 ThaliTest[225:23673] Finished load of: file:///var/mobile/Containers/Bundle/Application/B75ACEBC-3FB9-4F39-A280-76DFCCFCA18A/ThaliTest.app/www/index.html
,2015-12-16 01:38:15.378 ThaliTest[225:23673] JXcore Cordova plugin initializing
,2015-12-16 01:38:15.379 ThaliTest[225:23905] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 01:38:16.711 ThaliTest[225:23673] THREAD WARNING: ['JXcore'] took '89.865967' ms. Plugin should use a background thread.
,Connected to the server!

```
