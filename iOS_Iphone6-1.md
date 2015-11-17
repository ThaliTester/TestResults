#### Test 50388019b27d54e_iOS_Iphone6-1 Logs


```[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019b27d54e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/63AE0524-24CC-4829-A2F0-A560B0A3799C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/63AE0524-24CC-4829-A2F0-A560B0A3799C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019b27d54e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019b27d54e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25B870E7-5AE3-405A-A70A-C010CFEA2500/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53511"
,(lldb)     command script import "/tmp/63AE0524-24CC-4829-A2F0-A560B0A3799C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 18:18:59.406 HelloWorld[698:421275] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/023B09DB-1A19-44AF-987E-E442562FA480/Library/Cookies/Cookies.binarycookies
,2015-11-17 18:18:59.778 HelloWorld[698:421275] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 18:18:59.779 HelloWorld[698:421275] Multi-tasking -> Device: YES, App: YES
,2015-11-17 18:18:59.781 HelloWorld[698:421275] Unlimited access to network resources
,2015-11-17 18:18:59.786 HelloWorld[698:421275] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 18:19:03.404 HelloWorld[698:421275] Resetting plugins due to page load.
,2015-11-17 18:19:03.742 HelloWorld[698:421275] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/25B870E7-5AE3-405A-A70A-C010CFEA2500/HelloWorld.app/www/index.html
,2015-11-17 18:19:03.775 HelloWorld[698:421275] JXcore Cordova plugin initializing
,2015-11-17 18:19:03.777 HelloWorld[698:421409] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
,Free memory 122667008
,execPath /private/var/mobile/Containers/Bundle/Application/25B870E7-5AE3-405A-A70A-C010CFEA2500/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/25B870E7-5AE3-405A-A70A-C010CFEA2500/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-17 18:19:03.977 HelloWorld[698:421409] Native method ScreenInfo not found.
,2015-11-17 18:19:03.978 HelloWorld[698:421409] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
```
