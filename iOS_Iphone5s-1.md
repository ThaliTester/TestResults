#### Test 50242285ae22b3b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285ae22b3b/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/84E33873-9F3F-4B74-82B4-61BCCC056604/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/84E33873-9F3F-4B74-82B4-61BCCC056604/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285ae22b3b/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285ae22b3b/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6395D47B-B914-4FAE-866F-A55566AC20D5/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50109"
,(lldb)     command script import "/tmp/84E33873-9F3F-4B74-82B4-61BCCC056604/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 14:48:57.146 HelloWorld[1499:3200055] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A50995E0-FD35-4CBC-9665-0C7C5A4A01A6/Library/Cookies/Cookies.binarycookies
,2016-01-08 14:48:57.578 HelloWorld[1499:3200055] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 14:48:57.579 HelloWorld[1499:3200055] Multi-tasking -> Device: YES, App: YES
,2016-01-08 14:48:57.583 HelloWorld[1499:3200055] Unlimited access to network resources
,2016-01-08 14:48:57.593 HelloWorld[1499:3200055] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 14:49:06.198 HelloWorld[1499:3200055] Resetting plugins due to page load.
,2016-01-08 14:49:09.656 HelloWorld[1499:3200055] Finished load of: file:///var/mobile/Containers/Bundle/Application/6395D47B-B914-4FAE-866F-A55566AC20D5/HelloWorld.app/www/index.html
,2016-01-08 14:49:09.760 HelloWorld[1499:3200055] JXcore Cordova plugin initializing
2016-01-08 14:49:09.762 HelloWorld[1499:3200230] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5s-1

Total memory 1048576000

Free memory 1035812864

execPath /private/var/mobile/Containers/Bundle/Application/6395D47B-B914-4FAE-866F-A55566AC20D5/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/6,395D47B-B914-4FAE-866F-A55566AC20D5/HelloWorld.app/www/jxcore/

userPath []

2016-01-08 14:49:09.989 HelloWorld[1499:3200230] Native method ScreenInfo not found.
2016-01-08 14:49:09.989 HelloWorld[1499:3200230] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5133  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
