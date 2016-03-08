#### Test 61703351926082e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F2AFD576-32E9-4AE5-89EC-A9685D21B1F0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F2AFD576-32E9-4AE5-89EC-A9685D21B1F0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/227B04D9-93C5-40EB-B549-CC4E8F6B359B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49211"
,(lldb)     command script import "/tmp/F2AFD576-32E9-4AE5-89EC-A9685D21B1F0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 08:56:38.186 HelloWorld[870:1280691] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D994E8DB-D9BA-4AE9-9E8B-1D8646F46BFB/Library/Cookies/Cookies.binarycookies
,2016-03-08 08:56:38.614 HelloWorld[870:1280691] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 08:56:38.615 HelloWorld[870:1280691] Multi-tasking -> Device: YES, App: YES
,2016-03-08 08:56:38.619 HelloWorld[870:1280691] Unlimited access to network resources
,2016-03-08 08:56:38.627 HelloWorld[870:1280691] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 08:56:47.192 HelloWorld[870:1280691] Resetting plugins due to page load.
,2016-03-08 08:56:50.089 HelloWorld[870:1280691] Finished load of: file:///var/mobile/Containers/Bundle/Application/227B04D9-93C5-40EB-B549-CC4E8F6B359B/HelloWorld.app/www/index.html
,2016-03-08 08:56:50.165 HelloWorld[870:1280691] JXcore Cordova plugin initializing
,2016-03-08 08:56:50.167 HelloWorld[870:1280866] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

,Total memory 1037041664

Free memory 1402716160

execPath /private/var/mobile/Containers/Bundle/Application/227B04D9-93C5-40EB-B549-CC4E8F6B359B/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/227B04D9-93C5-40EB-B549-CC4E8F6B359B/HelloWorld.app/www/jxcore/

userPath []

2016-03-08 08:56:50.360 HelloWorld[870:1280866] Native method ScreenInfo not found.
2016-03-08 08:56:50.360 HelloWorld[870:1280866] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5112  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
