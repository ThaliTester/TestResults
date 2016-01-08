#### Test 5024228542a63d7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/09580A61-C259-4DFC-AA3B-AE3764379661/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/09580A61-C259-4DFC-AA3B-AE3764379661/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CCC46A65-3731-47C0-B42D-64BFDB57C460/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50844"
,(lldb)     command script import "/tmp/09580A61-C259-4DFC-AA3B-AE3764379661/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 19:08:38.511 HelloWorld[1124:3612611] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C418DC75-E686-4F24-97AE-C11ADC4A5BF3/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:08:39.031 HelloWorld[1124:3612611] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:08:39.032 HelloWorld[1124:3612611] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:08:39.039 HelloWorld[1124:3612611] Unlimited access to network resources
,2016-01-08 19:08:39.050 HelloWorld[1124:3612611] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:08:48.804 HelloWorld[1124:3612611] Resetting plugins due to page load.
,2016-01-08 19:08:52.140 HelloWorld[1124:3612611] Finished load of: file:///var/mobile/Containers/Bundle/Application/CCC46A65-3731-47C0-B42D-64BFDB57C460/HelloWorld.app/www/index.html
,2016-01-08 19:08:52.223 HelloWorld[1124:3612611] JXcore Cordova plugin initializing
,2016-01-08 19:08:52.226 HelloWorld[1124:3612801] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5-1

,Total memory 1064304640

Free memory 398168064

execPath /private/var/mobile/Containers/Bundle/Application/CCC46A65-3731-47C0-B42D-64BFDB57C460/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/CCC46A65-3731-47C0-B42D-6,4BFDB57C460/HelloWorld.app/www/jxcore/

,userPath []

2016-01-08 19:08:52.642 HelloWorld[1124:3612801] Native method ScreenInfo not found.
2016-01-08 19:08:52.642 HelloWorld[1124:3612801] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5220  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
