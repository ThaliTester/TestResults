#### Test 503880196df3bb6 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":23,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_503880196df3bb6/serverApp/index.js',
  '{"devices":{"ios":5,"android":23}}' ]

JSON { devices: { ios: 5, android: 23 } }



android : false
```


###iOS Logs

```
IpadAir1-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J71AP 'IpadAir1-1' (72077319a5ba6195ddfb95f3a55e9fa0d62da640) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E9D13A05-7A4A-4BF7-B399-737E74382364/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'
,Executing commands in '/tmp/E9D13A05-7A4A-4BF7-B399-737E74382364/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/600D46C5-B49A-4C8E-B5EF-08C220DD947B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49663"
,(lldb)     command script import "/tmp/E9D13A05-7A4A-4BF7-B399-737E74382364/fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.py"
,(lldb)     command script add -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 02:31:56.033 HelloWorld[233:15035] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7E89B4CA-78FD-4FEF-A9E2-A2D330CF3F3D/Library/Cookies/Cookies.binarycookies
,2015-11-14 02:31:56.407 HelloWorld[233:15035] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 02:31:56.408 HelloWorld[233:15035] Multi-tasking -> Device: YES, App: YES
,2015-11-14 02:31:56.411 HelloWorld[233:15035] Unlimited access to network resources
,2015-11-14 02:31:56.415 HelloWorld[233:15035] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 02:31:59.702 HelloWorld[233:15035] Resetting plugins due to page load.
,2015-11-14 02:32:00.027 HelloWorld[233:15035] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/600D46C5-B49A-4C8E-B5EF-08C220DD947B/HelloWorld.app/www/index.html
,2015-11-14 02:32:00.111 HelloWorld[233:15035] JXcore Cordova plugin initializing
2015-11-14 02:32:00.112 HelloWorld[233:15136] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir1-1
,Total memory 1022865408
Free memory 228179968
execPath /private/var/mobile/Containers/Bundle/Application/600D46C5-B49A-4C8E-B5EF-08C220DD947B/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/600D46C5-B49A-4C8E-B5EF,-08C220DD947B/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 02:32:00.363 HelloWorld[233:15136] Native method ScreenInfo not found.
2015-11-14 02:32:00.364 HelloWorld[233:15136] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/48CEA0EC-7FD1-48DB-8D7A-C719100935D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/48CEA0EC-7FD1-48DB-8D7A-C719100935D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F4DF563C-D814-4922-BF28-1BFE61E8A50B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49669"
,(lldb)     command script import "/tmp/48CEA0EC-7FD1-48DB-8D7A-C719100935D0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 02:31:57.416 HelloWorld[237:16563] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1B4E971-59D4-4B0B-8891-84421B4AD574/Library/Cookies/Cookies.binarycookies
,2015-11-14 02:31:57.807 HelloWorld[237:16563] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 02:31:57.808 HelloWorld[237:16563] Multi-tasking -> Device: YES, App: YES
,2015-11-14 02:31:57.812 HelloWorld[237:16563] Unlimited access to network resources
,2015-11-14 02:31:57.820 HelloWorld[237:16563] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 02:32:00.945 HelloWorld[237:16563] Resetting plugins due to page load.
,2015-11-14 02:32:01.206 HelloWorld[237:16563] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F4DF563C-D814-4922-BF28-1BFE61E8A50B/HelloWorld.app/www/index.html
,2015-11-14 02:32:01.286 HelloWorld[237:16563] JXcore Cordova plugin initializing
2015-11-14 02:32:01.290 HelloWorld[237:16666] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
,Free memory 321232896
,execPath /private/var/mobile/Containers/Bundle/Application/F4DF563C-D814-4922-BF28-1BFE61E8A50B/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/F4DF563C-D814-4922-BF28-1BFE61E8A50B/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-14 02:32:01.597 HelloWorld[237:16666] Native method ScreenInfo not found.
,2015-11-14 02:32:01.600 HelloWorld[237:16666] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5120  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/21F5F69C-0B13-49EE-A417-01652E003FE8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/21F5F69C-0B13-49EE-A417-01652E003FE8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C92554B1-6B50-46D0-861E-A0BE4201AD7C/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49662"
,(lldb)     command script import "/tmp/21F5F69C-0B13-49EE-A417-01652E003FE8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 02:31:57.629 HelloWorld[255:17003] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/97594680-940A-409C-AFF8-75B2D66444C7/Library/Cookies/Cookies.binarycookies
,2015-11-14 02:31:58.023 HelloWorld[255:17003] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 02:31:58.024 HelloWorld[255:17003] Multi-tasking -> Device: YES, App: YES
,2015-11-14 02:31:58.027 HelloWorld[255:17003] Unlimited access to network resources
,2015-11-14 02:31:58.032 HelloWorld[255:17003] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 02:32:01.605 HelloWorld[255:17003] Resetting plugins due to page load.
,2015-11-14 02:32:02.035 HelloWorld[255:17003] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/C92554B1-6B50-46D0-861E-A0BE4201AD7C/HelloWorld.app/www/index.html
,2015-11-14 02:32:02.078 HelloWorld[255:17003] JXcore Cordova plugin initializing
,2015-11-14 02:32:02.080 HelloWorld[255:17130] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 236691456
execPath /private/var/mobile/Containers/Bundle/Application/C92554B1-6B50-46D0-861E-A0BE4201AD7C/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/C92554B1-6B50-46D0-861E-A0BE4201AD7C/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 02:32:02.282 HelloWorld[255:17130] Native method ScreenInfo not found.
2015-11-14 02:32:02.282 HelloWorld[255:17130] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5106  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1AE97B5A-4A82-4AE2-BE61-614B8D3CA3E9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1AE97B5A-4A82-4AE2-BE61-614B8D3CA3E9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/B91CC8CA-A6C6-4930-BD9C-0152FAD0EE5B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49666"
,(lldb)     command script import "/tmp/1AE97B5A-4A82-4AE2-BE61-614B8D3CA3E9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 02:32:45.276 HelloWorld[187:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 02:32:45.281 HelloWorld[187:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-14 02:32:45.288 HelloWorld[187:60b] Unlimited access to network resources
,2015-11-14 02:32:45.295 HelloWorld[187:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 02:32:56.376 HelloWorld[187:60b] Resetting plugins due to page load.
,2015-11-14 02:32:56.736 HelloWorld[187:60b] Finished load of: file:///var/mobile/Applications/B91CC8CA-A6C6-4930-BD9C-0152FAD0EE5B/HelloWorld.app/www/index.html
,2015-11-14 02:32:57.278 HelloWorld[187:60b] JXcore Cordova plugin initializing
,2015-11-14 02:32:57.281 HelloWorld[187:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 662351872
execPath /private/var/mobile/Applications/B91CC8CA-A6C6-4930-BD9C-0152FAD0EE5B/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/B91CC8CA-A6C6-4930-BD9C-0152FAD0EE5B/HelloWorld.app/www/jxcore/
userPath []
,2015-11-14 02:32:57.751 HelloWorld[187:6607] Native method ScreenInfo not found.
,2015-11-14 02:32:57.754 HelloWorld[187:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5261  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B9B9499B-1A47-4DBF-97E8-751072890A7B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B9B9499B-1A47-4DBF-97E8-751072890A7B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196df3bb6/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5D15475E-B94B-4C4D-AB42-941A090EE852/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49660"
,(lldb)     command script import "/tmp/B9B9499B-1A47-4DBF-97E8-751072890A7B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 02:31:54.168 HelloWorld[265:23194] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/059D08F1-0BC6-47E8-B36C-F41E01C15A88/Library/Cookies/Cookies.binarycookies
,2015-11-14 02:31:54.449 HelloWorld[265:23194] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 02:31:54.450 HelloWorld[265:23194] Multi-tasking -> Device: YES, App: YES
,2015-11-14 02:31:54.452 HelloWorld[265:23194] Unlimited access to network resources
,2015-11-14 02:31:54.457 HelloWorld[265:23194] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 02:31:58.580 HelloWorld[265:23194] Resetting plugins due to page load.
,2015-11-14 02:32:00.039 HelloWorld[265:23194] Finished load of: file:///var/mobile/Containers/Bundle/Application/5D15475E-B94B-4C4D-AB42-941A090EE852/HelloWorld.app/www/index.html
,2015-11-14 02:32:00.086 HelloWorld[265:23194] JXcore Cordova plugin initializing
,2015-11-14 02:32:00.088 HelloWorld[265:23379] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 791068672
execPath /private/var/mobile/Containers/Bundle/Application/5D15475E-B94B-4C4D-AB42-941A090EE852/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/5D15475E-B94B-4C4D-AB42-941A090,EE852/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 02:32:00.269 HelloWorld[265:23379] Native method ScreenInfo not found.
2015-11-14 02:32:00.269 HelloWorld[265:23379] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5097  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":23,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_503880196df3bb6/serverApp/index.js',
  '{"devices":{"ios":5,"android":23}}' ]

JSON { devices: { ios: 5, android: 23 } }


```

###Android Logs
####Node name: thali01
Console output:
```
Warning: Phone 30049d9501da2100	offline OFFLINE
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,--------- beginning of main
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5090 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityThread( 5090): Added TimaKeyStore provider
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityThread( 5090): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): mDVFSHelper.acquire()
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5124 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5124): Added TimaKeyStore provider
V/ActivityManager( 1021): Display changed displayId=0
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/ActivityThread( 1476): updateVisibility : ActivityRecord{b486f3f token=android.os.BinderProxy@2a384dc1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
V/ActivityThread( 5124): updateVisibility : ActivityRecord{3f2e878b token=android.os.BinderProxy@122a6505 {com.example.hello/com.example.hello.MainActivity}} show : true
I/ActivityManager( 1021): Displayed Component not be shown by security: +615ms (total +710ms)
W/ActivityManager( 1021): mDVFSHelper.release()
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1021): Killing 3968:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/jxcore-log( 5124): Initializing JXcore engine
W/jxcore-log( 5124): JXcore engine is ready
W/jxcore-log( 5124): Starting JXcore engine
W/jxcore-log( 5124): Platform android
W/jxcore-log( 5124): 
W/jxcore-log( 5124): Process ARCH arm
W/jxcore-log( 5124): 
I/jxcore-log( 5124): JXcore Cordova bridge is ready!
I/jxcore-log( 5124): 
W/jxcore-log( 5124): JXcore engine is started
E/jxcore-log( 5124): >> samsung-SM-A500FU
E/jxcore-log( 5124): 
I/jxcore-log( 5124): Total memory 1983787008
I/jxcore-log( 5124): 
I/jxcore-log( 5124): Free memory 33673216
I/jxcore-log( 5124): 
I/jxcore-log( 5124): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5124): 
I/jxcore-log( 5124): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5124): 
I/jxcore-log( 5124): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5124): 
I/jxcore-log( 5124): Size 720 1280
I/jxcore-log( 5124): 
I/jxcore-log( 5124): Screen Brightness 5
I/jxcore-log( 5124): 
E/jxcore-log( 5124): Dummy Error Log.
E/jxcore-log( 5124): 
I/jxcore-log( 5124): getBuffer is called!!!!
I/jxcore-log( 5124): 
,I/jxcore-log( 5124): ****TEST TOOK:  5043  ms ****
I/jxcore-log( 5124): 
,I/jxcore-log( 5124): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5124): 
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 5124:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{f3f66f9 u0 com.example.hello/.MainActivity t15}
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5201 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5201): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5218 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5218): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5236): Added TimaKeyStore provider
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5254 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5265 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5254): Added TimaKeyStore provider
,I/ActivityManager( 1021): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5278 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityThread( 5265): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 4260:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5278): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 4164:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5265): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5312): Added TimaKeyStore provider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 3637:com.google.android.talk/u0a104 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 1021): Killing 4628:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2966): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2966): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
,I/ActivityManager( 2966): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/ActivityManager( 2966): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2966): Displayed com.example.hello/.MainActivity: +1s716ms
,I/ActivityManager( 2966): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,W/jxcore-log( 6346): Initializing JXcore engine
W/jxcore-log( 6346): JXcore engine is ready
,W/jxcore-log( 6346): Starting JXcore engine
,W/jxcore-log( 6346): Platform android
W/jxcore-log( 6346): 
W/jxcore-log( 6346): Process ARCH arm
W/jxcore-log( 6346): 
,I/jxcore-log( 6346): JXcore Cordova bridge is ready!
I/jxcore-log( 6346): 
W/jxcore-log( 6346): JXcore engine is started
,E/jxcore-log( 6346): >> HUAWEI-ALE-L21
E/jxcore-log( 6346): 
,I/jxcore-log( 6346): Total memory 1949741056
I/jxcore-log( 6346): 
,I/jxcore-log( 6346): Free memory 19415040
I/jxcore-log( 6346): 
I/jxcore-log( 6346): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6346): 
I/jxcore-log( 6346): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6346): 
,I/jxcore-log( 6346): userPath [ 'www' ]
I/jxcore-log( 6346): 
,I/jxcore-log( 6346): Size 720 1184
I/jxcore-log( 6346): 
,I/jxcore-log( 6346): Screen Brightness 242
I/jxcore-log( 6346): 
,E/jxcore-log( 6346): Dummy Error Log.
E/jxcore-log( 6346): 
,I/jxcore-log( 6346): getBuffer is called!!!!
I/jxcore-log( 6346): 
,I/ActivityManager( 2966): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/jxcore-log( 6346): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 6346): 
,I/jxcore-log( 6346): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6346): 
,I/ActivityManager( 2966): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager( 2966): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1278): Start proc 6642:com.google.android.onetimeinitializer/u0a13 for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
I/ActivityManager( 1278): Killing 5782:com.lge.lifetracker/u0a137 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 6671:com.android.providers.calendar/u0a19 for broadcast com.android.providers.calendar/.CalendarReceiver
I/ActivityManager( 1278): Start proc 6697:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.AlarmInitReceiver
I/ActivityManager( 1278): Killing 5837:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 6749:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
I/ActivityManager( 1278): Killing 3846:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22
I/ActivityManager( 1278): Killing 5892:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
I/ActivityManager( 1278): Waited long enough for: ServiceRecord{58fb887 u0 com.lge.iftttmanager/.internal.service.LGIFTTTService}
I/ActivityManager( 1278): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10000000 cmp=com.lge.camera/.app.BoostCameraActivity (has extras)} from uid 10053 on display 0
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{141baa07 #46 A=com.lge.camera.app.BoostCameraActivity U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{141baa07 #46 A=com.lge.camera.app.BoostCameraActivity U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1278): Start proc 6802:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
I/ActivityManager( 1278): Killing 5965:com.lge.lpd/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 6913:com.lge.task/u0a20 for broadcast com.lge.task/.database.TasksReceiver
I/ActivityManager( 1278): Start proc 6940:com.android.managedprovisioning/u0a43 for broadcast com.android.managedprovisioning/.BootReminder
I/ActivityManager( 1278): Start proc 6961:com.lge.appbox.client:AppBoxCommonService/u0a9 for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService
W/ActivityManager( 1278): Unable to start service Intent { act=com.lge.ia.task.incalagent pkg=com.lge.ia.task.incalagent (has extras) } U=0: not found
W/ActivityManager( 1278): Unable to start service Intent { act=com.lge.ia.task.incalagent pkg=com.lge.ia.task.incalagent (has extras) } U=0: not found
I/ActivityManager( 1278): Start proc 6997:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
I/ActivityManager( 1278): Killing 6115:com.android.browser/u0a24 (adj 15): empty #22
I/ActivityManager( 1278): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{2c16a713 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 0
W/ActivityManager( 1278): Unable to start service Intent { act=com.lge.ia.task.smartsetting pkg=com.lge.ia.task.smartsetting (has extras) } U=0: not found
W/ActivityManager( 1278): Unable to start service Intent { act=com.lge.ia.task.smartsetting pkg=com.lge.ia.task.smartsetting (has extras) } U=0: not found
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1278): Start proc 7028:com.lge.lpd/1000 for broadcast com.lge.lpd/.receiver.LPDBootCompletedReceiver
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1278): Killing 6162:com.lge.email/u0a56 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 7065:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1278): Start proc 7085:com.lge.ia.task.process.shared/u0a31 for service com.lge.ia.task.s4urecommender/.S4URecommenderService
,I/ActivityManager( 1278): Killing 6311:com.lge.wifisettings/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7153:com.lge.smartconfig/1000 for broadcast com.lge.smartconfig/.SmartConfigReceiver
,I/ActivityManager( 1278): Killing 6493:com.android.providers.partnerbookmarks/u0a103 (adj 15): empty #22
,W/jxcore-log( 7065): Initializing JXcore engine
W/jxcore-log( 7065): JXcore engine is ready
,W/jxcore-log( 7065): Starting JXcore engine
,D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{2c16a713 #47 A=com.example.hello U=0 sz=1} / mTaskToReturnTo = 1
,I/ActivityManager( 1278): Displayed com.example.hello/.MainActivity: +941ms (total +1s902ms)
,I/ActivityManager( 1278): Start proc 7212:com.lge.voicerecorder/u0a41 for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver
,I/ActivityManager( 1278): Killing 6521:com.lge.eula/u0a105 (adj 15): empty #22
,W/jxcore-log( 7065): Platform android
W/jxcore-log( 7065): 
W/jxcore-log( 7065): Process ARCH arm
W/jxcore-log( 7065): 
,I/jxcore-log( 7065): JXcore Cordova bridge is ready!
I/jxcore-log( 7065): 
W/jxcore-log( 7065): JXcore engine is started
,E/jxcore-log( 7065): >> LGE-LG-H815
E/jxcore-log( 7065): 
,I/jxcore-log( 7065): Total memory 2968948736
I/jxcore-log( 7065): 
,I/jxcore-log( 7065): Free memory 121450496
I/jxcore-log( 7065): 
I/jxcore-log( 7065): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7065): 
I/jxcore-log( 7065): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7065): 
,I/jxcore-log( 7065): userPath [ 'www' ]
I/jxcore-log( 7065): 
,I/jxcore-log( 7065): Size 1440 2392
I/jxcore-log( 7065): 
,I/jxcore-log( 7065): Screen Brightness 255
I/jxcore-log( 7065): 
,E/jxcore-log( 7065): Dummy Error Log.
E/jxcore-log( 7065): 
,I/ActivityManager( 1278): Killing 6239:com.android.contacts/u0a18 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7233:com.google.android.configupdater/u0a64 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager( 1278): Start proc 7265:com.lge.drmservice/u0a68 for broadcast com.lge.drmservice/.DrmBroadcastReceiver
,I/ActivityManager( 1278): Killing 6550:com.android.keychain/1000 (adj 15): empty #22
,I/jxcore-log( 7065): getBuffer is called!!!!
I/jxcore-log( 7065): 
,I/ActivityManager( 1278): Start proc 7285:com.lge.gcuv/1000 for broadcast com.lge.gcuv/.GcuvReceiver
,I/ActivityManager( 1278): Killing 6473:com.lge.hiddenmenu/1000 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10031 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10031 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 7310:com.lge.cloudhub/u0a73 for broadcast com.lge.cloudhub/.service.CloudHubReceiver
,I/ActivityManager( 1278): Killing 6615:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 5912:com.lge.eodengine/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7335:com.lge.drive.activator/u0a65 for broadcast com.lge.drive.activator/com.lge.drive.oem.BootReceiver
,I/ActivityManager( 1278): Killing 6018:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7358:com.lge.gnss.airtest/u0a80 for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver
,I/ActivityManager( 1278): Killing 6642:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 6064:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7383:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.ModemProtocol.L5000LoggingReceiver
,I/ActivityManager( 1278): Start proc 7404:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.LockSettingsReceiver
I/ActivityManager( 1278): Killing 6697:com.lge.clock/u0a16 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 6749:com.lge.bnr/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7426:com.lge.springcleaning/1000 for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver
,I/ActivityManager( 1278): Start proc 7446:com.lge.springcleaning:AppCleanupService/1000 for service com.lge.springcleaning/.service.AppCleanupService
,I/ActivityManager( 1278): Start proc 7466:com.lge.lgfota.permission/1000 for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver
,I/ActivityManager( 1278): Killing 6671:com.android.providers.calendar/u0a19 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 6802:com.lge.myplace/u0a30 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7487:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,I/ActivityManager( 1278): Start proc 7508:com.lge.ia.task.incalagent/u0a8 for broadcast com.lge.ia.task.incalagent/.BootReceiver
,I/ActivityManager( 1278): Killing 6140:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/ActivityManager( 1278): Waited long enough for: ServiceRecord{3f1fdd27 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/ActivityManager( 1278): Start proc 7528:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,I/ActivityManager( 1278): Start proc 7549:com.android.vending/u0a62 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
,I/ActivityManager( 1278): Killing 6913:com.lge.task/u0a20 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 6216:com.lge.lgdmsclient/1000 (adj 15): empty #23
,I/ActivityManager( 1278): Start proc 7592:com.google.android.talk/u0a121 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,I/ActivityManager( 1278): Killing 6940:com.android.managedprovisioning/u0a43 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 6961:com.lge.appbox.client:AppBoxCommonService/u0a9 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 7065): ****TEST TOOK:  5076  ms ****
I/jxcore-log( 7065): 
I/jxcore-log( 7065): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7065): 
,I/ActivityManager( 1278): Start proc 7642:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
,I/ActivityManager( 1278): Killing 6041:com.lge.appbox.client/u0a9 (adj 15): empty #22
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=0: pkg removed
,I/ActivityManager( 1278): Killing 7065:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1278): Force removing ActivityRecord{383f1d50 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
,D/ActivityThread( 7642): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Spurious death for ProcessRecord{2e37ca7e 7065:com.example.hello/u0a360}, curProc for 7065: null
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1278): Start proc 7680:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1278): Waited long enough for: ServiceRecord{5800371 u0 com.lge.splitwindow/.SplitService}
,W/ActivityManager( 1278): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager( 1278): Displayed com.lge.launcher2/.Launcher: +198ms
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1278): Killing 6354:com.android.settings/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 7714:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 7642): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3694e28f that was originally bound here
E/ActivityThread( 7642): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3694e28f that was originally bound here
E/ActivityThread( 7642): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1259)
E/ActivityThread( 7642): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1153)
E/ActivityThread( 7642): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1888)
E/ActivityThread( 7642): 	at android.app.ContextImpl.bindService(ContextImpl.java:1871)
E/ActivityThread( 7642): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 7642): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 7642): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 7642): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 7642): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 7642): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 7642): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 7642): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 7642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 7642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7642): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1278): Unbind failed: could not find connection for android.os.BinderProxy@946ce4d


