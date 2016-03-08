#### Test 61703351926082e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8A37E44B-F7D4-4428-A29D-3C3ED6717C57/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8A37E44B-F7D4-4428-A29D-3C3ED6717C57/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F08F8123-4130-4100-A9FE-7856B4A4962F/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49213"
,(lldb)     command script import "/tmp/8A37E44B-F7D4-4428-A29D-3C3ED6717C57/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 08:56:39.078 HelloWorld[895:1315742] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9E29DD96-48BB-4D99-97E7-F7B534BF8B17/Library/Cookies/Cookies.binarycookies
,2016-03-08 08:56:39.486 HelloWorld[895:1315742] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 08:56:39.487 HelloWorld[895:1315742] Multi-tasking -> Device: YES, App: YES
,2016-03-08 08:56:39.491 HelloWorld[895:1315742] Unlimited access to network resources
,2016-03-08 08:56:39.502 HelloWorld[895:1315742] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 08:56:47.990 HelloWorld[895:1315742] Resetting plugins due to page load.
,2016-03-08 08:56:50.816 HelloWorld[895:1315742] Finished load of: file:///var/mobile/Containers/Bundle/Application/F08F8123-4130-4100-A9FE-7856B4A4962F/HelloWorld.app/www/index.html
,2016-03-08 08:56:50.909 HelloWorld[895:1315742] JXcore Cordova plugin initializing
2016-03-08 08:56:50.910 HelloWorld[895:1315959] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5s-1

,Total memory 1048576000

Free memory 602308608

execPath /private/var/mobile/Containers/Bundle/Application/F08F8123-4130-4100-A9FE-7856B4A4962F/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/F08F8123-4130-4100-A9FE-7,856B4A4962F/HelloWorld.app/www/jxcore/

userPath []

2016-03-08 08:56:51.136 HelloWorld[895:1315959] Native method ScreenInfo not found.
2016-03-08 08:56:51.136 HelloWorld[895:1315959] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5132  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
