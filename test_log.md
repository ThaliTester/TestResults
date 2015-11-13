#### Test 50388019e7dad2f Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019e7dad2f/serverApp/index.js',
  '{"devices":{"ios":3,"cancel":1}}' ]

JSON { devices: { ios: 3, cancel: 1 } }



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FF6A930E-E496-4019-B452-92977127549D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FF6A930E-E496-4019-B452-92977127549D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A3E0A41D-F3F9-4B0E-979A-E764C0E1251E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60052"
,(lldb)     command script import "/tmp/FF6A930E-E496-4019-B452-92977127549D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,Skipping (17df3859480c382d3b761fa2643dde395ced1bd8ss).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8267BB95-B58F-4DA8-B122-8151B08AE787/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8267BB95-B58F-4DA8-B122-8151B08AE787/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/20540D8B-CB3C-49D7-BFB9-6B0A6068A58A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60053"
,(lldb)     command script import "/tmp/8267BB95-B58F-4DA8-B122-8151B08AE787/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:02:19.880 HelloWorld[3351:3688018] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05CD6AC5-827D-4A6A-8BBA-EB974D8A6921/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:02:20.187 HelloWorld[3351:3688018] Apache Cordova native platform version 3.9.2 is starting.
2015-11-14 00:02:20.188 HelloWorld[3351:3688018] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:02:20.190 HelloWorld[3351:3688018] Unlimited access to network resources
,2015-11-14 00:02:20.194 HelloWorld[3351:3688018] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:02:22.477 HelloWorld[3351:3688018] Resetting plugins due to page load.
,2015-11-14 00:02:22.657 HelloWorld[3351:3688018] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/20540D8B-CB3C-49D7-BFB9-6B0A6068A58A/HelloWorld.app/www/index.html
,2015-11-14 00:02:22.703 HelloWorld[3351:3688018] JXcore Cordova plugin initializing
2015-11-14 00:02:22.705 HelloWorld[3351:3688096] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
,Free memory 96362496
,execPath /private/var/mobile/Containers/Bundle/Application/20540D8B-CB3C-49D7-BFB9-6B0A6068A58A/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/20540D8B-CB3C-49D7-BFB9-6B0A6068A58A/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-14 00:02:22.899 HelloWorld[3351:3688096] Native method ScreenInfo not found.
,2015-11-14 00:02:22.900 HelloWorld[3351:3688096] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5098  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DDD167A6-9466-40AC-A864-FC1EA885E922/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DDD167A6-9466-40AC-A864-FC1EA885E922/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019e7dad2f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CEACC50A-8F6B-4BFA-B524-14F7FCC5E789/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60056"
,(lldb)     command script import "/tmp/DDD167A6-9466-40AC-A864-FC1EA885E922/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:02:49.614 HelloWorld[2200:4872930] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F64D4234-1519-444A-9349-287FB274C972/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:02:49.893 HelloWorld[2200:4872930] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:02:49.893 HelloWorld[2200:4872930] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:02:49.895 HelloWorld[2200:4872930] Unlimited access to network resources
,2015-11-14 00:02:49.900 HelloWorld[2200:4872930] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file




server: 
iOS application timeout
,Unexpected exit on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 app:Iphone5s-1 code:null,Unexpected exit on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe app:IpadAir2-1 code:null


```



#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019e7dad2f/serverApp/index.js',
  '{"devices":{"ios":3,"cancel":1}}' ]

JSON { devices: { ios: 3, cancel: 1 } }


```

