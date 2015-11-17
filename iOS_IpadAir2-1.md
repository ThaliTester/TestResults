#### Test 503880196ac79ce_iOS_IpadAir2-1 Logs


```[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/87A85D2A-31D6-4F8E-B8A3-4EFE55284BF6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/87A85D2A-31D6-4F8E-B8A3-4EFE55284BF6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/18AA47BC-853A-476D-A4B3-50E50114C4F1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53689"
,(lldb)     command script import "/tmp/87A85D2A-31D6-4F8E-B8A3-4EFE55284BF6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 18:28:39.127 HelloWorld[599:543937] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B300655F-F39D-4848-BFF2-1B4D1C3EF08A/Library/Cookies/Cookies.binarycookies
,2015-11-17 18:28:39.399 HelloWorld[599:543937] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 18:28:39.400 HelloWorld[599:543937] Multi-tasking -> Device: YES, App: YES
,2015-11-17 18:28:39.402 HelloWorld[599:543937] Unlimited access to network resources
,2015-11-17 18:28:39.407 HelloWorld[599:543937] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 18:28:43.419 HelloWorld[599:543937] Resetting plugins due to page load.
,2015-11-17 18:28:44.818 HelloWorld[599:543937] Finished load of: file:///var/mobile/Containers/Bundle/Application/18AA47BC-853A-476D-A4B3-50E50114C4F1/HelloWorld.app/www/index.html
,2015-11-17 18:28:44.863 HelloWorld[599:543937] JXcore Cordova plugin initializing
,2015-11-17 18:28:44.865 HelloWorld[599:544116] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 907706368
execPath /private/var/mobile/Containers/Bundle/Application/18AA47BC-853A-476D-A4B3-50E50114C4F1/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/18AA47BC-853A-476D-A4B3-50E5011,4C4F1/HelloWorld.app/www/jxcore/
,userPath []
2015-11-17 18:28:45.049 HelloWorld[599:544116] Native method ScreenInfo not found.
2015-11-17 18:28:45.050 HelloWorld[599:544116] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5097  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
```
