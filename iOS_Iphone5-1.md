#### Test 50242285feafdeb_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B347013C-A7E6-4E8F-AEC3-BBE2037AC716/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B347013C-A7E6-4E8F-AEC3-BBE2037AC716/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/962BF267-1A18-40AB-932B-8F1571E9B290/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52953"
,(lldb)     command script import "/tmp/B347013C-A7E6-4E8F-AEC3-BBE2037AC716/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 23:46:18.157 HelloWorld[1272:4110379] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6C517FA-E800-42E0-A92F-333F2F60E8A8/Library/Cookies/Cookies.binarycookies
,2016-01-11 23:46:18.517 HelloWorld[1272:4110379] Apache Cordova native platform version 3.9.2 is starting.
2016-01-11 23:46:18.518 HelloWorld[1272:4110379] Multi-tasking -> Device: YES, App: YES
,2016-01-11 23:46:18.522 HelloWorld[1272:4110379] Unlimited access to network resources
,2016-01-11 23:46:18.533 HelloWorld[1272:4110379] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 23:46:24.497 HelloWorld[1272:4110379] Resetting plugins due to page load.
,2016-01-11 23:46:26.539 HelloWorld[1272:4110379] Finished load of: file:///var/mobile/Containers/Bundle/Application/962BF267-1A18-40AB-932B-8F1571E9B290/HelloWorld.app/www/index.html
,2016-01-11 23:46:26.613 HelloWorld[1272:4110379] JXcore Cordova plugin initializing
,2016-01-11 23:46:26.619 HelloWorld[1272:4110492] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5-1

,Total memory 1064304640

Free memory 411537408

execPath /private/var/mobile/Containers/Bundle/Application/962BF267-1A18-40AB-932B-8F1571E9B290/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/962BF267-1A18-40AB-932B-8,F1571E9B290/HelloWorld.app/www/jxcore/

userPath []

2016-01-11 23:46:26.945 HelloWorld[1272:4110492] Native method ScreenInfo not found.
2016-01-11 23:46:26.945 HelloWorld[1272:4110492] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

Warning: iOS does not support ToggleWiFi

****TEST TOOK:  5171  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
