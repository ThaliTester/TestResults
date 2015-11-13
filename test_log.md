#### Test 50388019995d1da Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019995d1da/serverApp/index.js',
  '{"devices":{"ios":5,"cancel":1}}' ]

JSON { devices: { ios: 5, cancel: 1 } }



ios : false
```


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019995d1da/serverApp/index.js',
  '{"devices":{"ios":5,"cancel":1}}' ]

JSON { devices: { ios: 5, cancel: 1 } }


```

###iOS Logs

```
IpadAir1-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J71AP 'IpadAir1-1' (72077319a5ba6195ddfb95f3a55e9fa0d62da640) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C14DC334-D89D-4251-B7A9-C2FAC0C2F296/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'
,Executing commands in '/tmp/C14DC334-D89D-4251-B7A9-C2FAC0C2F296/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0BB0E0D3-17BE-4006-A1C9-14AE7C010A29/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49284"
,(lldb)     command script import "/tmp/C14DC334-D89D-4251-B7A9-C2FAC0C2F296/fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.py"
,(lldb)     command script add -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:57:06.276 HelloWorld[203:5130] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D998BC4-9E6B-42D5-96A8-F95A14C104DA/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:57:06.763 HelloWorld[203:5130] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:57:06.764 HelloWorld[203:5130] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:57:06.773 HelloWorld[203:5130] Unlimited access to network resources
,2015-11-14 00:57:06.782 HelloWorld[203:5130] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:57:10.133 HelloWorld[203:5130] Resetting plugins due to page load.
,2015-11-14 00:57:10.482 HelloWorld[203:5130] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/0BB0E0D3-17BE-4006-A1C9-14AE7C010A29/HelloWorld.app/www/index.html
,2015-11-14 00:57:10.610 HelloWorld[203:5130] JXcore Cordova plugin initializing
,2015-11-14 00:57:10.612 HelloWorld[203:5244] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir1-1
,Total memory 1022865408
Free memory 237740032
execPath /private/var/mobile/Containers/Bundle/Application/0BB0E0D3-17BE-4006-A1C9-14AE7C010A29/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/0BB0E0D3-17BE-4006-A1C9-14AE7C010A29/HelloWorld.app/www/jxcore/
,userPath []
2015-11-14 00:57:10.871 HelloWorld[203:5244] Native method ScreenInfo not found.
2015-11-14 00:57:10.871 HelloWorld[203:5244] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5112  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F21B8D6B-85ED-4AB6-AF6A-E719C3C64764/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F21B8D6B-85ED-4AB6-AF6A-E719C3C64764/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE2A514E-19BC-4492-8067-F21826E6E159/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49285"
,(lldb)     command script import "/tmp/F21B8D6B-85ED-4AB6-AF6A-E719C3C64764/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:57:07.236 HelloWorld[199:6534] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/53EF8D0D-C04E-44F2-B43B-19179B35C745/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:57:07.697 HelloWorld[199:6534] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:57:07.698 HelloWorld[199:6534] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:57:07.705 HelloWorld[199:6534] Unlimited access to network resources
,2015-11-14 00:57:07.711 HelloWorld[199:6534] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:57:12.020 HelloWorld[199:6534] Resetting plugins due to page load.
,2015-11-14 00:57:12.492 HelloWorld[199:6534] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/EE2A514E-19BC-4492-8067-F21826E6E159/HelloWorld.app/www/index.html
,2015-11-14 00:57:12.593 HelloWorld[199:6534] JXcore Cordova plugin initializing
2015-11-14 00:57:12.595 HelloWorld[199:6649] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
Free memory 326483968
,execPath /private/var/mobile/Containers/Bundle/Application/EE2A514E-19BC-4492-8067-F21826E6E159/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/EE2A514E-19BC-4492-8067-F21826E6E159/HelloWorld.app/www/jxcore/
,userPath []
2015-11-14 00:57:12.829 HelloWorld[199:6649] Native method ScreenInfo not found.
2015-11-14 00:57:12.829 HelloWorld[199:6649] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5111  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/60D05A61-26F3-4CB6-AA29-02D7BB9A9ACA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/60D05A61-26F3-4CB6-AA29-02D7BB9A9ACA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2A6EB9F0-986D-4CA8-A751-C20401C78133/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49282"
,(lldb)     command script import "/tmp/60D05A61-26F3-4CB6-AA29-02D7BB9A9ACA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:57:07.129 HelloWorld[220:7255] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B47DA09-5605-42D7-9924-D6C236349ECA/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:57:07.549 HelloWorld[220:7255] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:57:07.550 HelloWorld[220:7255] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:57:07.556 HelloWorld[220:7255] Unlimited access to network resources
,2015-11-14 00:57:07.566 HelloWorld[220:7255] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:57:11.496 HelloWorld[220:7255] Resetting plugins due to page load.
,2015-11-14 00:57:11.935 HelloWorld[220:7255] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/2A6EB9F0-986D-4CA8-A751-C20401C78133/HelloWorld.app/www/index.html
,2015-11-14 00:57:12.028 HelloWorld[220:7255] JXcore Cordova plugin initializing
,2015-11-14 00:57:12.029 HelloWorld[220:7390] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
Free memory 252313600
execPath /private/var/mobile/Containers/Bundle/Application/2A6EB9F0-986D-4CA8-A751-C20401C78133/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/2A6EB9F0-986D-4CA8-A751,-C20401C78133/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 00:57:12.230 HelloWorld[220:7390] Native method ScreenInfo not found.
2015-11-14 00:57:12.231 HelloWorld[220:7390] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5111  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F897C82A-CA04-4614-8A5E-2D9391EAE43B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F897C82A-CA04-4614-8A5E-2D9391EAE43B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/80B79C49-9837-480E-93A4-BED9D04A47F3/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49288"
,(lldb)     command script import "/tmp/F897C82A-CA04-4614-8A5E-2D9391EAE43B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:57:55.828 HelloWorld[154:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:57:55.832 HelloWorld[154:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:57:55.838 HelloWorld[154:60b] Unlimited access to network resources
,2015-11-14 00:57:55.848 HelloWorld[154:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:58:07.129 HelloWorld[154:60b] Resetting plugins due to page load.
,2015-11-14 00:58:08.048 HelloWorld[154:60b] Finished load of: file:///var/mobile/Applications/80B79C49-9837-480E-93A4-BED9D04A47F3/HelloWorld.app/www/index.html
,2015-11-14 00:58:08.130 HelloWorld[154:60b] JXcore Cordova plugin initializing
,2015-11-14 00:58:08.131 HelloWorld[154:6807] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 668430336
execPath /private/var/mobile/Applications/80B79C49-9837-480E-93A4-BED9D04A47F3/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/80B79C49-9837-480E-93A4-BED9D04A47F3/HelloWorld.app/www/jxcore/
userPath []
,2015-11-14 00:58:08.603 HelloWorld[154:6807] Native method ScreenInfo not found.
,2015-11-14 00:58:08.606 HelloWorld[154:6807] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5255  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D4F3B2D4-93A8-4DB6-AC67-A8B18FF75B3E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D4F3B2D4-93A8-4DB6-AC67-A8B18FF75B3E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019995d1da/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08C716C4-90CE-44D8-98CB-B8792C70C01F/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49280"
,(lldb)     command script import "/tmp/D4F3B2D4-93A8-4DB6-AC67-A8B18FF75B3E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 00:57:03.906 HelloWorld[229:9514] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A269CD22-A3E0-45A0-9BE8-DD68F53A0601/Library/Cookies/Cookies.binarycookies
,2015-11-14 00:57:04.323 HelloWorld[229:9514] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 00:57:04.324 HelloWorld[229:9514] Multi-tasking -> Device: YES, App: YES
,2015-11-14 00:57:04.328 HelloWorld[229:9514] Unlimited access to network resources
,2015-11-14 00:57:04.334 HelloWorld[229:9514] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 00:57:08.741 HelloWorld[229:9514] Resetting plugins due to page load.
,2015-11-14 00:57:10.249 HelloWorld[229:9514] Finished load of: file:///var/mobile/Containers/Bundle/Application/08C716C4-90CE-44D8-98CB-B8792C70C01F/HelloWorld.app/www/index.html
,2015-11-14 00:57:10.306 HelloWorld[229:9514] JXcore Cordova plugin initializing
,2015-11-14 00:57:10.306 HelloWorld[229:9673] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 797540352
execPath /private/var/mobile/Containers/Bundle/Application/08C716C4-90CE-44D8-98CB-B8792C70C01F/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/08C716C4-90CE-44D8-98CB-B8792C70C01F/HelloWorld.app/www/jxcore/
,userPath []
2015-11-14 00:57:10.489 HelloWorld[229:9673] Native method ScreenInfo not found.
2015-11-14 00:57:10.489 HelloWorld[229:9673] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5096  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

