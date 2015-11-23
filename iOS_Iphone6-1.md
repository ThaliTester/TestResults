#### Test 503880196b4ec73_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C7A6AC9B-5E7C-4470-ABFD-C1217E6A2709/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C7A6AC9B-5E7C-4470-ABFD-C1217E6A2709/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196b4ec73/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B5CFB2AE-CAF7-45CD-950F-228BBC6085EA/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53863"
,(lldb)     command script import "/tmp/C7A6AC9B-5E7C-4470-ABFD-C1217E6A2709/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 20:19:06.476 HelloWorld[1454:1104488] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B0CD5A7-B1EF-4A78-BE73-2D504D70258B/Library/Cookies/Cookies.binarycookies
,2015-11-23 20:19:06.853 HelloWorld[1454:1104488] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 20:19:06.854 HelloWorld[1454:1104488] Multi-tasking -> Device: YES, App: YES
,2015-11-23 20:19:06.857 HelloWorld[1454:1104488] Unlimited access to network resources
,2015-11-23 20:19:06.861 HelloWorld[1454:1104488] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 20:19:10.367 HelloWorld[1454:1104488] Resetting plugins due to page load.
,2015-11-23 20:19:10.717 HelloWorld[1454:1104488] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/B5CFB2AE-CAF7-45CD-950F-228BBC6085EA/HelloWorld.app/www/index.html
,2015-11-23 20:19:10.750 HelloWorld[1454:1104488] JXcore Cordova plugin initializing
2015-11-23 20:19:10.751 HelloWorld[1454:1104613] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
Free memory 140034048
execPath /private/var/mobile/Containers/Bundle/Application/B5CFB2AE-CAF7-45CD-950F-228BBC6085EA/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/B5CFB2AE-CAF7-45CD-950F,-228BBC6085EA/HelloWorld.app/www/jxcore/
userPath []
2015-11-23 20:19:10.953 HelloWorld[1454:1104613] Native method ScreenInfo not found.
2015-11-23 20:19:10.954 HelloWorld[1454:1104613] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5110  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
