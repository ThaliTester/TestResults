#### Test 61703351436c7c0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/AC0C7F84-E790-4E63-B788-C7133FC61F04/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AC0C7F84-E790-4E63-B788-C7133FC61F04/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E3B65603-5DCD-4AD3-86B7-C03F56C3A170/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49860"
,(lldb)     command script import "/tmp/AC0C7F84-E790-4E63-B788-C7133FC61F04/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 15:19:52.979 HelloWorld[756:1602427] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/89288099-9C1D-43A0-A8CD-1CB1B7C4A8E2/Library/Cookies/Cookies.binarycookies
,2016-03-09 15:19:53.107 HelloWorld[756:1602427] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-09 15:19:53.109 HelloWorld[756:1602427] Multi-tasking -> Device: YES, App: YES
,2016-03-09 15:19:53.116 HelloWorld[756:1602427] Unlimited access to network resources
,2016-03-09 15:19:53.130 HelloWorld[756:1602427] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 15:20:03.395 HelloWorld[756:1602427] Resetting plugins due to page load.
,2016-03-09 15:20:06.925 HelloWorld[756:1602427] Finished load of: file:///var/mobile/Containers/Bundle/Application/E3B65603-5DCD-4AD3-86B7-C03F56C3A170/HelloWorld.app/www/index.html
,2016-03-09 15:20:07.052 HelloWorld[756:1602427] JXcore Cordova plugin initializing
2016-03-09 15:20:07.054 HelloWorld[756:1602604] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5-1

,Total memory 1064304640

Free memory 453808128

execPath /private/var/mobile/Containers/Bundle/Application/E3B65603-5DCD-4AD3-86B7-C03F56C3A170/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/E3B65603-5DCD-4AD3-86B7-C,03F56C3A170/HelloWorld.app/www/jxcore/

userPath []

2016-03-09 15:20:07.489 HelloWorld[756:1602604] Native method ScreenInfo not found.
2016-03-09 15:20:07.490 HelloWorld[756:1602604] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5236  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