```

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2933 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +578ms (total +33s832ms)
,W/jxcore-log( 2933): Initializing JXcore engine
W/jxcore-log( 2933): JXcore engine is ready
,W/jxcore-log( 2933): Starting JXcore engine
,W/jxcore-log( 2933): Platform android
W/jxcore-log( 2933): 
,W/jxcore-log( 2933): Process ARCH arm
W/jxcore-log( 2933): 
,I/jxcore-log( 2933): JXcore Cordova bridge is ready!
I/jxcore-log( 2933): 
,W/jxcore-log( 2933): JXcore engine is started
,E/jxcore-log( 2933): >> LGE-Nexus 5
E/jxcore-log( 2933): 
,I/jxcore-log( 2933): Total memory 1946181632
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): Free memory 318627840
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): userPath [ 'www' ]
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): Size 1080 1776
I/jxcore-log( 2933): 
,I/jxcore-log( 2933): Screen Brightness 82
I/jxcore-log( 2933): 
E/jxcore-log( 2933): Dummy Error Log.
E/jxcore-log( 2933): 
,I/jxcore-log( 2933): getBuffer is called!!!!
I/jxcore-log( 2933): 
,I/ActivityManager(  760): Waited long enough for: ServiceRecord{3a06f870 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  760): Waited long enough for: ServiceRecord{3a0e8b46 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  760): Killing 2228:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,I/jxcore-log( 2933): ****TEST TOOK:  5067  ms ****
I/jxcore-log( 2933): 
I/jxcore-log( 2933): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2933): 
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2933:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  760): Force removing ActivityRecord{388b8631 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  760): Spurious death for ProcessRecord{96a1c7c 2933:com.example.hello/u0a277}, curProc for 2933: null
I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3064 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3096 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2306:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2343:com.google.android.keep/u0a71 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3124 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,--------- beginning of crash


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  853): Start proc com.android.browser for broadcast com.android.browser/com.lge.browser.settings.BrowserSettingReceiver: pid=3094 uid=10012 gids={50012, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  853): Killing 2375:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3147 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
I/ActivityManager(  853): Killing 1893:com.android.printspooler/u0a87 (adj 15): empty #11
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{3dd8d965 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{3dd8d965 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  853): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3167 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityThread( 1876): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1876): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1876): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1876): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1876): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1876): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1876): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1876): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1876): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  853): Activity reported stop, but no longer stopping: ActivityRecord{38b10a3b u0 com.lge.launcher2/.Launcher t218}
E/ActivityThread( 3147): Failed to find provider info for com.lge.ims.rcs
E/ActivityThread( 3147): Failed to find provider info for com.lge.ims.rcs
,I/ActivityManager(  853): Displayed com.example.hello/.MainActivity: +1s74ms
,E/ActivityThread( 3147): Failed to find provider info for com.lge.ims.provider.uc
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3255 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2540:com.lge.qremote/u0a106 (adj 15): empty #11
,W/jxcore-log( 3167): Initializing JXcore engine
W/jxcore-log( 3167): JXcore engine is ready
W/jxcore-log( 3167): Starting JXcore engine
,W/jxcore-log( 3167): Platform android
W/jxcore-log( 3167): 
W/jxcore-log( 3167): Process ARCH arm
W/jxcore-log( 3167): 
,I/ActivityManager(  853): Killing 2847:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/jxcore-log( 3167): JXcore Cordova bridge is ready!
I/jxcore-log( 3167): 
W/jxcore-log( 3167): JXcore engine is started
,E/jxcore-log( 3167): >> LGE-LG-D722
E/jxcore-log( 3167): 
,I/jxcore-log( 3167): Total memory 906309632
I/jxcore-log( 3167): 
I/jxcore-log( 3167): Free memory 32677888
I/jxcore-log( 3167): 
I/jxcore-log( 3167): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3167): 
I/jxcore-log( 3167): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3167): 
I/jxcore-log( 3167): userPath [ 'www' ]
I/jxcore-log( 3167): 
I/jxcore-log( 3167): Size 720 1196
I/jxcore-log( 3167): 
,I/jxcore-log( 3167): Screen Brightness 255
I/jxcore-log( 3167): 
E/jxcore-log( 3167): Dummy Error Log.
E/jxcore-log( 3167): 
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3281 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3308 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2867:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/jxcore-log( 3167): getBuffer is called!!!!
I/jxcore-log( 3167): 
,I/ActivityManager(  853): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3325 uid=10071 gids={50071, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2984:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,W/ActivityManager(  853): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3356 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3005:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  853): Killing 2131:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3036:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3389 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3418 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3437 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3054:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3459 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3073:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3483 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3094:com.android.browser/u0a12 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3504 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3535 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3255:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3563 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3582 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3325:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3611 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3356:com.lge.eula/1000 (adj 15): empty #11
,W/ActivityManager(  853): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,I/ActivityManager(  853): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3631 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2273:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3281:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3389:com.android.keychain/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3653 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3673 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3308:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/jxcore-log( 3167): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 3167): 
I/jxcore-log( 3167): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3167): 
,I/ActivityManager(  853): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3711 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3418:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3737 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3437:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ActivityManager(  853): Waited long enough for: ServiceRecord{257fb67d u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3767 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  853): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,I/ActivityManager(  853): Killing 3167:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  853): Force removing ActivityRecord{30af863a u0 com.example.hello/.MainActivity t219}: app died, no saved state
,I/ActivityManager(  853): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  853): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3798 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  853): Spurious death for ProcessRecord{3b169671 3167:com.example.hello/u0a30}, curProc for 3167: null
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3820 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3459:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3504:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3849 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3535:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  853): Waited long enough for: ServiceRecord{3c84b7ef u0 com.lge.sizechangable.weather/.service.WeatherService}
,I/ActivityManager(  853): Killing 3563:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3582:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3611:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system
I/ActivityManager( 2420): Waited long enough for: ServiceRecord{4343d5e0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,--------- beginning of /dev/log/main
W/ActivityManager( 2420): mDVFSHelper.acquire()
D/ActivityThread( 6473): Added TimaKesytore provider
,W/ActivityManager( 2420): mDVFSHelper.release()
,W/jxcore-log( 6473): Initializing JXcore engine
,W/jxcore-log( 6473): JXcore engine is ready
,W/jxcore-log( 6473): Starting JXcore engine
,W/jxcore-log( 6473): Platform android
W/jxcore-log( 6473): 
,W/jxcore-log( 6473): Process ARCH arm
W/jxcore-log( 6473): 
,I/jxcore-log( 6473): JXcore Cordova bridge is ready!
I/jxcore-log( 6473): 
,W/jxcore-log( 6473): JXcore engine is started
,E/jxcore-log( 6473): >> samsung-SM-G800F
E/jxcore-log( 6473): 
,I/jxcore-log( 6473): Total memory 1319530496
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Free memory 31678464
I/jxcore-log( 6473): 
I/jxcore-log( 6473): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Size 720 1280
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Screen Brightness 134
I/jxcore-log( 6473): 
,E/jxcore-log( 6473): Dummy Error Log.
E/jxcore-log( 6473): 
,I/jxcore-log( 6473): getBuffer is called!!!!
I/jxcore-log( 6473): 
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{4325c5e8 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,I/jxcore-log( 6473): ****TEST TOOK:  5325  ms ****
I/jxcore-log( 6473): 
I/jxcore-log( 6473): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6473): 
,I/ActivityManager( 2420): Killing 6473:com.example.hello/u0a426 (adj 0): stop com.example.hello
,W/ActivityManager( 2420): Force removing ActivityRecord{4314b5b0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ActivityManager( 2420): mDVFSHelper.acquire()
,D/ActivityThread( 6532): Added TimaKesytore provider
,W/ActivityManager( 2420): mDVFSHelper.release()
,I/ActivityManager( 2420): Killing 5715:com.sec.phone/1001 (adj 15): empty #43
,D/ActivityThread( 6546): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5587:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/ActivityThread( 6564): Added TimaKesytore provider
,D/ActivityThread( 6580): Added TimaKesytore provider
,D/ActivityThread( 6606): Added TimaKesytore provider,
,I/ActivityManager( 2420): Killing 5304:com.google.android.talk/u0a109 (adj 15): empty #43
,D/ActivityThread( 6625): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5733:com.android.calendar/u0a144 (adj 15): empty #43
,D/ActivityThread( 6631): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5789:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/ActivityThread( 6652): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5793:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/ActivityManager( 2420): Process com.google.android.apps.docs (pid 6652) (adj 0) has died.
,D/ActivityThread( 6673): Added TimaKesytore provider


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3445
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3461 uid=10357 gids={50357, 3003, 3001, 3002}
,I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +332ms (total +367ms)
,W/jxcore-log( 3461): Initializing JXcore engine
,W/jxcore-log( 3461): JXcore engine is ready
,W/jxcore-log( 3461): Starting JXcore engine
,W/jxcore-log( 3461): Platform android
W/jxcore-log( 3461): 
,W/jxcore-log( 3461): Process ARCH arm
W/jxcore-log( 3461): 
,I/jxcore-log( 3461): JXcore Cordova bridge is ready!
I/jxcore-log( 3461): 
,W/jxcore-log( 3461): JXcore engine is started
,E/jxcore-log( 3461): >> motorola-XT1039
E/jxcore-log( 3461): 
,I/jxcore-log( 3461): Total memory 893136896
I/jxcore-log( 3461): 
I/jxcore-log( 3461): Free memory 40529920
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): userPath [ 'www' ]
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): Size 720 1184
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): Screen Brightness 10
I/jxcore-log( 3461): 
,E/jxcore-log( 3461): Dummy Error Log.
E/jxcore-log( 3461): 
,I/jxcore-log( 3461): getBuffer is called!!!!
I/jxcore-log( 3461): 
,I/jxcore-log( 3461): ****TEST TOOK:  5031  ms ****
I/jxcore-log( 3461): 
I/jxcore-log( 3461): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3461): 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10357 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3461:com.example.hello/u0a357 (adj 0): stop com.example.hello
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{41f19228 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10357 user=0: pkg removed
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{41f19228 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{41f19228 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3572 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3592 uid=10058 gids={50058}
,I/ActivityManager( 1020): Killing 3343:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3610 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1020): Killing 3366:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1020): Killing 3286:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3626 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3125:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1029): Killing 3499:com.lge.lifetracker/u0a37 (adj 15): empty #17
I/ActivityManager( 1029): Killing 3642:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.BootReceiver: pid=4096 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{314e5970 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{314e5970 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1029): Waited long enough for: ServiceRecord{1d4e6e31 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1029): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4116 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4135 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 4096): Failed to find provider info for com.lge.lgaccount.provider
I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.wifi.WifiAutoControlReceiver: pid=4175 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/ActivityManager( 1029): Killing 3679:com.android.keychain/1000 (adj 15): empty #17
W/ActivityThread( 2085): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2085): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2085): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3321)
W/ActivityThread( 2085): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3407)
W/ActivityThread( 2085): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
W/ActivityThread( 2085): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1312)
W/ActivityThread( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 2085): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 2085): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ActivityThread( 2085): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 2085): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 2085): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ActivityThread( 2085): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1029): Killing 3394:com.lge.hiddenmenu/1000 (adj 15): empty #17
I/ActivityManager( 1029): Displayed com.example.hello/.MainActivity: +853ms
I/ActivityManager( 1029): Activity reported stop, but no longer stopping: ActivityRecord{213a784b u0 com.lge.launcher2/.Launcher t3}
I/ActivityManager( 1029): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=4254 uid=10042 gids={50042, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
W/jxcore-log( 4116): Initializing JXcore engine
W/jxcore-log( 4116): JXcore engine is ready
W/jxcore-log( 4116): Starting JXcore engine
I/ActivityManager( 1029): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=4275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 3722:com.google.android.onetimeinitializer/u0a7 (adj 15): empty #17
,W/jxcore-log( 4116): Platform android
W/jxcore-log( 4116): 
,W/jxcore-log( 4116): Process ARCH arm
W/jxcore-log( 4116): 
I/jxcore-log( 4116): JXcore Cordova bridge is ready!
I/jxcore-log( 4116): 
W/jxcore-log( 4116): JXcore engine is started
,E/jxcore-log( 4116): >> LGE-LG-D855
E/jxcore-log( 4116): 
I/jxcore-log( 4116): Total memory 2995761152
I/jxcore-log( 4116): 
I/jxcore-log( 4116): Free memory 837619712
I/jxcore-log( 4116): 
I/jxcore-log( 4116): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4116): 
I/jxcore-log( 4116): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4116): 
,I/jxcore-log( 4116): userPath [ 'www' ]
I/jxcore-log( 4116): 
I/jxcore-log( 4116): Size 1440 2392
I/jxcore-log( 4116): 
I/jxcore-log( 4116): Screen Brightness 50
I/jxcore-log( 4116): 
E/jxcore-log( 4116): Dummy Error Log.
E/jxcore-log( 4116): 
,I/ActivityManager( 1029): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4295 uid=10043 gids={50043, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager( 1029): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4325 uid=10050 gids={50050, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 3759:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4349 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 4116): getBuffer is called!!!!
I/jxcore-log( 4116): 
,I/ActivityManager( 1029): Killing 3796:com.lge.clock/u0a10 (adj 15): empty #17
,W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/ActivityManager( 1029): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4402 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4426 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 3847:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4455 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 3876:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4475 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 3905:com.android.browser/u0a12 (adj 15): empty #17
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 4475): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1029): Start proc com.lge.clock for content provider com.lge.clock/.alarmclock.ALProvider: pid=4519 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1029): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4544 uid=10065 gids={50065, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4475): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@33cc0505 that was originally bound here
E/ActivityThread( 4475): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@33cc0505 that was originally bound here
E/ActivityThread( 4475): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4475): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4475): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4475): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4475): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4475): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4475): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4475): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4475): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4475): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4475): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4475): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4475): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4475): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4475): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1029): Unbind failed: could not find connection for android.os.BinderProxy@1da14c70
,I/ActivityManager( 1029): Killing 3942:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #17
,I/ActivityManager( 1029): Killing 2981:com.android.contacts/u0a19 (adj 15): empty #17
,W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/ActivityManager( 1029): Killing 2527:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4567 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1029): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.lgodm.LGODMReceiver: pid=4607 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4012:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/ActivityManager( 1029): Killing 4039:com.lge.email/u0a23 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4626 uid=10073 gids={50073, 9997} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 3582:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4645 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4135:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4665 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1029): Killing 4096:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4683 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 2628:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/ActivityManager( 1029): Waited long enough for: ServiceRecord{3601cf7a u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager( 1029): Killing 4175:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4701 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4254:com.lge.voicerecorder/u0a42 (adj 15): empty #17
,I/ActivityManager( 1029): Process com.lge.defaultaccount (pid 4626) has died
,I/ActivityManager( 1029): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/ActivityManager( 1029): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4736 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4295:com.android.managedprovisioning/u0a43 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=4755 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 4116): ****TEST TOOK:  5111  ms ****
I/jxcore-log( 4116): 
I/jxcore-log( 4116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4116): 
,I/ActivityManager( 1029): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4777 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 4349:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=4805 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4402:com.lge.cloudhub/u0a58 (adj 15): empty #17
,I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 4116:com.example.hello/u0a318 (adj 0): stop com.example.hello
,W/ActivityManager( 1029): Force removing ActivityRecord{3a3c64e9 u0 com.example.hello/.MainActivity t4}: app died, no saved state
,W/ActivityManager( 1029): Spurious death for ProcessRecord{11ffa7df 4116:com.example.hello/u0a318}, curProc for 4116: null
I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=0: pkg removed
,--------- beginning of crash
I/ActivityManager( 1029): Process com.google.android.youtube (pid 4805) has died
W/ActivityManager( 1029): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/ActivityManager( 1029): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService$DeviceStateReceiver: pid=4876 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4791 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +944ms
,W/jxcore-log( 4791): Initializing JXcore engine
W/jxcore-log( 4791): JXcore engine is ready
,W/jxcore-log( 4791): Starting JXcore engine
,W/jxcore-log( 4791): Platform android
W/jxcore-log( 4791): 
W/jxcore-log( 4791): Process ARCH arm
W/jxcore-log( 4791): 
,I/jxcore-log( 4791): JXcore Cordova bridge is ready!
I/jxcore-log( 4791): 
,W/jxcore-log( 4791): JXcore engine is started
,E/jxcore-log( 4791): >> motorola-XT1072
E/jxcore-log( 4791): 
,I/jxcore-log( 4791): Total memory 916258816
I/jxcore-log( 4791): 
I/jxcore-log( 4791): Free memory 31272960
I/jxcore-log( 4791): 
I/jxcore-log( 4791): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4791): 
,I/jxcore-log( 4791): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4791): 
,I/jxcore-log( 4791): userPath [ 'www' ]
I/jxcore-log( 4791): 
,I/jxcore-log( 4791): Size 720 1184
I/jxcore-log( 4791): 
,I/jxcore-log( 4791): Screen Brightness 82
I/jxcore-log( 4791): 
E/jxcore-log( 4791): Dummy Error Log.
E/jxcore-log( 4791): 
,I/jxcore-log( 4791): getBuffer is called!!!!
I/jxcore-log( 4791): 
,I/jxcore-log( 4791): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 4791): 
I/jxcore-log( 4791): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4791): 
,I/ActivityManager(  884): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
,I/ActivityManager(  884): Killing 4791:com.example.hello/u0a278 (adj 0): stop com.example.hello
,W/ActivityManager(  884): Force removing ActivityRecord{3e53cc97 u0 com.example.hello/.MainActivity t181}: app died, no saved state
,W/ActivityManager(  884): Spurious death for ProcessRecord{12fded8b 4791:com.example.hello/u0a278}, curProc for 4791: null
,I/ActivityManager(  884): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4909 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4935 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4613:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4954 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4653:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4973 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5007 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager(  848): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  848): mDVFSHelper.acquire()
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6722 uid=10191 gids={50191, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6722): Added TimaKeyStore provider
V/ActivityManager(  848): Display changed displayId=0
D/ActivityManager(  848): post active user change for 0
I/ActivityManager(  848): Displayed com.example.hello/.MainActivity: +566ms
W/ActivityManager(  848): mDVFSHelper.release()
W/jxcore-log( 6722): Initializing JXcore engine
W/jxcore-log( 6722): JXcore engine is ready
W/jxcore-log( 6722): Starting JXcore engine
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6774): Added TimaKeyStore provider
,I/ActivityManager(  848): Killing 5286:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,W/jxcore-log( 6722): Platform android
W/jxcore-log( 6722): 
W/jxcore-log( 6722): Process ARCH arm
W/jxcore-log( 6722): 
,I/jxcore-log( 6722): JXcore Cordova bridge is ready!
I/jxcore-log( 6722): 
,W/jxcore-log( 6722): JXcore engine is started
,E/jxcore-log( 6722): >> samsung-SM-G900F
E/jxcore-log( 6722): 
,I/jxcore-log( 6722): Total memory 1787449344
I/jxcore-log( 6722): 
,I/jxcore-log( 6722): Free memory 59576320
I/jxcore-log( 6722): 
I/jxcore-log( 6722): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6722): 
I/jxcore-log( 6722): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6722): 
,I/jxcore-log( 6722): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6722): 
,I/jxcore-log( 6722): Size 1080 1920
I/jxcore-log( 6722): 
,I/jxcore-log( 6722): Screen Brightness 134
I/jxcore-log( 6722): 
,E/jxcore-log( 6722): Dummy Error Log.
E/jxcore-log( 6722): 
,I/jxcore-log( 6722): getBuffer is called!!!!
I/jxcore-log( 6722): 
,I/ActivityManager(  848): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  848): mDVFSHelper.acquire()
,E/ActivityManager(  848): Invalid thumbnail dimensions: 576x576
,D/ActivityManager(  848): post active user change for 0
,I/jxcore-log( 6722): ****TEST TOOK:  5043  ms ****
I/jxcore-log( 6722): 
,I/jxcore-log( 6722): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6722): 
,I/ActivityManager(  848): Force stopping com.example.hello appid=10191 user=-1: uninstall pkg
I/ActivityManager(  848): Killing 6722:com.example.hello/u0a191 (adj 0): stop com.example.hello
,W/ActivityManager(  848): Force removing ActivityRecord{163b0526 u0 com.example.hello/.MainActivity t361}: app died, no saved state
,I/ActivityManager(  848): Force stopping com.example.hello appid=10191 user=0: pkg removed
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6822 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  848): handle home activity for 0
D/ActivityManager(  848): post active user change for 0
,D/ActivityThread( 6822): Added TimaKeyStore provider
,W/ActivityManager(  848): mDVFSHelper.release()
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6846 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5123:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
,D/ActivityThread( 6846): Added TimaKeyStore provider
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6866 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5423:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,D/ActivityThread( 6866): Added TimaKeyStore provider
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6887 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5976:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,D/ActivityThread( 6887): Added TimaKeyStore provider
,I/ActivityManager(  848): Killing 6120:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 3527): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 3527): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager( 3527): mDVFSHelper.acquire()
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3527): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10732 uid=10385 gids={50385, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 3999): updateVisibility : ActivityRecord{fbcedca token=android.os.BinderProxy@33c526ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread(10732): Added TimaKeyStore provider
V/ActivityThread( 3999): updateVisibility : ActivityRecord{fbcedca token=android.os.BinderProxy@33c526ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/ActivityManager( 3527): Display changed displayId=0
,D/ActivityManager( 3527): post active user change for 0
,I/ActivityManager( 3527): Displayed com.example.hello/.MainActivity: +337ms
,W/jxcore-log(10732): Initializing JXcore engine
W/jxcore-log(10732): JXcore engine is ready
,W/jxcore-log(10732): Starting JXcore engine
,W/jxcore-log(10732): Platform android
W/jxcore-log(10732): 
W/jxcore-log(10732): Process ARCH arm
W/jxcore-log(10732): 
,I/jxcore-log(10732): JXcore Cordova bridge is ready!
I/jxcore-log(10732): 
W/jxcore-log(10732): JXcore engine is started
,E/jxcore-log(10732): >> samsung-SM-N910C
E/jxcore-log(10732): 
,I/jxcore-log(10732): Total memory 2970812416
I/jxcore-log(10732): 
,I/jxcore-log(10732): Free memory 117972992
I/jxcore-log(10732): 
I/jxcore-log(10732): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10732): 
I/jxcore-log(10732): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10732): 
,I/jxcore-log(10732): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10732): 
,I/jxcore-log(10732): Size 1440 2560
I/jxcore-log(10732): 
,I/jxcore-log(10732): Screen Brightness 134
I/jxcore-log(10732): 
,E/jxcore-log(10732): Dummy Error Log.
E/jxcore-log(10732): 
,W/ActivityManager( 3527): mDVFSHelper.release()
,I/jxcore-log(10732): getBuffer is called!!!!
I/jxcore-log(10732): 
,I/jxcore-log(10732): ****TEST TOOK:  5079  ms ****
I/jxcore-log(10732): 
,I/jxcore-log(10732): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10732): 
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10385 user=-1: uninstall pkg
I/ActivityManager( 3527): Killing 10732:com.example.hello/u0a385 (adj 0): stop com.example.hello
,W/ActivityManager( 3527): Force removing ActivityRecord{278a9207 u0 com.example.hello/.MainActivity t441}: app died, no saved state
,W/ActivityManager( 3527): mDVFSHelper.acquire()
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10385 user=0: pkg removed
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10818 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 3527): handle home activity for 0
D/ActivityManager( 3527): post active user change for 0
,D/ActivityThread(10818): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10839 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10022:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/ActivityThread(10839): Added TimaKeyStore provider
,V/ActivityThread( 3999): updateVisibility : ActivityRecord{fbcedca token=android.os.BinderProxy@33c526ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10861 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread(10861): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10880 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(10880): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10896 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,W/ActivityManager( 3527): mDVFSHelper.release()
,D/ActivityThread(10896): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
V/ActivityManager( 3527): Display changed displayId=0
,I/ActivityManager( 3527): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10914 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ActivityThread(10914): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10944 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,D/ActivityThread(10929): Added TimaKeyStore provider
I/ActivityManager( 3527): Killing 10040:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/ActivityManager( 3527): Killing 10106:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ActivityThread(10944): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 10090:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10960 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(10960): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=10977 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(10977): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10063:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/ActivityThread(10995): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=11018 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10209:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/ActivityThread(11018): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 10160:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Process com.android.keychain (pid 10929)(adj 5) has died(174,1299)
,W/ActivityManager( 3527): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=11036 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/ActivityManager( 3527): Process com.sec.pcw.device (pid 10960)(adj 9) has died(158,1299)
,D/ActivityThread(11036): Added TimaKeyStore provider
,D/ActivityThread(10995): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ActivityThread(10995): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.facebook.katana:dash for broadcast com.facebook.katana/com.facebook.dash.receivers.DashPackageUninstallReceiver: pid=11058 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Process ACMS.Process (pid 10995)(adj 0) has died(205,1299)
,W/ActivityManager( 3527): Scheduling restart of crashed service com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService in 1000ms
,I/ActivityManager( 3527): Process com.google.android.googlequicksearchbox:search (pid 4052)(adj 1) has died(205,1299)
,D/ActivityThread(11058): Added TimaKeyStore provider
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10991ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10990ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 20990ms
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=11074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3527): Killing 10369:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 10312:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##32
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(11074): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=11092 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10384:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ActivityThread(11092): Added TimaKeyStore provider
,I/ActivityManager( 3527): Process com.facebook.appmanager (pid 10977)(adj 9) has died(226,1299)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=11107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(11107): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 10470:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3527): Process com.facebook.katana:dash (pid 11058)(adj 9) has died(254,1300)
D/ActivityThread(11134): Added TimaKeyStore provider
,I/ActivityManager( 3527): Process com.google.process.gapps (pid 4161)(adj 1) has died(318,1300)
,W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30597ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40597ms
,I/ActivityManager( 3527): Process com.google.android.gms (pid 4479)(adj 5) has died(310,1300)
,W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 50581ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 50581ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 50581ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 50581ms
W/ActivityManager( 3527): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 60581ms


```

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on ZX1G429CRK 
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
,I/ActivityManager(  890): do not start freezing screen for locked container getKeyguardshowstate = false
--------- beginning of system
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  890): mDVFSHelper.acquire()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  890): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6174 uid=10219 gids={50219, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1434): updateVisibility : ActivityRecord{6aceaa8 token=android.os.BinderProxy@1a372714 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 6174): Added TimaKeyStore provider
V/ActivityManager(  890): Display changed displayId=0
V/ActivityThread( 1434): updateVisibility : ActivityRecord{6aceaa8 token=android.os.BinderProxy@1a372714 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/ActivityManager(  890): post active user change for 0
I/ActivityManager(  890): Displayed com.example.hello/.MainActivity: +582ms
W/jxcore-log( 6174): Initializing JXcore engine
W/jxcore-log( 6174): JXcore engine is ready
W/jxcore-log( 6174): Starting JXcore engine
W/ActivityManager(  890): mDVFSHelper.release()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6233 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/jxcore-log( 6174): Platform android
W/jxcore-log( 6174): 
W/jxcore-log( 6174): Process ARCH arm
W/jxcore-log( 6174): 
,D/ActivityThread( 6233): Added TimaKeyStore provider
I/ActivityManager(  890): Killing 5034:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
I/jxcore-log( 6174): JXcore Cordova bridge is ready!
I/jxcore-log( 6174): 
W/jxcore-log( 6174): JXcore engine is started
E/jxcore-log( 6174): >> samsung-SM-N9005
E/jxcore-log( 6174): 
I/jxcore-log( 6174): Total memory 2971471872
I/jxcore-log( 6174): 
I/jxcore-log( 6174): Free memory 418775040
I/jxcore-log( 6174): 
I/jxcore-log( 6174): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6174): 
I/jxcore-log( 6174): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6174): 
I/jxcore-log( 6174): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6174): 
I/jxcore-log( 6174): Size 1080 1920
I/jxcore-log( 6174): 
I/jxcore-log( 6174): Screen Brightness 162
I/jxcore-log( 6174): 
E/jxcore-log( 6174): Dummy Error Log.
E/jxcore-log( 6174): 
,I/jxcore-log( 6174): getBuffer is called!!!!
I/jxcore-log( 6174): 
,I/jxcore-log( 6174): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 6174): 
,I/jxcore-log( 6174): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6174): 
,I/ActivityManager(  890): Force stopping com.example.hello appid=10219 user=-1: uninstall pkg
,I/ActivityManager(  890): Killing 6174:com.example.hello/u0a219 (adj 0): stop com.example.hello
,W/ActivityManager(  890): Force removing ActivityRecord{1b047a51 u0 com.example.hello/.MainActivity t2}: app died, no saved state
W/ActivityManager(  890): mDVFSHelper.acquire()
,I/ActivityManager(  890): Force stopping com.example.hello appid=10219 user=0: pkg removed
,W/ActivityManager(  890): Spurious death for ProcessRecord{3ce2c8f 6174:com.example.hello/u0a219}, curProc for 6174: null
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6312 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  890): handle home activity for 0
D/ActivityManager(  890): post active user change for 0
,D/ActivityThread( 6312): Added TimaKeyStore provider
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6335 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 4399:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,W/ActivityManager(  890): mDVFSHelper.release()
,D/ActivityThread( 6335): Added TimaKeyStore provider
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6352 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5068:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/ActivityThread( 6352): Added TimaKeyStore provider
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6370 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5320:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ActivityThread( 6370): Added TimaKeyStore provider
,I/ActivityManager(  890): Killing 5337:com.sec.knox.bridge/1000 (adj 13): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6391 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6391): Added TimaKeyStore provider
,E/ActivityThread( 6391): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6408 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 6408): Added TimaKeyStore provider
,I/ActivityManager(  890): Process com.google.android.googlequicksearchbox:search (pid 1618)(adj 1) has died(493,1361)
,W/ActivityManager(  890): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  890): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
W/ActivityManager(  890): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6423 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5399:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,E/ActivityThread( 6408): Unable to setupGraphicsSupport due to missing cache directory
,D/ActivityThread( 6423): Added TimaKeyStore provider
,I/ActivityManager(  890): Killing 4806:com.sec.android.app.music:service/u0a49 (adj 13): bgCount ##41
,E/ActivityThread( 6423): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a


