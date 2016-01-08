#### Test 5497026140aeaf4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F3005E3A-B58D-49AC-852A-D452550C8090/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F3005E3A-B58D-49AC-852A-D452550C8090/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026140aeaf4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/87B28EC9-A139-4AFC-849E-5AAC992665AA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51026"
,(lldb)     command script import "/tmp/F3005E3A-B58D-49AC-852A-D452550C8090/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 19:36:49.620 ThaliTest[1566:3236497] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/59F26E1D-C65C-40CB-A61D-CCF35268AF13/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:36:50.061 ThaliTest[1566:3236497] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:36:50.062 ThaliTest[1566:3236497] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:36:50.072 ThaliTest[1566:3236497] Unlimited access to network resources
,2016-01-08 19:36:50.090 ThaliTest[1566:3236497] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:36:58.492 ThaliTest[1566:3236497] Resetting plugins due to page load.
,2016-01-08 19:37:01.791 ThaliTest[1566:3236497] Finished load of: file:///var/mobile/Containers/Bundle/Application/87B28EC9-A139-4AFC-849E-5AAC992665AA/ThaliTest.app/www/index.html
,2016-01-08 19:37:01.984 ThaliTest[1566:3236497] JXcore Cordova plugin initializing
,2016-01-08 19:37:01.986 ThaliTest[1566:3236689] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
