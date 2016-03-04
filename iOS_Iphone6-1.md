#### Test 61703351a2a4153_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/944B2465-A8AF-4916-9065-6BB4D371852D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/944B2465-A8AF-4916-9065-6BB4D371852D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/742E9709-F860-47E6-B773-BA700F291C53/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49727"
,(lldb)     command script import "/tmp/944B2465-A8AF-4916-9065-6BB4D371852D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 13:20:18.217 HelloWorld[632:740872] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5159A7D-270B-4AC2-871A-1A1C3CEA04CD/Library/Cookies/Cookies.binarycookies
,2016-03-04 13:20:18.585 HelloWorld[632:740872] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-04 13:20:18.586 HelloWorld[632:740872] Multi-tasking -> Device: YES, App: YES
,2016-03-04 13:20:18.589 HelloWorld[632:740872] Unlimited access to network resources
,2016-03-04 13:20:18.599 HelloWorld[632:740872] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 13:20:27.426 HelloWorld[632:740872] Resetting plugins due to page load.
,2016-03-04 13:20:30.430 HelloWorld[632:740872] Finished load of: file:///var/mobile/Containers/Bundle/Application/742E9709-F860-47E6-B773-BA700F291C53/HelloWorld.app/www/index.html
,2016-03-04 13:20:30.509 HelloWorld[632:740872] JXcore Cordova plugin initializing
2016-03-04 13:20:30.510 HelloWorld[632:741067] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

,Free memory 1688371200

execPath /private/var/mobile/Containers/Bundle/Application/742E9709-F860-47E6-B773-BA700F291C53/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/742E9709-F860-47E6-B773-BA700F291C53/HelloWorld.app,/www/jxcore/

userPath []

2016-03-04 13:20:30.703 HelloWorld[632:741067] Native method ScreenInfo not found.
2016-03-04 13:20:30.703 HelloWorld[632:741067] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5112  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
