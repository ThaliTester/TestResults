#### Test 5038801932cd575_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/53E0DAC6-E06C-4D6B-AF19-8C7EA22485AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/53E0DAC6-E06C-4D6B-AF19-8C7EA22485AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/0684AD00-9554-4C13-91F0-9A887CDC7E4B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54020"
,(lldb)     command script import "/tmp/53E0DAC6-E06C-4D6B-AF19-8C7EA22485AD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 22:45:17.064 HelloWorld[668:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 22:45:17.068 HelloWorld[668:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-23 22:45:17.076 HelloWorld[668:60b] Unlimited access to network resources
,2015-11-23 22:45:17.082 HelloWorld[668:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 22:45:28.111 HelloWorld[668:60b] Resetting plugins due to page load.
,2015-11-23 22:45:28.953 HelloWorld[668:60b] Finished load of: file:///var/mobile/Applications/0684AD00-9554-4C13-91F0-9A887CDC7E4B/HelloWorld.app/www/index.html
,2015-11-23 22:45:29.019 HelloWorld[668:60b] JXcore Cordova plugin initializing
,2015-11-23 22:45:29.021 HelloWorld[668:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 588615680
execPath /private/var/mobile/Applications/0684AD00-9554-4C13-91F0-9A887CDC7E4B/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/0684AD00-9554-4C13-91F0-9A887CDC7E4B/HelloWor,ld.app/www/jxcore/
userPath []
,2015-11-23 22:45:29.489 HelloWorld[668:6807] Native method ScreenInfo not found.
,2015-11-23 22:45:29.491 HelloWorld[668:6807] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5258  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
