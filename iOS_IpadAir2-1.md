#### Test 50242285feafdeb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FC2A68DA-C45A-4B6F-9ECE-9492D4D75609/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FC2A68DA-C45A-4B6F-9ECE-9492D4D75609/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3402ECDD-9EBC-47B4-BC5E-32AF5EF079E7/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52954"
,(lldb)     command script import "/tmp/FC2A68DA-C45A-4B6F-9ECE-9492D4D75609/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 23:46:16.343 HelloWorld[1822:3846968] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/19D9EB9F-5B11-45A8-B6AE-829AC0D0D53A/Library/Cookies/Cookies.binarycookies
,2016-01-11 23:46:16.573 HelloWorld[1822:3846968] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 23:46:16.574 HelloWorld[1822:3846968] Multi-tasking -> Device: YES, App: YES
,2016-01-11 23:46:16.576 HelloWorld[1822:3846968] Unlimited access to network resources
,2016-01-11 23:46:16.580 HelloWorld[1822:3846968] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 23:46:20.879 HelloWorld[1822:3846968] Resetting plugins due to page load.
,2016-01-11 23:46:22.330 HelloWorld[1822:3846968] Finished load of: file:///var/mobile/Containers/Bundle/Application/3402ECDD-9EBC-47B4-BC5E-32AF5EF079E7/HelloWorld.app/www/index.html
,2016-01-11 23:46:22.377 HelloWorld[1822:3846968] JXcore Cordova plugin initializing
,2016-01-11 23:46:22.378 HelloWorld[1822:3847122] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-IpadAir2-1

,Total memory 2084569088

,Free memory 823345152

,execPath /private/var/mobile/Containers/Bundle/Application/3402ECDD-9EBC-47B4-BC5E-32AF5EF079E7/HelloWorld.app/HelloWorld

,process.cwd /var/mobile/Containers/Bundle/Application/3402ECDD-9EBC-47B4-BC5E-32AF5EF079E7/HelloWorld.app/www/jxcore/

,userPath []

,2016-01-11 23:46:22.543 HelloWorld[1822:3847122] Native method ScreenInfo not found.
2016-01-11 23:46:22.544 HelloWorld[1822:3847122] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

****TEST TOOK:  5102  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
