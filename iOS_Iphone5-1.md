#### Test 61703351926082e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B85A4AA5-2DF7-4E9C-AB46-14F3B311802F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B85A4AA5-2DF7-4E9C-AB46-14F3B311802F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9D2C5A67-235D-4B52-BA7D-619B6BF72DE5/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49208"
,(lldb)     command script import "/tmp/B85A4AA5-2DF7-4E9C-AB46-14F3B311802F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 08:56:42.296 HelloWorld[702:1411938] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/95F5714B-F9CA-4FA6-80AC-5938468EBD1D/Library/Cookies/Cookies.binarycookies
,2016-03-08 08:56:42.430 HelloWorld[702:1411938] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 08:56:42.432 HelloWorld[702:1411938] Multi-tasking -> Device: YES, App: YES
,2016-03-08 08:56:42.438 HelloWorld[702:1411938] Unlimited access to network resources
,2016-03-08 08:56:42.451 HelloWorld[702:1411938] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 08:56:51.632 HelloWorld[702:1411938] Resetting plugins due to page load.
,2016-03-08 08:56:55.807 HelloWorld[702:1411938] Finished load of: file:///var/mobile/Containers/Bundle/Application/9D2C5A67-235D-4B52-BA7D-619B6BF72DE5/HelloWorld.app/www/index.html
,2016-03-08 08:56:55.893 HelloWorld[702:1411938] JXcore Cordova plugin initializing
2016-03-08 08:56:55.895 HelloWorld[702:1412111] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5-1

Total memory 1064304640

Free memory 449257472

execPath /private/var/mobile/Containers/Bundle/Application/9D2C5A67-235D-4B52-BA7D-619B6BF72DE5/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/9D2,C5A67-235D-4B52-BA7D-619B6BF72DE5/HelloWorld.app/www/jxcore/

userPath []

2016-03-08 08:56:56.326 HelloWorld[702:1412111] Native method ScreenInfo not found.
2016-03-08 08:56:56.326 HelloWorld[702:1412111] Native method ScreenBrightness not found.
D,ummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5233  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