HTC-HTC One_M8: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5807 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +464ms
I/ActivityManager(  892): Killing 5255:com.htc.cs.dm/u0a105 (adj 15): empty #17
I/ActivityManager(  892): Recipient 5255
I/ActivityManager(  892): Killing 5444:com.google.android.apps.docs/u0a107 (adj 15): empty #17
I/ActivityManager(  892): Recipient 5444
W/jxcore-log( 5807): Initializing JXcore engine
W/jxcore-log( 5807): JXcore engine is ready
W/jxcore-log( 5807): Starting JXcore engine
,W/jxcore-log( 5807): Platform android
W/jxcore-log( 5807): 
W/jxcore-log( 5807): Process ARCH arm
W/jxcore-log( 5807): 
,I/jxcore-log( 5807): JXcore Cordova bridge is ready!,
I/jxcore-log( 5807): 
W/jxcore-log( 5807): JXcore engine is started
,E/jxcore-log( 5807): >> HTC-HTC One_M8
E/jxcore-log( 5807): 
,I/jxcore-log( 5807): Total memory 1912020992,
I/jxcore-log( 5807): 
I/jxcore-log( 5807): Free memory 129576960
I/jxcore-log( 5807): 
I/jxcore-log( 5807): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5807): 
I/jxcore-log( 5807): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5807): 
,I/jxcore-log( 5807): userPath [ 'www' ]
I/jxcore-log( 5807): 
,I/jxcore-log( 5807): Size 1080 1776
I/jxcore-log( 5807): 
,I/jxcore-log( 5807): Screen Brightness 142
I/jxcore-log( 5807): 
,E/jxcore-log( 5807): Dummy Error Log.
E/jxcore-log( 5807): 
,I/jxcore-log( 5807): getBuffer is called!!!!
I/jxcore-log( 5807): 
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{1c3b912d u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  892): Killing 5521:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5521,
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{1bb1f6ca u0 com.htc.musicenhancer/.EnhancerService},
,I/jxcore-log( 5807): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 5807): 
I/jxcore-log( 5807): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5807): 
,I/ActivityManager(  892): Killing 5539:com.htc.sdm/u0a82 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5539,
,I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  892): Killing 5807:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  892): Recipient 5807,
,W/ActivityManager(  892): Force removing ActivityRecord{2f3086e5 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/ActivityManager(  892): Spurious death for ProcessRecord{95cc0ed 5807:com.example.hello/u0a380}, curProc for 5807: null
,I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5910 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5561:com.htc.task/u0a72 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5561,
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5942 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5997 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,I/ActivityManager(  892): Recipient 5942
,I/ActivityManager(  892): Process com.google.android.apps.docs (pid 5942) has died,
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=6014 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6033 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=6053 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  892): App crashed! Process: com.android.documentsui,
I/ActivityManager(  892): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6070 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5382:com.google.android.gms:car/u0a25 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5382
,W/ActivityManager(  892): Can't addPackageDependency on system process
,I/ActivityManager(  892): Killing 4380:com.android.defcontainer/u0a15 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4380
,I/ActivityManager(  892): Killing 4948:com.google.android.music:main/u0a167 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4948
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0,
,I/ActivityManager(  892): Recipient 6014
,I/ActivityManager(  892): Process com.google.android.apps.docs (pid 6014) has died,
W/ActivityManager(  892): Force removing ActivityRecord{20193d75 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state
,I/ActivityManager(  892): Killing 5163:com.google.android.gm/u0a115 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5163


motorola-Nexus 6: 
--------- beginning of system
I/ActivityManager(  822): Process com.motorola.service.ims (pid 1978) has died
--------- beginning of main
I/ActivityManager(  822): Start proc 2088:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
I/ActivityManager(  822): Start proc 2120:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  822): Start proc 2146:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
I/ActivityManager(  822): Start proc 2168:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  822): Start proc 2200:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  822): Start proc 2235:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
,I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +418ms (total +7s767ms)
,W/jxcore-log( 2235): Initializing JXcore engine
W/jxcore-log( 2235): JXcore engine is ready
,W/jxcore-log( 2235): Starting JXcore engine
,I/ActivityManager(  822): Start proc 2301:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,W/jxcore-log( 2235): Platform android
W/jxcore-log( 2235): 
W/jxcore-log( 2235): Process ARCH arm
W/jxcore-log( 2235): 
,I/jxcore-log( 2235): JXcore Cordova bridge is ready!
I/jxcore-log( 2235): 
,W/jxcore-log( 2235): JXcore engine is started
,E/jxcore-log( 2235): >> motorola-Nexus 6
E/jxcore-log( 2235): 
,I/jxcore-log( 2235): Total memory 3113791488
I/jxcore-log( 2235): 
,I/jxcore-log( 2235): Free memory 1201065984
I/jxcore-log( 2235): 
I/jxcore-log( 2235): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2235): 
I/jxcore-log( 2235): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2235): 
,I/jxcore-log( 2235): userPath [ 'www' ]
I/jxcore-log( 2235): 
,I/jxcore-log( 2235): Size 1440 2392
I/jxcore-log( 2235): 
,I/jxcore-log( 2235): Screen Brightness 82
I/jxcore-log( 2235): 
E/jxcore-log( 2235): Dummy Error Log.
E/jxcore-log( 2235): 
,I/ActivityManager(  822): Start proc 2338:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/jxcore-log( 2235): getBuffer is called!!!!
I/jxcore-log( 2235): 
,I/ActivityManager(  822): Start proc 2359:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,--------- beginning of crash
,I/ActivityManager(  822): Start proc 2393:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager(  822): Start proc 2429:com.android.keychain/1000 for service com.android.keychain/.KeyChainService
,I/ActivityManager(  822): Start proc 2453:com.google.android.dialer/u0a13 for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver
,I/ActivityManager(  822): Start proc 2476:com.motorola.motocit/u0a2 for broadcast com.motorola.motocit/.CQATestBootReceiver
,I/ActivityManager(  822): Killing 1905:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1498:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/ActivityManager(  822): Killing 2030:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2497:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  822): Killing 1996:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2518:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.BootCompletedReceiver
,I/ActivityManager(  822): Start proc 2546:com.google.android.onetimeinitializer/u0a15 for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  822): Killing 2013:com.verizon.omadm/u0a93 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2570:com.android.managedprovisioning/u0a17 for broadcast com.android.managedprovisioning/.BootReminder
,I/ActivityManager(  822): Killing 1444:com.android.printspooler/u0a81 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2591:com.android.settings/1000 for broadcast com.android.settings/.sim.SimBootReceiver
,I/ActivityManager(  822): Killing 2088:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2120:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2168:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2611:org.simalliance.openmobileapi.service/u0a23 for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver
,I/ActivityManager(  822): Killing 2200:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2631:org.simalliance.openmobileapi.service:remote/u0a23 for service org.simalliance.openmobileapi.service/.SmartcardService
,I/ActivityManager(  822): Start proc 2648:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  822): Killing 1563:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/jxcore-log( 2235): ****TEST TOOK:  5201  ms ****
I/jxcore-log( 2235): 
,I/jxcore-log( 2235): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2235): 
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 2235:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/ActivityManager(  822): Force removing ActivityRecord{16427c6a u0 com.example.hello/.MainActivity t20}: app died, no saved state
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{e4094fa 2235:com.example.hello/u0a272}, curProc for 2235: null
,I/ActivityManager(  822): Start proc 2688:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
,I/ActivityManager(  822): Start proc 2711:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  822): Start proc 2758:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,I/ActivityManager(  822): Killing 1471:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2786:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/ActivityManager(  822): Start proc 2803:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,I/ActivityManager(  822): Killing 2359:com.google.android.apps.plus/u0a74 (adj 15): empty #17


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5426 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5426): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
V/ActivityThread( 1474): updateVisibility : ActivityRecord{148fb067 token=android.os.BinderProxy@121e6692 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{1d83fc54 u0 com.example.hello/.MainActivity t22}
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5426): updateVisibility : ActivityRecord{100fc938 token=android.os.BinderProxy@1d50c1aa {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1017): Displayed Component not be shown by security: +658ms (total +738ms)
,W/ActivityManager( 1017): mDVFSHelper.release()
,W/jxcore-log( 5426): Initializing JXcore engine
W/jxcore-log( 5426): JXcore engine is ready
,W/jxcore-log( 5426): Starting JXcore engine
,W/jxcore-log( 5426): Platform android
W/jxcore-log( 5426): 
W/jxcore-log( 5426): Process ARCH arm
W/jxcore-log( 5426): 
,I/jxcore-log( 5426): JXcore Cordova bridge is ready!
I/jxcore-log( 5426): 
,W/jxcore-log( 5426): JXcore engine is started
,E/jxcore-log( 5426): >> samsung-SM-A300FU
E/jxcore-log( 5426): 
,I/jxcore-log( 5426): Total memory 1451114496
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): Free memory 25841664
I/jxcore-log( 5426): 
I/jxcore-log( 5426): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5426): 
I/jxcore-log( 5426): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): userPath [ 'www' ]
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): Size 540 960
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): Screen Brightness 160
I/jxcore-log( 5426): 
E/jxcore-log( 5426): Dummy Error Log.
E/jxcore-log( 5426): 
,I/jxcore-log( 5426): getBuffer is called!!!!
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5426): 
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 5426:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1d83fc54 u0 com.example.hello/.MainActivity t22}
,W/ActivityManager( 1017): Spurious death for ProcessRecord{974c67f 5426:com.example.hello/u0a345}, curProc for 5426: null
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1d83fc54 u0 com.example.hello/.MainActivity t22 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{1d83fc54 u0 com.example.hello/.MainActivity t22 f}
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5490 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 5490): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1017): Killing 4893:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5510 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityThread( 5510): Added TimaKeyStore provider
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3922:com.sec.spp.push/u0a32 (adj 15): empty #31,
,D/ActivityThread( 5527): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5555 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 5544): Added TimaKeyStore provider


