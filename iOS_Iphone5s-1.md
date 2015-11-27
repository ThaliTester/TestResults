#### Test 506502789318894_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/81F09E87-A241-41F8-95ED-2BADCEF59E62/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/81F09E87-A241-41F8-95ED-2BADCEF59E62/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789318894/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/61E5FBE4-6B84-44E6-8383-96728888A54D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56814"
,(lldb)     command script import "/tmp/81F09E87-A241-41F8-95ED-2BADCEF59E62/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 12:40:18.701 ThaliTest[1843:1599630] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D77617B-C3CE-4E5C-8D73-50968FAFA94C/Library/Cookies/Cookies.binarycookies
,2015-11-27 12:40:19.113 ThaliTest[1843:1599630] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 12:40:19.114 ThaliTest[1843:1599630] Multi-tasking -> Device: YES, App: YES
,2015-11-27 12:40:19.123 ThaliTest[1843:1599630] Unlimited access to network resources
,2015-11-27 12:40:19.132 ThaliTest[1843:1599630] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 12:40:22.764 ThaliTest[1843:1599630] Resetting plugins due to page load.
,2015-11-27 12:40:22.961 ThaliTest[1843:1599630] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/61E5FBE4-6B84-44E6-8383-96728888A54D/ThaliTest.app/www/index.html
,2015-11-27 12:40:23.107 ThaliTest[1843:1599630] JXcore Cordova plugin initializing
2015-11-27 12:40:23.108 ThaliTest[1843:1599749] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,my name is : Apple-Iphone5s-1_PT7234
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
