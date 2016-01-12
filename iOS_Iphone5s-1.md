#### Test 55613145ac448d4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7AED1278-BE42-4F84-B7CA-D360E1B0326D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
Executing commands in '/tmp/7AED1278-BE42-4F84-B7CA-D360E1B0326D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145ac448d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7426D2D4-A4A3-4A19-BC7C-E01A673865BD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53226"
,(lldb)     command script import "/tmp/7AED1278-BE42-4F84-B7CA-D360E1B0326D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-12 11:59:37.781 ThaliTest[1790:3966572] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B05B6955-EA92-4B13-9550-ACBCE8EF6573/Library/Cookies/Cookies.binarycookies
,2016-01-12 11:59:38.044 ThaliTest[1790:3966572] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-12 11:59:38.045 ThaliTest[1790:3966572] Multi-tasking -> Device: YES, App: YES
,2016-01-12 11:59:38.053 ThaliTest[1790:3966572] Unlimited access to network resources
,2016-01-12 11:59:38.062 ThaliTest[1790:3966572] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 11:59:41.954 ThaliTest[1790:3966572] Resetting plugins due to page load.
,2016-01-12 11:59:43.350 ThaliTest[1790:3966572] Finished load of: file:///var/mobile/Containers/Bundle/Application/7426D2D4-A4A3-4A19-BC7C-E01A673865BD/ThaliTest.app/www/index.html
,2016-01-12 11:59:43.544 ThaliTest[1790:3966572] JXcore Cordova plugin initializing
2016-01-12 11:59:43.545 ThaliTest[1790:3966738] JXcore instance initializing
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
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
