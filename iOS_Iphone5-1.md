#### Test 50242285576d0b0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E0575050-366A-46F4-BADE-B151896E07FA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/E0575050-366A-46F4-BADE-B151896E07FA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/005E74CC-AD49-465E-8BDA-0D980C9C4B73/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49223"
,(lldb)     command script import "/tmp/E0575050-366A-46F4-BADE-B151896E07FA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-06 15:07:49.279 HelloWorld[296:19977] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/00A7C024-C5B8-4FDA-899F-D3F846A74381/Library/Cookies/Cookies.binarycookies
,2015-12-06 15:07:49.770 HelloWorld[296:19977] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-06 15:07:49.771 HelloWorld[296:19977] Multi-tasking -> Device: YES, App: YES
,2015-12-06 15:07:49.778 HelloWorld[296:19977] Unlimited access to network resources
,2015-12-06 15:07:49.790 HelloWorld[296:19977] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-06 15:07:59.639 HelloWorld[296:19977] Resetting plugins due to page load.
,2015-12-06 15:08:03.341 HelloWorld[296:19977] Finished load of: file:///var/mobile/Containers/Bundle/Application/005E74CC-AD49-465E-8BDA-0D980C9C4B73/HelloWorld.app/www/index.html
,2015-12-06 15:08:03.430 HelloWorld[296:19977] JXcore Cordova plugin initializing
,2015-12-06 15:08:03.432 HelloWorld[296:20138] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1064304640
Free memory 305672192
execPath /private/var/mobile/Containers/Bundle/Application/005E74CC-AD49-465E-8BDA-0D980C9C4B73/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/005E74CC-AD,49-465E-8BDA-0D980C9C4B73/HelloWorld.app/www/jxcore/
userPath []
2015-12-06 15:08:03.911 HelloWorld[296:20138] Native method ScreenInfo not found.
2015-12-06 15:08:03.911 HelloWorld[296:20138] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5246  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