HTC-HTC One M8s: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  970): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4544 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  970): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4585 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Killing 3954:com.google.android.configupdater/u0a98 (adj 15): empty #17
I/ActivityManager(  970): Recipient 3954
I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4626 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4571 on display 0
I/ActivityManager(  970): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4654 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityThread( 1513): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1513): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1513): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1513): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1513): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1513): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1513): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1513): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1513): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1513): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1513): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1513): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  970): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4678 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/ActivityManager(  970): Activity reported stop, but no longer stopping: ActivityRecord{22929f41 u0 com.htc.launcher/.Launcher t9}
W/ActivityThread( 4626): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  970): Killing 3102:com.htc.cs.dm/u0a99 (adj 15): empty #17
I/ActivityManager(  970): Recipient 3102
I/ActivityManager(  970): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4716 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/ActivityManager(  970): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4738 uid=10076 gids={50076, 9997} abi=arm64-v8a
I/ActivityManager(  970): Killing 3997:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  970): Recipient 3997
I/ActivityManager(  970): Killing 4026:com.htc.htccupd/u0a13 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4026
I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4774 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  970): Killing 4095:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4095
I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4799 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4822 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  970): Killing 4116:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4116
I/ActivityManager(  970): Displayed com.example.hello/.MainActivity: +1s644ms
I/ActivityManager(  970): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4858 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager(  970): Killing 4142:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4142
I/ActivityManager(  970): Killing 4165:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4165
,W/jxcore-log( 4654): Initializing JXcore engine,
W/jxcore-log( 4654): JXcore engine is ready
,W/jxcore-log( 4654): Starting JXcore engine,
,I/ActivityManager(  970): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,W/jxcore-log( 4654): Platform android
W/jxcore-log( 4654): 
,W/jxcore-log( 4654): Process ARCH arm
W/jxcore-log( 4654): 
,I/jxcore-log( 4654): JXcore Cordova bridge is ready!,
I/jxcore-log( 4654): 
W/jxcore-log( 4654): JXcore engine is started
,I/ActivityManager(  970): Killing 4223:com.google.android.gms:car/u0a24 (adj 15): empty #17
,E/jxcore-log( 4654): >> HTC-HTC One M8s
E/jxcore-log( 4654): 
,I/jxcore-log( 4654): Total memory 1931808768,
I/jxcore-log( 4654): 
I/jxcore-log( 4654): Free memory 90247168
I/jxcore-log( 4654): 
I/jxcore-log( 4654): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4654): 
I/jxcore-log( 4654): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4654): 
,I/jxcore-log( 4654): userPath [ 'www' ]
I/jxcore-log( 4654): 
,I/jxcore-log( 4654): Size 1080 1776,
I/jxcore-log( 4654): 
,I/jxcore-log( 4654): Screen Brightness 142
I/jxcore-log( 4654): 
,E/jxcore-log( 4654): Dummy Error Log.
E/jxcore-log( 4654): 
,I/ActivityManager(  970): Recipient 4223,
,I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4916 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4186:com.android.vending/u0a72 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4186
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{b199054 u0 com.htc.HTCSpeaker/.NGFService},
,I/jxcore-log( 4654): getBuffer is called!!!!
I/jxcore-log( 4654): 
,I/ActivityManager(  970): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4967 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 3286:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 3286
,I/ActivityManager(  970): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4989 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 4382:com.google.android.youtube/u0a176 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4382
,I/ActivityManager(  970): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5013 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  970): Killing 4461:com.google.android.gm/u0a106 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4461,
,I/ActivityManager(  970): Killing 4504:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4504,
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 4074): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4074): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  970): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5056 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 4678:com.htc.sense.news/u0a74 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4678
,W/ActivityThread( 5056): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5095 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 4716:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4716,
,I/ActivityManager(  970): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5125 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5170 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  970): Killing 4738:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4738
,I/ActivityManager(  970): Killing 3746:com.htc.sense.mms/u0a64 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 3746
,I/ActivityManager(  970): Killing 4774:com.htc.mobiledata:remote/u0a46 (adj 15): empty #18
,I/ActivityManager(  970): Recipient 4774,
,I/ActivityManager(  970): Killing 4822:com.htc.mobiledata/u0a46 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 4822
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5204 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
I/ActivityManager(  970): Killing 4349:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4349
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5229 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,I/jxcore-log( 4654): ****TEST TOOK:  5088  ms ****,
I/jxcore-log( 4654): 
I/ActivityManager(  970): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5258 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
I/jxcore-log( 4654): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4654): 
,I/ActivityManager(  970): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5280 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5315 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4858:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4858,
,I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  970): Killing 4654:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  970): Recipient 4654,
,W/ActivityManager(  970): Force removing ActivityRecord{1c6d92b1 u0 com.example.hello/.MainActivity t10}: app died, no saved state,
,W/ActivityManager(  970): Spurious death for ProcessRecord{17eb6a8d 4654:com.example.hello/u0a373}, curProc for 4654: null
I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=0: pkg removed
,I/ActivityManager(  970): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5372 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4891:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4891
,I/ActivityManager(  970): Killing 4544:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4544
,I/ActivityManager(  970): Killing 4967:com.htc.cs.dm/u0a99 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4967,
,W/ActivityThread( 5315): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,E/ActivityManager(  970): App crashed! Process: com.google.android.music:main


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 3334:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43370fe8 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  962): Waited long enough for: ServiceRecord{431b3b60 u0 com.lge.slideaside/.MainService}
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3843
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43370fe8 stackId=1, 2 tasks}
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{43370fe8 stackId=1, 2 tasks}
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43370fe8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  962): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3861 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager( 3861): Timeline: Activity_idle id: android.os.BinderProxy@42880408 time:42468
I/ActivityManager(  962): Displayed com.example.hello/.MainActivity: +370ms
W/jxcore-log( 3861): Initializing JXcore engine
W/jxcore-log( 3861): JXcore engine is ready
W/jxcore-log( 3861): Starting JXcore engine
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3} time:42885
D/ActivityManager(  962): no-history finish of ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{43101d00 ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3861): Platform android
W/jxcore-log( 3861): 
W/jxcore-log( 3861): Process ARCH arm
W/jxcore-log( 3861): 
I/jxcore-log( 3861): JXcore Cordova bridge is ready!
I/jxcore-log( 3861): 
W/jxcore-log( 3861): JXcore engine is started
,E/jxcore-log( 3861): >> LGE-LG-D802
E/jxcore-log( 3861): 
,I/jxcore-log( 3861): Total memory 1943035904
I/jxcore-log( 3861): 
I/jxcore-log( 3861): Free memory 448516096
I/jxcore-log( 3861): 
I/jxcore-log( 3861): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3861): 
,I/jxcore-log( 3861): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3861): 
,I/jxcore-log( 3861): userPath [ 'www' ]
I/jxcore-log( 3861): 
,I/jxcore-log( 3861): Size 1080 1776
I/jxcore-log( 3861): 
,I/jxcore-log( 3861): Screen Brightness 255
I/jxcore-log( 3861): 
,E/jxcore-log( 3861): Dummy Error Log.
E/jxcore-log( 3861): 
,I/jxcore-log( 3861): getBuffer is called!!!!
I/jxcore-log( 3861): 
,I/ActivityManager(  962): Killing 3379:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43370fe8 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3861): ****TEST TOOK:  5039  ms ****
I/jxcore-log( 3861): 
,I/jxcore-log( 3861): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3861): 
,I/ActivityManager(  962): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  962): Killing 3861:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  962): Force removing ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{433828c0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43370fe8 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  962): moveHomeStack:
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/ActivityManager(  962): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{4287c620 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3964 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=3978 uid=10090 gids={50090}
,I/ActivityManager(  962): Killing 3283:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  962): Service ServiceRecord{432001c8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432912b0 3283:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  962): Service ServiceRecord{430b79c0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432912b0 3283:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Killing 2082:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4005 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  962): Delaying start of: ServiceRecord{43177808 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1} time:49554
,I/ActivityManager(  962): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4022 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  962): Killing 3193:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  962): Killing 3726:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4287bfb8 time:49608
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4039 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  962): Killing 3742:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Delaying start of: ServiceRecord{431a5a28 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager(  962): Process android.process.media (pid 4039) has died.
,I/ActivityManager(  962): Start proc android.process.media for restart android.process.media: pid=4055 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Process com.google.android.gms (pid 1939) has died.
,W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10998ms
W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10996ms
W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20996ms
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c13f28 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c508f8 u0 com.lge.launcher2/.Launcher t1}


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on c5afcdcb 
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
D/ActivityThread( 4526): Added TimaKeyStore provider
--------- beginning of system
I/ActivityManager( 1019): Killing 3801:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1019): Process com.samsung.indexservice (pid 4491)(adj 9) has died(72,1132)
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{1a440db6 u0 com.samsung.android.providers.context/.ContextService}
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=4562 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 4562): Added TimaKeyStore provider
I/ActivityManager( 1019): Waited long enough for: ServiceRecord{3beb7ab7 u0 com.android.settings/.wifi.WifiCredService}
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=4602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityThread( 4602): Added TimaKeyStore provider
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
I/ActivityManager( 1019): Process com.samsung.indexservice (pid 4562)(adj 9) has died(40,1136)
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4621 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1494): updateVisibility : ActivityRecord{33e47582 token=android.os.BinderProxy@3b8bce4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=4635 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/ActivityThread( 4621): Added TimaKeyStore provider
V/ActivityThread( 1494): updateVisibility : ActivityRecord{33e47582 token=android.os.BinderProxy@3b8bce4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityThread( 4635): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
I/ActivityManager( 1019): Killing 3864:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/ActivityManager( 1019): Killing 3845:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #32
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4673 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageChangeEventReceiver: pid=4687 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 4673): Added TimaKeyStore provider
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4703 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityThread( 4687): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4720 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4703): Added TimaKeyStore provider
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4735 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3880:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
D/ActivityThread( 4720): Added TimaKeyStore provider
D/ActivityThread( 4735): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4759 uid=10091 gids={50091, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3907:com.sec.modem.settings/1000 (adj 15): empty #31
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4759): Added TimaKeyStore provider
I/ActivityManager( 1019): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4775 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3922:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4775): Added TimaKeyStore provider,
,I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3953:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/ActivityThread( 4791): Added TimaKeyStore provider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4811 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3985:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4811): Added TimaKeyStore provider
,I/ActivityManager( 1019): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4827 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4001:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4827): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4844 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4854 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4052:com.osp.app.signin/u0a41 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityThread( 4844): Added TimaKeyStore provider
,D/ActivityThread( 4791): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ActivityThread( 4854): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4880 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=4897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Displayed Component not be shown by security: +1s215ms
W/ActivityManager( 1019): mDVFSHelper.release()
D/ActivityThread( 4897): Added TimaKeyStore provider
,D/ActivityThread( 4880): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 3708:com.android.providers.calendar/u0a42 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4917 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4101:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/ActivityThread( 4917): Added TimaKeyStore provider
,W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,I/ActivityManager( 1019): Killing 4033:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4963 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,D/ActivityThread( 4963): Added TimaKeyStore provider
,W/ActivityThread( 4963): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5002 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5002): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4152:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 4621): Initializing JXcore engine
W/jxcore-log( 4621): JXcore engine is ready
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,W/jxcore-log( 4621): Starting JXcore engine
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 4621): Platform android
W/jxcore-log( 4621): 
,W/jxcore-log( 4621): Process ARCH arm
W/jxcore-log( 4621): 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 4621): JXcore Cordova bridge is ready!
I/jxcore-log( 4621): 
,W/jxcore-log( 4621): JXcore engine is started
,E/jxcore-log( 4621): >> samsung-SM-A500FU
E/jxcore-log( 4621): 
,I/jxcore-log( 4621): Total memory 1983787008
I/jxcore-log( 4621): 
,I/jxcore-log( 4621): Free memory 29757440
I/jxcore-log( 4621): 
I/jxcore-log( 4621): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4621): 
,I/jxcore-log( 4621): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4621): 
,I/jxcore-log( 4621): userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
I/jxcore-log( 4621): 
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 4621): Size 720 1280
I/jxcore-log( 4621): 
,I/jxcore-log( 4621): Screen Brightness 5
I/jxcore-log( 4621): 
,E/jxcore-log( 4621): Dummy Error Log.
E/jxcore-log( 4621): 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5049 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4209:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,D/ActivityThread( 5049): Added TimaKeyStore provider
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{27d633d5 u0 com.sec.bcservice/.BroadcastService}
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2720e9b7 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/ActivityThread( 4759): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4621): getBuffer is called!!!!
I/jxcore-log( 4621): 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{9988e43 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5078 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 5078): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4301:flipboard.app/u0a98 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4186:com.dropbox.android/u0a92 (adj 15): empty #32
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 3657:com.google.android.talk/u0a104 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4408:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5097 uid=10165 gids={50165, 9997} abi=armeabi-v7a,
,D/ActivityThread( 5097): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4424:com.wsomacp/u0a25 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 5113): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4469:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5128 uid=10122 gids={50122, 9997} abi=armeabi-v7a,
I/ActivityManager( 1019): Killing 4507:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityThread( 5128): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4441:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5149 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,D/ActivityThread( 5149): Added TimaKeyStore provider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5178 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4635:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityThread( 5178): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4526:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5193 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/ActivityManager( 1019): Killing 3964:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/ActivityThread( 5193): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.ForceUpdateAlarmReceiver: pid=5214 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1019): Killing 3397:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityThread( 5214): Added TimaKeyStore provider
,V/ActivityThread( 4621): updateVisibility : ActivityRecord{2e247186 token=android.os.BinderProxy@da03dd3 {com.example.hello/com.example.hello.MainActivity}} show : true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5235 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4673:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ActivityThread( 5235): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/ActivityManager( 1019): Display changed displayId=0
,I/ActivityManager( 1019): Process com.sec.android.app.sysscope (pid 3938)(adj 0) has died(77,1099)
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5264 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 5264): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc flipboard.app for broadcast flipboard.app/flipboard.gcm.FlipboardGCMBroadcastReceiver: pid=5304 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5304): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4378:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5381 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5381): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4703:com.sec.pcw.device/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Process com.sec.android.app.wluc (pid 5097)(adj 15) has died(73,1100)
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityThread( 5399): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 5417): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5439 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ActivityThread( 5439): Added TimaKeyStore provider
,I/jxcore-log( 4621): ****TEST TOOK:  5062  ms ****
I/jxcore-log( 4621): 
,I/jxcore-log( 4621): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4621): 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5475 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityThread( 5475): Added TimaKeyStore provider
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 4621:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{2d4d6a6f u0 com.example.hello/.MainActivity t228}
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1019): Killing 4720:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/ActivityManager( 1019): Spurious death for ProcessRecord{14d92712 4621:com.example.hello/u0a174}, curProc for 4621: null
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5501 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1019): Killing 4735:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityThread( 5501): Added TimaKeyStore provider
,W/ActivityThread( 5439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4759:com.google.android.apps.docs/u0a91 (adj 15): empty #31,
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5517): Added TimaKeyStore provider
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5542 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5542): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,I/ActivityManager( 1019): Killing 4017:com.policydm/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5559 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5559): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5577 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1019): Process ACMS.Process (pid 4791)(adj 0) has died(110,1078)
,D/ActivityThread( 5577): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4811:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31


