#### Test 6170335106d974e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/13B01BFA-D4E4-4444-8249-D3C6A472BFEE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/13B01BFA-D4E4-4444-8249-D3C6A472BFEE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335106d974e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8AA08224-C80B-49BC-8610-4B344D017DA3/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50985"
,(lldb)     command script import "/tmp/13B01BFA-D4E4-4444-8249-D3C6A472BFEE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 14:39:50.529 HelloWorld[657:1293511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F191DDF2-E095-4278-B65C-BC3AFC1BBD71/Library/Cookies/Cookies.binarycookies
,2016-03-07 14:39:50.663 HelloWorld[657:1293511] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-07 14:39:50.665 HelloWorld[657:1293511] Multi-tasking -> Device: YES, App: YES
,2016-03-07 14:39:50.672 HelloWorld[657:1293511] Unlimited access to network resources
,2016-03-07 14:39:50.686 HelloWorld[657:1293511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 14:40:00.798 HelloWorld[657:1293511] Resetting plugins due to page load.
,2016-03-07 14:40:04.398 HelloWorld[657:1293511] Finished load of: file:///var/mobile/Containers/Bundle/Application/8AA08224-C80B-49BC-8610-4B344D017DA3/HelloWorld.app/www/index.html
,2016-03-07 14:40:04.484 HelloWorld[657:1293511] JXcore Cordova plugin initializing
,2016-03-07 14:40:04.486 HelloWorld[657:1293800] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone5-1

,Total memory 1064304640

Free memory 454639616

execPath /private/var/mobile/Containers/Bundle/Application/8AA08224-C80B-49BC-8610-4B344D017DA3/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/8AA08224-C80B-49BC-8610-4,B344D017DA3/HelloWorld.app/www/jxcore/

,userPath []

2016-03-07 14:40:04.940 HelloWorld[657:1293800] Native method ScreenInfo not found.
2016-03-07 14:40:04.940 HelloWorld[657:1293800] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5255  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
