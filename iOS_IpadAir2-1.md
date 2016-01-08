#### Test 5024228542a63d7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B2A07414-4631-4C64-94A8-D130F1942DA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B2A07414-4631-4C64-94A8-D130F1942DA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4AD4A08B-BA8C-4329-8FD2-982A1AFE73B7/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50846"
,(lldb)     command script import "/tmp/B2A07414-4631-4C64-94A8-D130F1942DA4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 19:08:36.514 HelloWorld[1586:3360541] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C3C24FC-751F-4AD9-A68A-BE310ED16525/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:08:36.840 HelloWorld[1586:3360541] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:08:36.841 HelloWorld[1586:3360541] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:08:36.843 HelloWorld[1586:3360541] Unlimited access to network resources
,2016-01-08 19:08:36.848 HelloWorld[1586:3360541] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:08:45.935 HelloWorld[1586:3360541] Resetting plugins due to page load.
,2016-01-08 19:08:49.518 HelloWorld[1586:3360541] Finished load of: file:///var/mobile/Containers/Bundle/Application/4AD4A08B-BA8C-4329-8FD2-982A1AFE73B7/HelloWorld.app/www/index.html
,2016-01-08 19:08:49.592 HelloWorld[1586:3360541] JXcore Cordova plugin initializing
,2016-01-08 19:08:49.593 HelloWorld[1586:3360761] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-IpadAir2-1

,Total memory 2084569088

,Free memory 814710784

,execPath /private/var/mobile/Containers/Bundle/Application/4AD4A08B-BA8C-4329-8FD2-982A1AFE73B7/HelloWorld.app/HelloWorld

,process.cwd /var/mobile/Containers/Bundle/Application/4AD4A08B-BA8C-4329-8FD2-982A1AFE73B7/HelloWorld.app/www/jxcore/

,userPath []

,2016-01-08 19:08:49.776 HelloWorld[1586:3360761] Native method ScreenInfo not found.
2016-01-08 19:08:49.776 HelloWorld[1586:3360761] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

****TEST TOOK:  5114  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
