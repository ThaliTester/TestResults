#### Test 61703351ed386f4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351ed386f4/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/71231D21-4277-43AC-9ACF-46C0402251A2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/71231D21-4277-43AC-9ACF-46C0402251A2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351ed386f4/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351ed386f4/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F07E0C7C-3693-4272-85CD-DA9D5846EE9E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50411"
,(lldb)     command script import "/tmp/71231D21-4277-43AC-9ACF-46C0402251A2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 08:52:34.668 HelloWorld[1009:1570219] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BA2E670E-8F47-447C-A491-380D322C5750/Library/Cookies/Cookies.binarycookies
,2016-03-10 08:52:35.070 HelloWorld[1009:1570219] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-10 08:52:35.072 HelloWorld[1009:1570219] Multi-tasking -> Device: YES, App: YES
,2016-03-10 08:52:35.075 HelloWorld[1009:1570219] Unlimited access to network resources
,2016-03-10 08:52:35.083 HelloWorld[1009:1570219] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 08:52:43.267 HelloWorld[1009:1570219] Resetting plugins due to page load.
,2016-03-10 08:52:46.284 HelloWorld[1009:1570219] Finished load of: file:///var/mobile/Containers/Bundle/Application/F07E0C7C-3693-4272-85CD-DA9D5846EE9E/HelloWorld.app/www/index.html
,2016-03-10 08:52:46.356 HelloWorld[1009:1570219] JXcore Cordova plugin initializing
2016-03-10 08:52:46.361 HelloWorld[1009:1570438] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

Free memory 1371832320

execPath /private/var/mobile/Containers/Bundle/Application/F07E0C7C-3693-4272-85CD-DA9D5846EE9E/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/F07E0C7C-3693-4272-85CD-DA9D5846EE9E/HelloWorld.app/www/jxcore/

userPath []

2016-03-10 08:52:46.551 HelloWorld[1009:1570438] Native method ScreenInfo not found.
2016-03-10 08:52:46.551 HelloWorld[1009:1570438] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5114  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
