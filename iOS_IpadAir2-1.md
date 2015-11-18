#### Test 50388019f4ce509_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AFD41713-1602-45F8-8BFE-D266CCE7DE2F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AFD41713-1602-45F8-8BFE-D266CCE7DE2F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41833AB1-FFE5-47D1-A909-A2C6B557C2DE/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49310"
,(lldb)     command script import "/tmp/AFD41713-1602-45F8-8BFE-D266CCE7DE2F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-18 09:10:37.712 HelloWorld[655:632656] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8E88436E-8F43-4AB9-9D4D-F2B179B419CA/Library/Cookies/Cookies.binarycookies
,2015-11-18 09:10:37.990 HelloWorld[655:632656] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-18 09:10:37.991 HelloWorld[655:632656] Multi-tasking -> Device: YES, App: YES
,2015-11-18 09:10:37.993 HelloWorld[655:632656] Unlimited access to network resources
,2015-11-18 09:10:37.998 HelloWorld[655:632656] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-18 09:10:41.985 HelloWorld[655:632656] Resetting plugins due to page load.
,2015-11-18 09:10:43.381 HelloWorld[655:632656] Finished load of: file:///var/mobile/Containers/Bundle/Application/41833AB1-FFE5-47D1-A909-A2C6B557C2DE/HelloWorld.app/www/index.html
,2015-11-18 09:10:43.434 HelloWorld[655:632656] JXcore Cordova plugin initializing
2015-11-18 09:10:43.435 HelloWorld[655:632819] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 895680512
execPath /private/var/mobile/Containers/Bundle/Application/41833AB1-FFE5-47D1-A909-A2C6B557C2DE/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/41833AB1-FFE5-47D1-A909-A2C6B557C2DE/HelloWorld.app/www/jxcore/
userPath []
2015-11-18 09:10:43.614 HelloWorld[655:632819] Native method ScreenInfo not found.
2015-11-18 09:10:43.614 HelloWorld[655:632819] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5089  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
