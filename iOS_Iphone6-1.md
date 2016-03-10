#### Test 623445121bdd37c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FE1442A8-2039-47E3-A671-D3D6DECD2B06/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FE1442A8-2039-47E3-A671-D3D6DECD2B06/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BDCA00CC-4236-4C8D-8A01-033C568D5474/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50307"
,(lldb)     command script import "/tmp/FE1442A8-2039-47E3-A671-D3D6DECD2B06/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 07:23:26.260 HelloWorld[998:1560180] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D885A92-82AD-46E7-B725-1677C2DADB79/Library/Cookies/Cookies.binarycookies
,2016-03-10 07:23:26.621 HelloWorld[998:1560180] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-10 07:23:26.622 HelloWorld[998:1560180] Multi-tasking -> Device: YES, App: YES
,2016-03-10 07:23:26.632 HelloWorld[998:1560180] Unlimited access to network resources
,2016-03-10 07:23:26.643 HelloWorld[998:1560180] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 07:23:34.799 HelloWorld[998:1560180] Resetting plugins due to page load.
,2016-03-10 07:23:38.041 HelloWorld[998:1560180] Finished load of: file:///var/mobile/Containers/Bundle/Application/BDCA00CC-4236-4C8D-8A01-033C568D5474/HelloWorld.app/www/index.html
,2016-03-10 07:23:38.118 HelloWorld[998:1560180] JXcore Cordova plugin initializing
,2016-03-10 07:23:38.120 HelloWorld[998:1560381] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1037041664
Free memory 1388658688
execPath /private/var/mobile/Containers/Bundle/Application/BDCA00CC-4236-4C8D-8A01-033C568D5474/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/BDCA00CC-4,236-4C8D-8A01-033C568D5474/HelloWorld.app/www/jxcore/
userPath []
2016-03-10 07:23:38.332 HelloWorld[998:1560381] Native method ScreenInfo not found.
2016-03-10 07:23:38.332 HelloWorld[998:1560381] Native method ScreenBrightness not found.
Dummy Error ,Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5115  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
