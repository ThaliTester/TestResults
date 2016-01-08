#### Test 549702610b97681_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B32F6CCE-8959-4EF0-A680-2386979D9CB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B32F6CCE-8959-4EF0-A680-2386979D9CB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/348DFBD4-1515-4E5F-A227-309C02B04C25/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51518"
,(lldb)     command script import "/tmp/B32F6CCE-8959-4EF0-A680-2386979D9CB4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-09 00:04:00.356 ThaliTest[1601:3268315] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B886647-AB59-4B49-99A3-FF99E9842C2D/Library/Cookies/Cookies.binarycookies
,2016-01-09 00:04:00.731 ThaliTest[1601:3268315] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-09 00:04:00.732 ThaliTest[1601:3268315] Multi-tasking -> Device: YES, App: YES
,2016-01-09 00:04:00.741 ThaliTest[1601:3268315] Unlimited access to network resources
,2016-01-09 00:04:00.751 ThaliTest[1601:3268315] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-09 00:04:09.696 ThaliTest[1601:3268315] Resetting plugins due to page load.
,2016-01-09 00:04:13.603 ThaliTest[1601:3268315] Finished load of: file:///var/mobile/Containers/Bundle/Application/348DFBD4-1515-4E5F-A227-309C02B04C25/ThaliTest.app/www/index.html
,2016-01-09 00:04:13.806 ThaliTest[1601:3268315] JXcore Cordova plugin initializing
,2016-01-09 00:04:13.808 ThaliTest[1601:3268536] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