samsung-SM-G900F: 
--------- beginning of main
D/ActivityThread( 3736): Added TimaKeyStore provider
--------- beginning of system
I/ActivityManager(  904): Killing 2788:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
D/ActivityThread( 3747): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3771 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3771): Added TimaKeyStore provider
I/ActivityManager(  904): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3789 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): Process com.sec.android.emergencymode.service (pid 1450)(adj 0) has died(112,674)
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3801 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2860:com.wsomacp/u0a25 (adj 15): bgCount ##41
D/ActivityThread( 3789): Added TimaKeyStore provider
D/ActivityThread( 3801): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2876:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=3835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2891:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
D/ActivityThread( 3820): Added TimaKeyStore provider
D/ActivityThread( 3835): Added TimaKeyStore provider
W/ActivityManager(  904): mDVFSHelper.acquire()
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): Killing 1941:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
I/ActivityManager(  904): Killing 2907:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
D/ActivityThread( 3855): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3871 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ActivityManager(  904): handle home activity for 0
D/ActivityManager(  904): post active user change for 0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=3880 uid=10109 gids={50109, 9997, 1023} abi=armeabi-v7a
D/ActivityThread( 3871): Added TimaKeyStore provider
I/ActivityManager(  904): Killing 2922:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3901 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 3880): Added TimaKeyStore provider
D/ActivityThread( 3901): Added TimaKeyStore provider
I/ActivityManager(  904): Killing 2956:com.sec.android.omc/1000 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.DisasterAlertCommonReceiver: pid=3927 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2971:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
I/ActivityManager(  904): Killing 2990:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3942 uid=10014 gids={50014, 9997} abi=armeabi-v7a
I/ActivityManager(  904): Killing 3021:com.sec.tcpdumpservice/1000 (adj 15): bgCount ##41
D/ActivityThread( 3927): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.app.airwakeupview for broadcast com.samsung.android.app.airwakeupview/.AirWakeupReceiver: pid=3954 uid=10072 gids={50072, 9997, 1028} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2939:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
D/ActivityThread( 3942): Added TimaKeyStore provider
D/ActivityThread( 3954): Added TimaKeyStore provider
I/ActivityManager(  904): Killing 1634:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
I/ActivityManager(  904): Killing 3145:com.android.calendar/u0a150 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
W/ActivityManager(  904): mDVFSHelper.release()
I/ActivityManager(  904): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3973 uid=10185 gids={50185, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3973): Added TimaKeyStore provider
I/ActivityManager(  904): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3989 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 3179:com.android.keychain/1000 (adj 15): bgCount ##41
D/ActivityThread( 3989): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4010 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 3273:com.mobeam.barcodeService/1000 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4010): Added TimaKeyStore provider
I/ActivityManager(  904): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=4026 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ActivityThread( 4026): Added TimaKeyStore provider
I/ActivityManager(  904): Killing 3084:com.samsung.android.securitylogagent/1000 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4050 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/ActivityManager(  904): Killing 3296:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.nearby.mediaserver for broadcast com.samsung.android.nearby.mediaserver/.DMSReceiver: pid=4059 uid=10076 gids={50076, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 2804:com.android.mms/u0a50 (adj 15): bgCount ##41
D/ActivityThread( 4050): Added TimaKeyStore provider
D/ActivityThread( 4059): Added TimaKeyStore provider
W/ActivityManager(  904): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  904): Killing 3351:com.sec.android.app.safetyassurance/u0a52 (adj 15): bgCount ##41
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  904): mDVFSHelper.acquire()
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  904): Killing 3401:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##41
D/ActivityThread( 4102): Added TimaKeyStore provider
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4120): Added TimaKeyStore provider
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4139 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityThread( 3973): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ActivityThread( 4139): Added TimaKeyStore provider
W/ActivityManager(  904): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  904): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager(  904): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  904): Killing 3365:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,D/ActivityThread( 4165): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4207 uid=10027 gids={50027, 9997} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3006:com.sec.modem.settings/1000 (adj 15): bgCount ##41
,W/ActivityManager(  904): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4207): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4226 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  904): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=4244 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3385:com.sec.dsm.system/1000 (adj 15): bgCount ##41
,D/ActivityThread( 4226): Added TimaKeyStore provider
,E/ActivityThread( 4010): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2a4115b6 that was originally bound here
E/ActivityThread( 4010): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2a4115b6 that was originally bound here
E/ActivityThread( 4010): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 4010): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 4010): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 4010): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 4010): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4010): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4010): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4010): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4010): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4010): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4010): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4010): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4010): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4010): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4010): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4010): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  904): Unbind failed: could not find connection for android.os.BinderProxy@8013f85
,D/ActivityThread( 4244): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4267 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,D/ActivityManager(  904): post active user change for 0
,D/ActivityThread( 4267): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 4287): Added TimaKeyStore provider
,I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +873ms
,W/ActivityManager(  904): mDVFSHelper.release()
,I/ActivityManager(  904): Killing 3460:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.MessageNotificationReceiver: pid=4314 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3505:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/ActivityThread( 4314): Added TimaKeyStore provider
,W/jxcore-log( 4139): Initializing JXcore engine
,W/jxcore-log( 4139): JXcore engine is ready
,W/jxcore-log( 4139): Starting JXcore engine
,W/jxcore-log( 4139): Platform android
W/jxcore-log( 4139): 
W/jxcore-log( 4139): Process ARCH arm
W/jxcore-log( 4139): 
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/jxcore-log( 4139): JXcore Cordova bridge is ready!
I/jxcore-log( 4139): 
,W/jxcore-log( 4139): JXcore engine is started
,E/jxcore-log( 4139): >> samsung-SM-G900F
E/jxcore-log( 4139): 
,I/jxcore-log( 4139): Total memory 1787449344
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): Free memory 46346240
I/jxcore-log( 4139): 
I/jxcore-log( 4139): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4139): 
I/jxcore-log( 4139): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): Size 1080 1920
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): Screen Brightness 134
I/jxcore-log( 4139): 
D/ActivityThread( 4374): Added TimaKeyStore provider
,E/jxcore-log( 4139): Dummy Error Log.
E/jxcore-log( 4139): 
,I/ActivityManager(  904): Killing 3522:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4405 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3442:com.google.android.configupdater/u0a92 (adj 15): bgCount ##41
,W/ActivityManager(  904): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ActivityThread( 4405): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4426 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3559:com.sec.android.automotive.drivelinkremote/u0a100 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4435 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 1651:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,D/ActivityThread( 4426): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4435): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.zalando.samsung.provider for broadcast com.zalando.samsung.provider/.PreInstallReceiver: pid=4457 uid=10192 gids={50192, 9997} abi=armeabi-v7a
,D/ActivityThread( 4457): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.LocalFota for broadcast com.LocalFota/.XLFBroadcastReceiver: pid=4478 uid=10120 gids={50120, 9997, 3003, 2001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3589:com.dropbox.android/u0a101 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4478): Added TimaKeyStore provider
,I/jxcore-log( 4139): getBuffer is called!!!!
I/jxcore-log( 4139): 
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4494 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 2371:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/ActivityThread( 4494): Added TimaKeyStore provider
,I/ActivityManager(  904): Process com.sec.factory (pid 3100)(adj 0) has died(56,665)
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4513 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3613:com.samsung.android.scloud.backup/u0a65 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3428:tv.peel.smartremote/u0a171 (adj 15): bgCount ##41
,D/ActivityThread( 4513): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4533 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 2216:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,D/ActivityThread( 4533): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.walkingmate.receiver.WalkingMateReceiver: pid=4551 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3649:org.simalliance.openmobileapi.service/1101 (adj 15): bgCount ##41
,D/ActivityThread( 4551): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4570 uid=10143 gids={50143, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3716:com.fmm.dm/1000 (adj 15): bgCount ##41
,D/ActivityThread( 4570): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4603 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3700:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4603): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4621 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 4621): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=4647 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3736:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4647): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4664 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4664): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4683 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,W/ActivityThread( 4621): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 4683): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 3747:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4720 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 4720): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4780 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3801:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3771:com.sec.factory.camera/1000 (adj 15): bgCount ##42
,D/ActivityThread( 4780): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 3835:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3855:com.sec.usbsettings/1000 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4860 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4860): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4880 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3637:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3820:com.wssnps/1000 (adj 15): bgCount ##42
D/ActivityThread( 4880): Added TimaKeyStore provider
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager(  904): getTasks: caller 10163 does not hold GET_TASKS; limiting output
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4913 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Process com.android.email (pid 4720)(adj 9) has died(60,621)
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4913): Added TimaKeyStore provider
,I/ActivityManager(  904): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4944 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 4944): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 3871:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3880:com.samsung.android.provider.filterprovider/u0a109 (adj 15): bgCount ##41
,I/ActivityManager(  904): Killing 3201:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,I/ActivityManager(  904): Process com.sec.android.app.sns3 (pid 4780)(adj 0) has died(76,627)
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4980 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 4980): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=5012 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3901:com.samsung.android.app.accesscontrol/1000 (adj 15): bgCount ##41
,D/ActivityThread( 5012): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 3927:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,W/ActivityManager(  904): getTasks: caller 10164 does not hold GET_TASKS; limiting output
,I/ActivityManager(  904): Process com.android.exchange (pid 4880)(adj 11) has died(78,636)
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5037 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5037): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=5054 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 3954:com.samsung.android.app.airwakeupview/u0a72 (adj 15): bgCount ##41
,D/ActivityThread( 5054): Added TimaKeyStore provider
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  904): Killing 3942:com.google.android.onetimeinitializer/u0a14 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5080 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 5080): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5100 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,W/ActivityThread( 5080): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4139): ****TEST TOOK:  5085  ms ****
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4139): 
,D/ActivityThread( 5100): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 3989:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,I/ActivityManager(  904): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  904): Killing 4139:com.example.hello/u0a374 (adj 0): stop com.example.hello
,W/ActivityManager(  904): Force removing ActivityRecord{3ec4b64b u0 com.example.hello/.MainActivity t11}: app died, no saved state
,W/ActivityManager(  904): mDVFSHelper.acquire()
,I/ActivityManager(  904): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/ActivityManager(  904): handle home activity for 0
D/ActivityManager(  904): post active user change for 0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=5152 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5152): Added TimaKeyStore provider
,D/ActivityThread( 5159): Added TimaKeyStore provider
,W/ActivityManager(  904): mDVFSHelper.release()
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5193 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 4026:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,D/ActivityThread( 5193): Added TimaKeyStore provider
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=5216 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 1687:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/ActivityThread( 5216): Added TimaKeyStore provider
,I/ActivityManager(  904): Killing 4050:com.android.managedprovisioning/u0a22 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5049 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5049): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
V/ActivityThread( 1460): updateVisibility : ActivityRecord{275d0953 token=android.os.BinderProxy@176f2572 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{346cdae8 u0 com.example.hello/.MainActivity t10}
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5049): updateVisibility : ActivityRecord{238822fb token=android.os.BinderProxy@1cd756f5 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1017): Displayed Component not be shown by security: +652ms (total +720ms)
,W/ActivityManager( 1017): mDVFSHelper.release()
,W/jxcore-log( 5049): Initializing JXcore engine
,W/jxcore-log( 5049): JXcore engine is ready
,W/jxcore-log( 5049): Starting JXcore engine
,W/jxcore-log( 5049): Platform android
W/jxcore-log( 5049): 
W/jxcore-log( 5049): Process ARCH arm,
W/jxcore-log( 5049): 
,I/jxcore-log( 5049): JXcore Cordova bridge is ready!,
I/jxcore-log( 5049): 
W/jxcore-log( 5049): JXcore engine is started
,E/jxcore-log( 5049): >> samsung-SM-A300FU,
E/jxcore-log( 5049): 
,I/jxcore-log( 5049): Total memory 1451114496
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Free memory 27631616
I/jxcore-log( 5049): 
I/jxcore-log( 5049): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): userPath [ 'www' ]
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Size 540 960
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): Screen Brightness 255
I/jxcore-log( 5049): 
,E/jxcore-log( 5049): Dummy Error Log.
E/jxcore-log( 5049): 
,I/jxcore-log( 5049): getBuffer is called!!!!
I/jxcore-log( 5049): 
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{32595474 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5049): ****TEST TOOK:  5071  ms ****
I/jxcore-log( 5049): 
,I/jxcore-log( 5049): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5049): 
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 5049:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{346cdae8 u0 com.example.hello/.MainActivity t10}
,W/ActivityManager( 1017): Spurious death for ProcessRecord{35935d63 5049:com.example.hello/u0a333}, curProc for 5049: null
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5116 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5131 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityThread( 5116): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5131): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5148 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityThread( 5148): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5165): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5183 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityThread( 5183): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5201 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2201
I/ActivityManager(  912): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2213 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
,I/ActivityManager(  912): Displayed com.example.hello/.MainActivity: +237ms
W/jxcore-log( 2213): Initializing JXcore engine
W/jxcore-log( 2213): JXcore engine is ready
W/jxcore-log( 2213): Starting JXcore engine
W/jxcore-log( 2213): Platform android
W/jxcore-log( 2213): 
W/jxcore-log( 2213): Process ARCH arm
W/jxcore-log( 2213): 
I/jxcore-log( 2213): JXcore Cordova bridge is ready!
I/jxcore-log( 2213): 
W/jxcore-log( 2213): JXcore engine is started
E/jxcore-log( 2213): >> HTC-HTC Desire 820
E/jxcore-log( 2213): 
I/jxcore-log( 2213): Total memory 1964650496
I/jxcore-log( 2213): 
I/jxcore-log( 2213): Free memory 833875968
I/jxcore-log( 2213): 
I/jxcore-log( 2213): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2213): 
I/jxcore-log( 2213): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2213): 
I/jxcore-log( 2213): userPath [ 'www' ]
I/jxcore-log( 2213): 
I/jxcore-log( 2213): Size 720 1184
I/jxcore-log( 2213): 
I/jxcore-log( 2213): Screen Brightness 10
I/jxcore-log( 2213): 
E/jxcore-log( 2213): Dummy Error Log.
E/jxcore-log( 2213): 
,I/jxcore-log( 2213): getBuffer is called!!!!
I/jxcore-log( 2213): 
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{423da028 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2258 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2271 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  912): Killing 1812:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1812
,I/ActivityManager(  912): Killing 1856:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  912): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2285 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  912): Recipient 1856
,I/ActivityManager(  912): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2297 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/ActivityManager(  912): Killing 1909:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1909
,I/ActivityManager(  912): Delay finish: com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2318 uid=10016 gids={50016, 3003, 5012, 2001}
,I/ActivityManager(  912): Killing 1263:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1263
,I/ActivityManager(  912): Killing 1921:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,I/ActivityManager(  912): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2345 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  912): Recipient 1921
,I/ActivityManager(  912): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2362 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,I/ActivityManager(  912): Killing 1868:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  912): Killing 1832:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1868
,I/ActivityManager(  912): Recipient 1832
,I/ActivityManager(  912): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/ActivityManager(  912): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2398 uid=10030 gids={50030}
,I/ActivityManager(  912): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Killing 2049:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  912): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2428 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  912): Recipient 2049
,I/ActivityManager(  912): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2440 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  912): Killing 1998:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1998
,I/ActivityManager(  912): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2452 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  912): Killing 2063:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2063
,I/ActivityManager(  912): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2469 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  912): Killing 2081:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2081
,I/ActivityManager(  912): Killing 2103:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2103
,I/ActivityManager(  912): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2481 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  912): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2495 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  912): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  912): Killing 1661:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2511 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  912): Killing 2012:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  912): Killing 2258:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2012
,I/ActivityManager(  912): Recipient 2258
,I/ActivityManager(  912): Recipient 1661
,I/ActivityManager(  912): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2526 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
I/ActivityManager(  912): Killing 2271:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2539 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  912): Killing 2285:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  912): Recipient 2271
,I/ActivityManager(  912): Recipient 2285
,I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/jxcore-log( 2213): ****TEST TOOK:  5045  ms ****
I/jxcore-log( 2213): 
,I/jxcore-log( 2213): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2213): 
I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Killing 2318:com.google.android.configupdater/u0a16 (adj 15): empty #17
I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  912): Recipient 2318
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42398f40 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  912): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  912): Killing 2213:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  912): Force removing ActivityRecord{425d0390 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  912): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  912): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2577 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  912): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2590 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  912): Killing 2345:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2345
,I/ActivityManager(  912): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2605 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  912): Killing 2297:android.process.media/u0a21 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2297
,I/ActivityManager(  912): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=2620 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
I/ActivityManager(  912): Killing 2362:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2362
,I/ActivityManager(  912): Delay finish: com.android.providers.media/.MediaScannerReceiver
,E/ActivityManager(  912): App crashed! Process: android.process.media
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2642 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{426361b0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  912): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2668 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  912): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2683 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,E/ActivityManager(  912): App crashed! Process: com.android.vending
,I/ActivityManager(  912): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2720 uid=10077 gids={50077}
,I/ActivityManager(  912): Killing 2398:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2398
,I/ActivityManager(  912): Killing 1983:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 1983
,I/ActivityManager(  912): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2738 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  912): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2752 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  912): Killing 2428:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2428
,I/ActivityManager(  912): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2766 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,I/ActivityManager(  912): Killing 2440:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 2440


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2652:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2652
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2960
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2996 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +315ms
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3048 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 2664:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2664
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
W/jxcore-log( 2996): Initializing JXcore engine
W/jxcore-log( 2996): JXcore engine is ready
I/ActivityManager(  908): Resuming delayed broadcast
W/jxcore-log( 2996): Starting JXcore engine
I/ActivityManager(  908): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3091 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
W/jxcore-log( 2996): Platform android
W/jxcore-log( 2996): 
W/jxcore-log( 2996): Process ARCH arm
W/jxcore-log( 2996): 
I/jxcore-log( 2996): JXcore Cordova bridge is ready!
I/jxcore-log( 2996): 
W/jxcore-log( 2996): JXcore engine is started
E/jxcore-log( 2996): >> HTC-HTC Desire 820
E/jxcore-log( 2996): 
I/jxcore-log( 2996): Total memory 1964650496
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Free memory 686788608
I/jxcore-log( 2996): 
I/jxcore-log( 2996): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2996): 
I/jxcore-log( 2996): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2996): 
I/jxcore-log( 2996): userPath [ 'www' ]
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Size 720 1184
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Screen Brightness 142
I/jxcore-log( 2996): 
E/jxcore-log( 2996): Dummy Error Log.
E/jxcore-log( 2996): 
I/ActivityManager(  908): Killing 2697:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3130 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3142 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 2731:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2697
,I/ActivityManager(  908): Killing 2679:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3158 uid=10041 gids={50041}
,I/ActivityManager(  908): Recipient 2731
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3174 uid=10078 gids={50078}
,I/ActivityManager(  908): Killing 2460:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2460
,I/ActivityManager(  908): Killing 2767:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2679
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3186 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3201 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  908): Killing 2793:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2793
,I/ActivityManager(  908): Recipient 2767
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3216 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3230 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 2810:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2810
,I/jxcore-log( 2996): getBuffer is called!!!!
I/jxcore-log( 2996): 
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3245 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  908): Killing 2825:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2825
,I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3257 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  908): Killing 2881:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2853:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  908): Recipient 2881
,I/ActivityManager(  908): Recipient 2853
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3269 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2895:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2895
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3285 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3299 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 2908:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  908): Killing 3048:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  908): Recipient 3048,
,I/ActivityManager(  908): Recipient 2908
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3324 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  908): Killing 2865:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2865
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3344 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 3091:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3091
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3361 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3130:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3130
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3379 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3396 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 3142:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3142
,I/ActivityManager(  908): Killing 3186:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3186
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3418 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3437 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  908): Killing 2840:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2840
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/jxcore-log( 2996): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2996): 
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  908): Killing 2996:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{423d35d8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42848998 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  908): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3473 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/ActivityManager(  908): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3510 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  908): Killing 3245:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3245


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  772): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Killing 1532:com.google.android.configupdater/u0a2 (adj 15): empty #17
I/ActivityManager(  772): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2110
I/ActivityManager(  772): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2124 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  772): Killing 1570:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,I/ActivityManager(  772): Displayed com.example.hello/.MainActivity: +281ms
,W/jxcore-log( 2124): Initializing JXcore engine
,W/jxcore-log( 2124): JXcore engine is ready
,W/jxcore-log( 2124): Starting JXcore engine
,W/jxcore-log( 2124): Platform android
W/jxcore-log( 2124): 
,W/jxcore-log( 2124): Process ARCH arm
W/jxcore-log( 2124): 
,I/jxcore-log( 2124): JXcore Cordova bridge is ready!
I/jxcore-log( 2124): 
,W/jxcore-log( 2124): JXcore engine is started
,E/jxcore-log( 2124): >> LGE-Nexus 5
E/jxcore-log( 2124): 
,I/jxcore-log( 2124): Total memory 1945137152
I/jxcore-log( 2124): 
I/jxcore-log( 2124): Free memory 899174400
I/jxcore-log( 2124): 
I/jxcore-log( 2124): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2124): 
,I/jxcore-log( 2124): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2124): 
,I/jxcore-log( 2124): userPath [ 'www' ]
I/jxcore-log( 2124): 
,I/jxcore-log( 2124): Size 1080 1776
I/jxcore-log( 2124): 
,I/jxcore-log( 2124): Screen Brightness 82
I/jxcore-log( 2124): 
,E/jxcore-log( 2124): Dummy Error Log.
E/jxcore-log( 2124): 
,I/jxcore-log( 2124): getBuffer is called!!!!
I/jxcore-log( 2124): 
,I/ActivityManager(  772): Killing 1212:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,I/ActivityManager(  772): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2201 uid=10001 gids={50001, 3003, 1028, 1015}
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Killing 1601:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  772): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2259 uid=10011 gids={50011, 3003}
,I/ActivityManager(  772): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2274 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  772): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2288 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  772): Killing 1690:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  772): Killing 1723:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  772): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  772): Delaying start of: ServiceRecord{43264fd8 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/ActivityManager(  772): Killing 1083:com.android.printspooler/u0a64 (adj 15): empty #17
,I/jxcore-log( 2124): ****TEST TOOK:  5027  ms ****
I/jxcore-log( 2124): 
,I/jxcore-log( 2124): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2124): 
,I/ActivityManager(  772): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  772): Killing 2124:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  772): Force removing ActivityRecord{43342a60 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  772): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2371 uid=10063 gids={50063, 3003, 3002, 1028, 1015}


```


