#### Test 502422853393492_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/FF2FB2F9-7AF3-4BD9-8E79-763B71FBA024/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FF2FB2F9-7AF3-4BD9-8E79-763B71FBA024/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2F681B10-4CDD-401C-9634-99CA95B43424/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49365"
,(lldb)     command script import "/tmp/FF2FB2F9-7AF3-4BD9-8E79-763B71FBA024/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-06 15:57:52.076 HelloWorld[306:20125] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3832EE11-120A-4561-BFC2-B68377BD94A7/Library/Cookies/Cookies.binarycookies
,2015-12-06 15:57:52.482 HelloWorld[306:20125] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-06 15:57:52.484 HelloWorld[306:20125] Multi-tasking -> Device: YES, App: YES
,2015-12-06 15:57:52.487 HelloWorld[306:20125] Unlimited access to network resources
,2015-12-06 15:57:52.499 HelloWorld[306:20125] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-06 15:58:00.789 HelloWorld[306:20125] Resetting plugins due to page load.
,2015-12-06 15:58:03.599 HelloWorld[306:20125] Finished load of: file:///var/mobile/Containers/Bundle/Application/2F681B10-4CDD-401C-9634-99CA95B43424/HelloWorld.app/www/index.html
,2015-12-06 15:58:03.747 HelloWorld[306:20125] JXcore Cordova plugin initializing
2015-12-06 15:58:03.748 HelloWorld[306:20323] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1048576000
Free memory 689750016
execPath /private/var/mobile/Containers/Bundle/Application/2F681B10-4CDD-401C-9634-99CA95B43424/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/2F681B10-4,CDD-401C-9634-99CA95B43424/HelloWorld.app/www/jxcore/
userPath []
2015-12-06 15:58:03.993 HelloWorld[306:20323] Native method ScreenInfo not found.
2015-12-06 15:58:03.993 HelloWorld[306:20323] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5131  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
