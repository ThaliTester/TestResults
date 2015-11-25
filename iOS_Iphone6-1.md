#### Test 503880196dc97cd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196dc97cd/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C7D64FB7-AA48-4340-ACF2-AA55FF54CFFA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C7D64FB7-AA48-4340-ACF2-AA55FF54CFFA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196dc97cd/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196dc97cd/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8986A2A9-959F-4DDF-9D93-1F22319AE118/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55726"
,(lldb)     command script import "/tmp/C7D64FB7-AA48-4340-ACF2-AA55FF54CFFA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 15:09:38.940 HelloWorld[1691:1310340] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AC1AE69D-CCD7-4F27-BD7D-9E2884B63B95/Library/Cookies/Cookies.binarycookies
,2015-11-25 15:09:39.314 HelloWorld[1691:1310340] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 15:09:39.315 HelloWorld[1691:1310340] Multi-tasking -> Device: YES, App: YES
,2015-11-25 15:09:39.324 HelloWorld[1691:1310340] Unlimited access to network resources
,2015-11-25 15:09:39.328 HelloWorld[1691:1310340] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 15:09:42.887 HelloWorld[1691:1310340] Resetting plugins due to page load.
,2015-11-25 15:09:43.238 HelloWorld[1691:1310340] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8986A2A9-959F-4DDF-9D93-1F22319AE118/HelloWorld.app/www/index.html
,2015-11-25 15:09:43.271 HelloWorld[1691:1310340] JXcore Cordova plugin initializing
2015-11-25 15:09:43.272 HelloWorld[1691:1310463] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 97542144
execPath /private/var/mobile/Containers/Bundle/Application/8986A2A9-959F-4DDF-9D93-1F22319AE118/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/8986,A2A9-959F-4DDF-9D93-1F22319AE118/HelloWorld.app/www/jxcore/
,userPath []
2015-11-25 15:09:43.481 HelloWorld[1691:1310463] Native method ScreenInfo not found.
2015-11-25 15:09:43.482 HelloWorld[1691:1310463] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5109  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
