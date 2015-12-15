#### Test 50242285d7f7159_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/34B9DF69-F7CC-45CC-947C-F2C8EA55B923/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
Executing commands in '/tmp/34B9DF69-F7CC-45CC-947C-F2C8EA55B923/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2752F3AC-7B94-44AA-ACA3-C86E7FF11058/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57819"
,(lldb)     command script import "/tmp/34B9DF69-F7CC-45CC-947C-F2C8EA55B923/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 21:54:10.305 HelloWorld[201:4071] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0215578B-C31B-48D5-9A3C-86BE81E22F5C/Library/Cookies/Cookies.binarycookies
,2015-12-15 21:54:10.776 HelloWorld[201:4071] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 21:54:10.777 HelloWorld[201:4071] Multi-tasking -> Device: YES, App: YES
,2015-12-15 21:54:10.784 HelloWorld[201:4071] Unlimited access to network resources
,2015-12-15 21:54:10.796 HelloWorld[201:4071] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 21:54:20.945 HelloWorld[201:4071] Resetting plugins due to page load.
,2015-12-15 21:54:24.794 HelloWorld[201:4071] Finished load of: file:///var/mobile/Containers/Bundle/Application/2752F3AC-7B94-44AA-ACA3-C86E7FF11058/HelloWorld.app/www/index.html
,2015-12-15 21:54:24.893 HelloWorld[201:4071] JXcore Cordova plugin initializing
2015-12-15 21:54:24.894 HelloWorld[201:4265] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1064304640
Free memory 427032576
execPath /private/var/mobile/Containers/Bundle/Application/2752F3AC-7B94-44AA-ACA3-C86E7FF11058/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/2752F3AC-7B,94-44AA-ACA3-C86E7FF11058/HelloWorld.app/www/jxcore/
userPath []
2015-12-15 21:54:25.379 HelloWorld[201:4265] Native method ScreenInfo not found.
2015-12-15 21:54:25.379 HelloWorld[201:4265] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5248  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
