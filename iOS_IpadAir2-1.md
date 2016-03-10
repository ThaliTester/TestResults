#### Test 623445121bdd37c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F5431AC7-5A60-4680-970E-F703EAA7CA77/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F5431AC7-5A60-4680-970E-F703EAA7CA77/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F6C1D798-B334-4DE3-A31A-5F1494397163/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50306"
,(lldb)     command script import "/tmp/F5431AC7-5A60-4680-970E-F703EAA7CA77/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 07:23:30.132 HelloWorld[1030:1600702] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7DD89BBD-6FB6-459A-A009-07187F59F527/Library/Cookies/Cookies.binarycookies
,2016-03-10 07:23:30.460 HelloWorld[1030:1600702] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-10 07:23:30.461 HelloWorld[1030:1600702] Multi-tasking -> Device: YES, App: YES
,2016-03-10 07:23:30.469 HelloWorld[1030:1600702] Unlimited access to network resources
,2016-03-10 07:23:30.476 HelloWorld[1030:1600702] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 07:23:38.670 HelloWorld[1030:1600702] Resetting plugins due to page load.
,2016-03-10 07:23:42.015 HelloWorld[1030:1600702] Finished load of: file:///var/mobile/Containers/Bundle/Application/F6C1D798-B334-4DE3-A31A-5F1494397163/HelloWorld.app/www/index.html
,2016-03-10 07:23:42.123 HelloWorld[1030:1600702] JXcore Cordova plugin initializing
,2016-03-10 07:23:42.124 HelloWorld[1030:1600905] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 874774528
,execPath /private/var/mobile/Containers/Bundle/Application/F6C1D798-B334-4DE3-A31A-5F1494397163/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/F6C1D798-B334-4DE3-A31A-5F1494397163/HelloWorld.app/www/jxcore/
,userPath []
,2016-03-10 07:23:42.336 HelloWorld[1030:1600905] Native method ScreenInfo not found.
2016-03-10 07:23:42.336 HelloWorld[1030:1600905] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5119  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
