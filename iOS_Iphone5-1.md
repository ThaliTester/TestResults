#### Test 61703351a2a4153_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D568E6C4-99E3-4C48-83A4-292B9E5A2386/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D568E6C4-99E3-4C48-83A4-292B9E5A2386/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF020594-306C-4745-B283-3BA5A10FAD1A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49724"
,(lldb)     command script import "/tmp/D568E6C4-99E3-4C48-83A4-292B9E5A2386/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 13:20:21.311 HelloWorld[541:833648] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E0BB267D-69AF-48B4-9D6A-E7AC69696046/Library/Cookies/Cookies.binarycookies
,2016-03-04 13:20:21.426 HelloWorld[541:833648] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-04 13:20:21.427 HelloWorld[541:833648] Multi-tasking -> Device: YES, App: YES
,2016-03-04 13:20:21.431 HelloWorld[541:833648] Unlimited access to network resources
,2016-03-04 13:20:21.443 HelloWorld[541:833648] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 13:20:31.129 HelloWorld[541:833648] Resetting plugins due to page load.
,2016-03-04 13:20:35.337 HelloWorld[541:833648] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF020594-306C-4745-B283-3BA5A10FAD1A/HelloWorld.app/www/index.html
,2016-03-04 13:20:35.416 HelloWorld[541:833648] JXcore Cordova plugin initializing
2016-03-04 13:20:35.418 HelloWorld[541:833827] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5-1

Total memory 1064304640

Free memory 432119808

execPath /private/var/mobile/Containers/Bundle/Application/DF020594-306C-4745-B283-3BA5A10FAD1A/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/DF0,20594-306C-4745-B283-3BA5A10FAD1A/HelloWorld.app/www/jxcore/

userPath []

2016-03-04 13:20:35.864 HelloWorld[541:833827] Native method ScreenInfo not found.
2016-03-04 13:20:35.865 HelloWorld[541:833827] Native method ScreenBrightness not found.
Dum,my Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5247  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
