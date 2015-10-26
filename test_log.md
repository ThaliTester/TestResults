#### Test 47672234e263d5f Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_47672234e263d5f/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }



android : false
```


###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7B59DFE3-4D21-4F61-8B0A-F5AC8F97822D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7B59DFE3-4D21-4F61-8B0A-F5AC8F97822D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F40FDA6C-64E3-4F1D-BB97-EA02BB372BB1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58389"
,(lldb)     command script import "/tmp/7B59DFE3-4D21-4F61-8B0A-F5AC8F97822D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-26 12:24:47.301 HelloWorld[585:470162] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31AF1817-8A48-4EA1-A6F3-08467ACED3EB/Library/Cookies/Cookies.binarycookies
,2015-10-26 12:24:47.679 HelloWorld[585:470162] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-26 12:24:47.680 HelloWorld[585:470162] Multi-tasking -> Device: YES, App: YES
,2015-10-26 12:24:47.684 HelloWorld[585:470162] Unlimited access to network resources
,2015-10-26 12:24:47.689 HelloWorld[585:470162] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-26 12:24:51.750 HelloWorld[585:470162] Resetting plugins due to page load.
,2015-10-26 12:24:52.115 HelloWorld[585:470162] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F40FDA6C-64E3-4F1D-BB97-EA02BB372BB1/HelloWorld.app/www/index.html
,2015-10-26 12:24:52.167 HelloWorld[585:470162] JXcore Cordova plugin initializing
2015-10-26 12:24:52.167 HelloWorld[585:470272] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
Free memory 159518720
execPath /private/var/mobile/Containers/Bundle/Application/F40FDA6C-64E3-4F1D-BB97-EA02BB372BB1/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/F40FDA6C-64E3-4F1D-BB97,-EA02BB372BB1/HelloWorld.app/www/jxcore/
userPath []
2015-10-26 12:24:52.390 HelloWorld[585:470272] Native method ScreenInfo not found.
2015-10-26 12:24:52.391 HelloWorld[585:470272] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5113  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/36734C92-D43F-47F7-8026-FD9020CA7B66/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/36734C92-D43F-47F7-8026-FD9020CA7B66/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/36585545-9E16-4B98-BB5E-1D2850038453/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58393"
,(lldb)     command script import "/tmp/36734C92-D43F-47F7-8026-FD9020CA7B66/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-26 12:25:32.189 HelloWorld[820:60b] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-26 12:25:32.192 HelloWorld[820:60b] Multi-tasking -> Device: YES, App: YES
,2015-10-26 12:25:32.201 HelloWorld[820:60b] Unlimited access to network resources
,2015-10-26 12:25:32.207 HelloWorld[820:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-26 12:25:43.299 HelloWorld[820:60b] Resetting plugins due to page load.
,2015-10-26 12:25:44.152 HelloWorld[820:60b] Finished load of: file:///var/mobile/Applications/36585545-9E16-4B98-BB5E-1D2850038453/HelloWorld.app/www/index.html
,2015-10-26 12:25:44.225 HelloWorld[820:60b] JXcore Cordova plugin initializing
,2015-10-26 12:25:44.227 HelloWorld[820:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 522633216
execPath /private/var/mobile/Applications/36585545-9E16-4B98-BB5E-1D2850038453/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/36585545-9E16-4B98-BB5E-1D2850038453/HelloWorld.app/www/jxcore/
userPath []
,2015-10-26 12:25:44.680 HelloWorld[820:6607] Native method ScreenInfo not found.
,2015-10-26 12:25:44.683 HelloWorld[820:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5231  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CB0E11EF-0900-4703-8321-07B2BA488B0A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CB0E11EF-0900-4703-8321-07B2BA488B0A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A4703305-DEC6-4370-91C2-21E74D55D2B6/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58388"
,(lldb)     command script import "/tmp/CB0E11EF-0900-4703-8321-07B2BA488B0A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-26 12:24:47.770 HelloWorld[1561:1438935] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76075235-5918-4A4C-89E7-1FC8A581E7CB/Library/Cookies/Cookies.binarycookies
,2015-10-26 12:24:48.153 HelloWorld[1561:1438935] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-26 12:24:48.154 HelloWorld[1561:1438935] Multi-tasking -> Device: YES, App: YES
,2015-10-26 12:24:48.157 HelloWorld[1561:1438935] Unlimited access to network resources
,2015-10-26 12:24:48.162 HelloWorld[1561:1438935] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-26 12:24:51.921 HelloWorld[1561:1438935] Resetting plugins due to page load.
,2015-10-26 12:24:52.187 HelloWorld[1561:1438935] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/A4703305-DEC6-4370-91C2-21E74D55D2B6/HelloWorld.app/www/index.html
,2015-10-26 12:24:52.263 HelloWorld[1561:1438935] JXcore Cordova plugin initializing
2015-10-26 12:24:52.264 HelloWorld[1561:1439066] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 137887744
execPath /private/var/mobile/Containers/Bundle/Application/A4703305-DEC6-4370-91C2-21E74D55D2B6/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/A4703305-DEC6-4370-91C2-21E74D55D2B6/HelloWorld.app/www/jxcore/
,userPath []
2015-10-26 12:24:52.532 HelloWorld[1561:1439066] Native method ScreenInfo not found.
2015-10-26 12:24:52.533 HelloWorld[1561:1439066] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5128  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/57D1B4EB-8E6F-4DF8-9303-747D957811A9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/57D1B4EB-8E6F-4DF8-9303-747D957811A9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234e263d5f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C4DF1585-B6E1-40FD-8A25-11066F4BD1BA/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58387"
,(lldb)     command script import "/tmp/57D1B4EB-8E6F-4DF8-9303-747D957811A9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-26 12:24:52.416 HelloWorld[1074:1833823] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E05BE7B7-C7D7-4809-BDE8-8FB51ADC68FE/Library/Cookies/Cookies.binarycookies
,2015-10-26 12:24:52.793 HelloWorld[1074:1833823] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-26 12:24:52.793 HelloWorld[1074:1833823] Multi-tasking -> Device: YES, App: YES
,2015-10-26 12:24:52.802 HelloWorld[1074:1833823] Unlimited access to network resources
,2015-10-26 12:24:52.809 HelloWorld[1074:1833823] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-26 12:25:02.191 HelloWorld[1074:1833823] Resetting plugins due to page load.
,2015-10-26 12:25:05.779 HelloWorld[1074:1833823] Finished load of: file:///var/mobile/Containers/Bundle/Application/C4DF1585-B6E1-40FD-8A25-11066F4BD1BA/HelloWorld.app/www/index.html
,2015-10-26 12:25:05.877 HelloWorld[1074:1833823] JXcore Cordova plugin initializing
,2015-10-26 12:25:05.878 HelloWorld[1074:1834055] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 391135232
,execPath /private/var/mobile/Containers/Bundle/Application/C4DF1585-B6E1-40FD-8A25-11066F4BD1BA/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/C4DF1585-B6E1-40FD-8A25-11066F4BD1BA/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-26 12:25:06.079 HelloWorld[1074:1834055] Native method ScreenInfo not found.
2015-10-26 12:25:06.079 HelloWorld[1074:1834055] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5112  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_47672234e263d5f/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 8095): Initializing JXcore engine
W/jxcore-log( 8095): JXcore engine is ready
,W/jxcore-log( 8095): Starting JXcore engine
,W/jxcore-log( 8095): Platform android
W/jxcore-log( 8095): 
W/jxcore-log( 8095): Process ARCH arm
W/jxcore-log( 8095): 
,I/jxcore-log( 8095): JXcore Cordova bridge is ready!
I/jxcore-log( 8095): 
W/jxcore-log( 8095): JXcore engine is started
,E/jxcore-log( 8095): >> samsung-SM-G920F
E/jxcore-log( 8095): 
,I/jxcore-log( 8095): Total memory 2829074432
I/jxcore-log( 8095): 
I/jxcore-log( 8095): Free memory 176857088
I/jxcore-log( 8095): 
I/jxcore-log( 8095): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8095): 
I/jxcore-log( 8095): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8095): 
,I/jxcore-log( 8095): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 8095): 
,I/jxcore-log( 8095): Size 1440 2560
I/jxcore-log( 8095): 
,I/jxcore-log( 8095): Screen Brightness 255
I/jxcore-log( 8095): 
E/jxcore-log( 8095): Dummy Error Log.
E/jxcore-log( 8095): 
,I/jxcore-log( 8095): getBuffer is called!!!!
I/jxcore-log( 8095): 
,I/jxcore-log( 8095): ****TEST TOOK:  5104  ms ****
I/jxcore-log( 8095): 
,I/jxcore-log( 8095): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8095): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 4152): Initializing JXcore engine
W/jxcore-log( 4152): JXcore engine is ready
W/jxcore-log( 4152): Starting JXcore engine
W/jxcore-log( 4152): Platform android
W/jxcore-log( 4152): 
W/jxcore-log( 4152): Process ARCH arm
W/jxcore-log( 4152): 
I/jxcore-log( 4152): JXcore Cordova bridge is ready!
I/jxcore-log( 4152): 
W/jxcore-log( 4152): JXcore engine is started
E/jxcore-log( 4152): >> samsung-SM-T232
E/jxcore-log( 4152): 
I/jxcore-log( 4152): Total memory 1352024064
I/jxcore-log( 4152): 
I/jxcore-log( 4152): Free memory 225525760
I/jxcore-log( 4152): 
I/jxcore-log( 4152): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4152): 
I/jxcore-log( 4152): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4152): 
I/jxcore-log( 4152): userPath [ 'www' ]
I/jxcore-log( 4152): 
I/jxcore-log( 4152): Size 800 1280
I/jxcore-log( 4152): 
I/jxcore-log( 4152): Screen Brightness 255
I/jxcore-log( 4152): 
E/jxcore-log( 4152): Dummy Error Log.
E/jxcore-log( 4152): 
,I/jxcore-log( 4152): getBuffer is called!!!!
I/jxcore-log( 4152): 
,I/jxcore-log( 4152): ****TEST TOOK:  5112  ms ****
I/jxcore-log( 4152): 
,I/jxcore-log( 4152): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4152): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 8584): Initializing JXcore engine
W/jxcore-log( 8584): JXcore engine is ready
,W/jxcore-log( 8584): Starting JXcore engine
,W/jxcore-log( 8584): Platform android
W/jxcore-log( 8584): 
W/jxcore-log( 8584): Process ARCH arm
W/jxcore-log( 8584): 
,I/jxcore-log( 8584): JXcore Cordova bridge is ready!
I/jxcore-log( 8584): 
,W/jxcore-log( 8584): JXcore engine is started
,E/jxcore-log( 8584): >> LGE-LG-H815
E/jxcore-log( 8584): 
,I/jxcore-log( 8584): Total memory 2968948736
I/jxcore-log( 8584): 
,I/jxcore-log( 8584): Free memory 317280256
I/jxcore-log( 8584): 
I/jxcore-log( 8584): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8584): 
I/jxcore-log( 8584): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8584): 
,I/jxcore-log( 8584): userPath [ 'www' ]
I/jxcore-log( 8584): 
,I/jxcore-log( 8584): Size 1440 2392
I/jxcore-log( 8584): 
,I/jxcore-log( 8584): Screen Brightness 255
I/jxcore-log( 8584): 
,E/jxcore-log( 8584): Dummy Error Log.
E/jxcore-log( 8584): 
,I/jxcore-log( 8584): getBuffer is called!!!!
I/jxcore-log( 8584): 
,I/jxcore-log( 8584): ****TEST TOOK:  5103  ms ****
I/jxcore-log( 8584): 
I/jxcore-log( 8584): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8584): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(16768): Initializing JXcore engine
W/jxcore-log(16768): JXcore engine is ready
W/jxcore-log(16768): Starting JXcore engine
W/jxcore-log(16768): Platform android
W/jxcore-log(16768): 
W/jxcore-log(16768): Process ARCH arm
W/jxcore-log(16768): 
I/jxcore-log(16768): JXcore Cordova bridge is ready!
I/jxcore-log(16768): 
W/jxcore-log(16768): JXcore engine is started
,E/jxcore-log(16768): >> HUAWEI-ALE-L21
E/jxcore-log(16768): 
,I/jxcore-log(16768): Total memory 1949741056
I/jxcore-log(16768): 
,I/jxcore-log(16768): Free memory 126726144
I/jxcore-log(16768): 
I/jxcore-log(16768): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16768): 
I/jxcore-log(16768): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16768): 
,I/jxcore-log(16768): userPath [ 'www' ]
I/jxcore-log(16768): 
,I/jxcore-log(16768): Size 720 1184
I/jxcore-log(16768): 
,I/jxcore-log(16768): Screen Brightness 242
I/jxcore-log(16768): 
,E/jxcore-log(16768): Dummy Error Log.
E/jxcore-log(16768): 
,I/jxcore-log(16768): getBuffer is called!!!!
I/jxcore-log(16768): 
,I/jxcore-log(16768): ****TEST TOOK:  5132  ms ****
I/jxcore-log(16768): 
I/jxcore-log(16768): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16768): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 1610): Initializing JXcore engine
,W/jxcore-log( 1610): JXcore engine is ready
,W/jxcore-log( 1610): Starting JXcore engine
,W/jxcore-log( 1610): Platform android
W/jxcore-log( 1610): 
W/jxcore-log( 1610): Process ARCH arm
W/jxcore-log( 1610): 
,I/jxcore-log( 1610): JXcore Cordova bridge is ready!
I/jxcore-log( 1610): 
,W/jxcore-log( 1610): JXcore engine is started
,E/jxcore-log( 1610): >> LGE-Nexus 5
E/jxcore-log( 1610): 
,I/jxcore-log( 1610): Total memory 1946181632
I/jxcore-log( 1610): 
I/jxcore-log( 1610): Free memory 325144576
I/jxcore-log( 1610): 
I/jxcore-log( 1610): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1610): 
I/jxcore-log( 1610): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1610): 
,I/jxcore-log( 1610): userPath [ 'www' ]
I/jxcore-log( 1610): 
,I/jxcore-log( 1610): Size 1080 1776
I/jxcore-log( 1610): 
,I/jxcore-log( 1610): Screen Brightness 82
I/jxcore-log( 1610): 
,E/jxcore-log( 1610): Dummy Error Log.
E/jxcore-log( 1610): 
,I/jxcore-log( 1610): getBuffer is called!!!!
I/jxcore-log( 1610): 
,I/jxcore-log( 1610): ****TEST TOOK:  5162  ms ****
I/jxcore-log( 1610): 
I/jxcore-log( 1610): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1610): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(29643): Initializing JXcore engine
W/jxcore-log(29643): JXcore engine is ready
W/jxcore-log(29643): Starting JXcore engine
,W/jxcore-log(29643): Platform android
W/jxcore-log(29643): 
W/jxcore-log(29643): Process ARCH arm
W/jxcore-log(29643): 
,I/jxcore-log(29643): JXcore Cordova bridge is ready!
I/jxcore-log(29643): 
W/jxcore-log(29643): JXcore engine is started
,E/jxcore-log(29643): >> LGE-LG-D722
E/jxcore-log(29643): 
I/jxcore-log(29643): Total memory 906309632
I/jxcore-log(29643): 
I/jxcore-log(29643): Free memory 17952768
I/jxcore-log(29643): 
I/jxcore-log(29643): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29643): 
I/jxcore-log(29643): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29643): 
I/jxcore-log(29643): userPath [ 'www' ]
I/jxcore-log(29643): 
,I/jxcore-log(29643): Size 720 1196
I/jxcore-log(29643): 
I/jxcore-log(29643): Screen Brightness 255
I/jxcore-log(29643): 
E/jxcore-log(29643): Dummy Error Log.
E/jxcore-log(29643): 
,I/jxcore-log(29643): getBuffer is called!!!!
I/jxcore-log(29643): 
,I/jxcore-log(29643): ****TEST TOOK:  5107  ms ****
I/jxcore-log(29643): 
,I/jxcore-log(29643): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(29643): 


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
Device test finished on TA4750HV7I 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(29976): Initializing JXcore engine
,W/jxcore-log(29976): JXcore engine is ready
,W/jxcore-log(29976): Starting JXcore engine
,W/jxcore-log(29976): Platform android
W/jxcore-log(29976): 
,W/jxcore-log(29976): Process ARCH arm
W/jxcore-log(29976): 
,I/jxcore-log(29976): JXcore Cordova bridge is ready!
I/jxcore-log(29976): 
,W/jxcore-log(29976): JXcore engine is started
,E/jxcore-log(29976): >> motorola-XT1039
E/jxcore-log(29976): 
,I/jxcore-log(29976): Total memory 893136896
I/jxcore-log(29976): 
I/jxcore-log(29976): Free memory 78979072
I/jxcore-log(29976): 
I/jxcore-log(29976): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29976): 
,I/jxcore-log(29976): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29976): 
,I/jxcore-log(29976): userPath [ 'www' ]
I/jxcore-log(29976): 
,I/jxcore-log(29976): Size 720 1184
I/jxcore-log(29976): 
,I/jxcore-log(29976): Screen Brightness 210
I/jxcore-log(29976): 
,E/jxcore-log(29976): Dummy Error Log.
E/jxcore-log(29976): 
,I/jxcore-log(29976): getBuffer is called!!!!
I/jxcore-log(29976): 
,I/jxcore-log(29976): ****TEST TOOK:  5155  ms ****
I/jxcore-log(29976): 
I/jxcore-log(29976): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(29976): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21462): Initializing JXcore engine
,W/jxcore-log(21462): JXcore engine is ready
,W/jxcore-log(21462): Starting JXcore engine
,W/jxcore-log(21462): Platform android
W/jxcore-log(21462): 
W/jxcore-log(21462): Process ARCH arm
W/jxcore-log(21462): 
,I/jxcore-log(21462): JXcore Cordova bridge is ready!
I/jxcore-log(21462): 
,W/jxcore-log(21462): JXcore engine is started
,E/jxcore-log(21462): >> LGE-LG-D855
E/jxcore-log(21462): 
,I/jxcore-log(21462): Total memory 2995761152
I/jxcore-log(21462): 
,I/jxcore-log(21462): Free memory 462618624
I/jxcore-log(21462): 
I/jxcore-log(21462): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21462): 
I/jxcore-log(21462): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21462): 
,I/jxcore-log(21462): userPath [ 'www' ]
I/jxcore-log(21462): 
,I/jxcore-log(21462): Size 1440 2392
I/jxcore-log(21462): 
,I/jxcore-log(21462): Screen Brightness 177
I/jxcore-log(21462): 
,E/jxcore-log(21462): Dummy Error Log.
E/jxcore-log(21462): 
,I/jxcore-log(21462): getBuffer is called!!!!
I/jxcore-log(21462): 
,I/jxcore-log(21462): ****TEST TOOK:  5207  ms ****
I/jxcore-log(21462): 
I/jxcore-log(21462): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21462): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(25339): Initializing JXcore engine
W/jxcore-log(25339): JXcore engine is ready
W/jxcore-log(25339): Starting JXcore engine
W/jxcore-log(25339): Platform android
W/jxcore-log(25339): 
W/jxcore-log(25339): Process ARCH arm
W/jxcore-log(25339): 
,I/jxcore-log(25339): JXcore Cordova bridge is ready!
I/jxcore-log(25339): 
,W/jxcore-log(25339): JXcore engine is started
,E/jxcore-log(25339): >> samsung-SM-G800F
E/jxcore-log(25339): 
,I/jxcore-log(25339): Total memory 1319530496
I/jxcore-log(25339): 
,I/jxcore-log(25339): Free memory 36896768
I/jxcore-log(25339): 
I/jxcore-log(25339): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25339): 
I/jxcore-log(25339): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25339): 
,I/jxcore-log(25339): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(25339): 
,I/jxcore-log(25339): Size 720 1280
I/jxcore-log(25339): 
,I/jxcore-log(25339): Screen Brightness 255
I/jxcore-log(25339): 
,E/jxcore-log(25339): Dummy Error Log.
E/jxcore-log(25339): 
,I/jxcore-log(25339): getBuffer is called!!!!
I/jxcore-log(25339): 
,I/jxcore-log(25339): ****TEST TOOK:  5133  ms ****
I/jxcore-log(25339): 
,I/jxcore-log(25339): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25339): 


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Device test finished on f56ad48d 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(27316): Initializing JXcore engine
,W/jxcore-log(27316): JXcore engine is ready
,W/jxcore-log(27316): Starting JXcore engine
,W/jxcore-log(27316): Platform android
W/jxcore-log(27316): 
W/jxcore-log(27316): Process ARCH arm
W/jxcore-log(27316): 
,I/jxcore-log(27316): JXcore Cordova bridge is ready!
I/jxcore-log(27316): 
,W/jxcore-log(27316): JXcore engine is started
,E/jxcore-log(27316): >> motorola-XT1072
E/jxcore-log(27316): 
,I/jxcore-log(27316): Total memory 916258816
I/jxcore-log(27316): 
I/jxcore-log(27316): Free memory 54591488
I/jxcore-log(27316): 
I/jxcore-log(27316): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27316): 
I/jxcore-log(27316): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27316): 
,I/jxcore-log(27316): userPath [ 'www' ]
I/jxcore-log(27316): 
,I/jxcore-log(27316): Size 720 1184
I/jxcore-log(27316): 
,I/jxcore-log(27316): Screen Brightness 82
I/jxcore-log(27316): 
,E/jxcore-log(27316): Dummy Error Log.
E/jxcore-log(27316): 
,I/jxcore-log(27316): getBuffer is called!!!!
I/jxcore-log(27316): 
,I/jxcore-log(27316): ****TEST TOOK:  5295  ms ****
I/jxcore-log(27316): 
,I/jxcore-log(27316): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27316): 


samsung-SM-N910C: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 9587): Initializing JXcore engine
W/jxcore-log( 9587): JXcore engine is ready
W/jxcore-log( 9587): Starting JXcore engine
,W/jxcore-log( 9587): Platform android
W/jxcore-log( 9587): 
W/jxcore-log( 9587): Process ARCH arm
W/jxcore-log( 9587): 
,I/jxcore-log( 9587): JXcore Cordova bridge is ready!
I/jxcore-log( 9587): 
,W/jxcore-log( 9587): JXcore engine is started
,E/jxcore-log( 9587): >> samsung-SM-N910C
E/jxcore-log( 9587): 
,I/jxcore-log( 9587): Total memory 2971066368
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): Free memory 259846144
I/jxcore-log( 9587): 
I/jxcore-log( 9587): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9587): 
I/jxcore-log( 9587): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): Size 1440 2560
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): Screen Brightness 134
I/jxcore-log( 9587): 
,E/jxcore-log( 9587): Dummy Error Log.
E/jxcore-log( 9587): 
,I/jxcore-log( 9587): getBuffer is called!!!!
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): ****TEST TOOK:  5182  ms ****
I/jxcore-log( 9587): 
,I/jxcore-log( 9587): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9587): 


samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16849): Initializing JXcore engine
W/jxcore-log(16849): JXcore engine is ready
,W/jxcore-log(16849): Starting JXcore engine
,W/jxcore-log(16849): Platform android,
W/jxcore-log(16849): 
W/jxcore-log(16849): Process ARCH arm
W/jxcore-log(16849): 
,I/jxcore-log(16849): JXcore Cordova bridge is ready!,
I/jxcore-log(16849): 
W/jxcore-log(16849): JXcore engine is started
,E/jxcore-log(16849): >> samsung-SM-A500FU
E/jxcore-log(16849): 
,I/jxcore-log(16849): Total memory 1983787008
I/jxcore-log(16849): 
,I/jxcore-log(16849): Free memory 363266048
I/jxcore-log(16849): 
,I/jxcore-log(16849): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16849): 
I/jxcore-log(16849): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16849): 
,I/jxcore-log(16849): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16849): 
,I/jxcore-log(16849): Size 720 1280
I/jxcore-log(16849): 
,I/jxcore-log(16849): Screen Brightness 255
I/jxcore-log(16849): 
,E/jxcore-log(16849): Dummy Error Log.
E/jxcore-log(16849): 
,I/jxcore-log(16849): getBuffer is called!!!!
I/jxcore-log(16849): 
,I/jxcore-log(16849): ****TEST TOOK:  5067  ms ****
I/jxcore-log(16849): 
,I/jxcore-log(16849): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16849): 


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6934): Initializing JXcore engine
W/jxcore-log( 6934): JXcore engine is ready
W/jxcore-log( 6934): Starting JXcore engine
,W/jxcore-log( 6934): Platform android
W/jxcore-log( 6934): 
W/jxcore-log( 6934): Process ARCH arm
W/jxcore-log( 6934): 
I/jxcore-log( 6934): JXcore Cordova bridge is ready!
I/jxcore-log( 6934): 
W/jxcore-log( 6934): JXcore engine is started
E/jxcore-log( 6934): >> samsung-SM-G900F
E/jxcore-log( 6934): 
I/jxcore-log( 6934): Total memory 1787449344
I/jxcore-log( 6934): 
I/jxcore-log( 6934): Free memory 50241536
I/jxcore-log( 6934): 
I/jxcore-log( 6934): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6934): 
I/jxcore-log( 6934): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6934): 
I/jxcore-log( 6934): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6934): 
I/jxcore-log( 6934): Size 1080 1920
I/jxcore-log( 6934): 
I/jxcore-log( 6934): Screen Brightness 255
I/jxcore-log( 6934): 
E/jxcore-log( 6934): Dummy Error Log.
E/jxcore-log( 6934): 
I/jxcore-log( 6934): getBuffer is called!!!!
I/jxcore-log( 6934): 
,I/jxcore-log( 6934): ****TEST TOOK:  5203  ms ****
I/jxcore-log( 6934): 
,I/jxcore-log( 6934): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6934): 


```

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on ZX1G429CRK 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(10657): Initializing JXcore engine
,W/jxcore-log(10657): JXcore engine is ready
,W/jxcore-log(10657): Starting JXcore engine,
,W/jxcore-log(10657): Platform android,
W/jxcore-log(10657): 
W/jxcore-log(10657): Process ARCH arm
W/jxcore-log(10657): 
,I/jxcore-log(10657): JXcore Cordova bridge is ready!,
I/jxcore-log(10657): 
W/jxcore-log(10657): JXcore engine is started
,E/jxcore-log(10657): >> HTC-HTC One_M8,
E/jxcore-log(10657): 
,I/jxcore-log(10657): Total memory 1912020992
I/jxcore-log(10657): 
,I/jxcore-log(10657): Free memory 383688704
I/jxcore-log(10657): 
I/jxcore-log(10657): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10657): 
I/jxcore-log(10657): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10657): 
,I/jxcore-log(10657): userPath [ 'www' ],
I/jxcore-log(10657): 
,I/jxcore-log(10657): Size 1080 1776
I/jxcore-log(10657): 
,I/jxcore-log(10657): Screen Brightness 142
I/jxcore-log(10657): ,
E/jxcore-log(10657): Dummy Error Log.
E/jxcore-log(10657): 
,I/jxcore-log(10657): getBuffer is called!!!!,
I/jxcore-log(10657): 
,I/jxcore-log(10657): ****TEST TOOK:  5147  ms ****
I/jxcore-log(10657): 
I/jxcore-log(10657): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10657): 


samsung-SM-N9005: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(24524): Initializing JXcore engine
W/jxcore-log(24524): JXcore engine is ready
W/jxcore-log(24524): Starting JXcore engine
,W/jxcore-log(24524): Platform android
W/jxcore-log(24524): 
,W/jxcore-log(24524): Process ARCH arm
W/jxcore-log(24524): 
,I/jxcore-log(24524): JXcore Cordova bridge is ready!
I/jxcore-log(24524): 
,W/jxcore-log(24524): JXcore engine is started
,E/jxcore-log(24524): >> samsung-SM-N9005
E/jxcore-log(24524): 
,I/jxcore-log(24524): Total memory 2971471872
I/jxcore-log(24524): 
,I/jxcore-log(24524): Free memory 297984000
I/jxcore-log(24524): 
I/jxcore-log(24524): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24524): 
I/jxcore-log(24524): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24524): 
,I/jxcore-log(24524): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(24524): 
,I/jxcore-log(24524): Size 1080 1920
I/jxcore-log(24524): 
,I/jxcore-log(24524): Screen Brightness 255
I/jxcore-log(24524): 
,E/jxcore-log(24524): Dummy Error Log.
E/jxcore-log(24524): 
,I/jxcore-log(24524): getBuffer is called!!!!
I/jxcore-log(24524): 
,I/jxcore-log(24524): ****TEST TOOK:  5160  ms ****
I/jxcore-log(24524): 
,I/jxcore-log(24524): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24524): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(27005): Initializing JXcore engine
,W/jxcore-log(27005): JXcore engine is ready
W/jxcore-log(27005): Starting JXcore engine
,W/jxcore-log(27005): Platform android
W/jxcore-log(27005): 
W/jxcore-log(27005): Process ARCH arm
W/jxcore-log(27005): 
,I/jxcore-log(27005): JXcore Cordova bridge is ready!
I/jxcore-log(27005): 
,W/jxcore-log(27005): JXcore engine is started
,E/jxcore-log(27005): >> motorola-Nexus 6
E/jxcore-log(27005): 
,I/jxcore-log(27005): Total memory 3114405888
I/jxcore-log(27005): 
,I/jxcore-log(27005): Free memory 535007232
I/jxcore-log(27005): 
,I/jxcore-log(27005): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27005): 
I/jxcore-log(27005): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27005): 
I/jxcore-log(27005): userPath [ 'www' ]
I/jxcore-log(27005): 
I/jxcore-log(27005): Size 1440 2392
I/jxcore-log(27005): 
,I/jxcore-log(27005): Screen Brightness 82
I/jxcore-log(27005): 
,E/jxcore-log(27005): Dummy Error Log.
E/jxcore-log(27005): 
,I/jxcore-log(27005): getBuffer is called!!!!
I/jxcore-log(27005): 
,I/jxcore-log(27005): ****TEST TOOK:  5174  ms ****
I/jxcore-log(27005): 
,I/jxcore-log(27005): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27005): 


```

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(10476): Initializing JXcore engine
W/jxcore-log(10476): JXcore engine is ready
W/jxcore-log(10476): Starting JXcore engine
W/jxcore-log(10476): Platform android
W/jxcore-log(10476): 
W/jxcore-log(10476): Process ARCH arm
W/jxcore-log(10476): 
I/jxcore-log(10476): JXcore Cordova bridge is ready!
I/jxcore-log(10476): 
W/jxcore-log(10476): JXcore engine is started
E/jxcore-log(10476): >> HTC-HTC One M8s
E/jxcore-log(10476): 
I/jxcore-log(10476): Total memory 1931808768
I/jxcore-log(10476): 
I/jxcore-log(10476): Free memory 218562560
I/jxcore-log(10476): 
I/jxcore-log(10476): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10476): 
I/jxcore-log(10476): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10476): 
I/jxcore-log(10476): userPath [ 'www' ]
I/jxcore-log(10476): 
I/jxcore-log(10476): Size 1080 1776
I/jxcore-log(10476): 
I/jxcore-log(10476): Screen Brightness 142
I/jxcore-log(10476): 
E/jxcore-log(10476): Dummy Error Log.
E/jxcore-log(10476): 
I/jxcore-log(10476): getBuffer is called!!!!
I/jxcore-log(10476): 
,I/jxcore-log(10476): ****TEST TOOK:  5094  ms ****
I/jxcore-log(10476): 
,I/jxcore-log(10476): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10476): 


samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(20600): Initializing JXcore engine
,W/jxcore-log(20600): JXcore engine is ready
,W/jxcore-log(20600): Starting JXcore engine
,W/jxcore-log(20600): Platform android
W/jxcore-log(20600): 
W/jxcore-log(20600): Process ARCH arm
W/jxcore-log(20600): 
,I/jxcore-log(20600): JXcore Cordova bridge is ready!
I/jxcore-log(20600): 
,W/jxcore-log(20600): JXcore engine is started
,E/jxcore-log(20600): >> samsung-SM-A300FU
E/jxcore-log(20600): 
,I/jxcore-log(20600): Total memory 1451114496
I/jxcore-log(20600): 
,I/jxcore-log(20600): Free memory 192626688
I/jxcore-log(20600): 
,I/jxcore-log(20600): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20600): 
I/jxcore-log(20600): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20600): 
,I/jxcore-log(20600): userPath [ 'www' ]
I/jxcore-log(20600): 
,I/jxcore-log(20600): Size 540 960
I/jxcore-log(20600): 
,I/jxcore-log(20600): Screen Brightness 160
I/jxcore-log(20600): 
,E/jxcore-log(20600): Dummy Error Log.
E/jxcore-log(20600): 
,I/jxcore-log(20600): getBuffer is called!!!!
I/jxcore-log(20600): 
,I/jxcore-log(20600): ****TEST TOOK:  5086  ms ****
I/jxcore-log(20600): 
,I/jxcore-log(20600): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20600): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
W/jxcore-log(32464): Initializing JXcore engine
W/jxcore-log(32464): JXcore engine is ready
W/jxcore-log(32464): Starting JXcore engine
W/jxcore-log(32464): Platform android
W/jxcore-log(32464): 
W/jxcore-log(32464): Process ARCH arm
W/jxcore-log(32464): 
I/jxcore-log(32464): JXcore Cordova bridge is ready!
I/jxcore-log(32464): 
W/jxcore-log(32464): JXcore engine is started
E/jxcore-log(32464): >> LGE-LG-D802
E/jxcore-log(32464): 
I/jxcore-log(32464): Total memory 1943035904
I/jxcore-log(32464): 
I/jxcore-log(32464): Free memory 231706624
I/jxcore-log(32464): 
I/jxcore-log(32464): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32464): 
I/jxcore-log(32464): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32464): 
I/jxcore-log(32464): userPath [ 'www' ]
I/jxcore-log(32464): 
I/jxcore-log(32464): Size 1080 1776
I/jxcore-log(32464): 
I/jxcore-log(32464): Screen Brightness 255
I/jxcore-log(32464): 
E/jxcore-log(32464): Dummy Error Log.
E/jxcore-log(32464): 
,I/jxcore-log(32464): getBuffer is called!!!!
I/jxcore-log(32464): 
,I/jxcore-log(32464): ****TEST TOOK:  5120  ms ****
I/jxcore-log(32464): 
,I/jxcore-log(32464): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32464): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6952): Initializing JXcore engine
W/jxcore-log( 6952): JXcore engine is ready
,W/jxcore-log( 6952): Starting JXcore engine
,W/jxcore-log( 6952): Platform android
W/jxcore-log( 6952): 
W/jxcore-log( 6952): Process ARCH arm
W/jxcore-log( 6952): 
,I/jxcore-log( 6952): JXcore Cordova bridge is ready!
I/jxcore-log( 6952): 
,W/jxcore-log( 6952): JXcore engine is started
,E/jxcore-log( 6952): >> samsung-SM-A500FU
E/jxcore-log( 6952): 
,I/jxcore-log( 6952): Total memory 1983787008
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): Free memory 270446592
I/jxcore-log( 6952): 
I/jxcore-log( 6952): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): Size 720 1280
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): Screen Brightness 255
I/jxcore-log( 6952): 
,E/jxcore-log( 6952): Dummy Error Log.
E/jxcore-log( 6952): 
,I/jxcore-log( 6952): getBuffer is called!!!!
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 6952): 
,I/jxcore-log( 6952): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6952): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 5938): Initializing JXcore engine
W/jxcore-log( 5938): JXcore engine is ready
,W/jxcore-log( 5938): Starting JXcore engine
,W/jxcore-log( 5938): Platform android
W/jxcore-log( 5938): 
,W/jxcore-log( 5938): Process ARCH arm
W/jxcore-log( 5938): 
,I/jxcore-log( 5938): JXcore Cordova bridge is ready!
I/jxcore-log( 5938): 
,W/jxcore-log( 5938): JXcore engine is started
,E/jxcore-log( 5938): >> samsung-SM-G900F
E/jxcore-log( 5938): 
,I/jxcore-log( 5938): Total memory 1787449344
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): Free memory 89812992
I/jxcore-log( 5938): 
I/jxcore-log( 5938): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5938): 
I/jxcore-log( 5938): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): Size 1080 1920
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): Screen Brightness 134
I/jxcore-log( 5938): 
,E/jxcore-log( 5938): Dummy Error Log.
E/jxcore-log( 5938): 
,I/jxcore-log( 5938): getBuffer is called!!!!
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): ****TEST TOOK:  5202  ms ****
I/jxcore-log( 5938): 
,I/jxcore-log( 5938): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5938): 


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
,--------- beginning of main
,W/jxcore-log(11632): Initializing JXcore engine
,W/jxcore-log(11632): JXcore engine is ready
,W/jxcore-log(11632): Starting JXcore engine,
,W/jxcore-log(11632): Platform android
W/jxcore-log(11632): 
W/jxcore-log(11632): Process ARCH arm
W/jxcore-log(11632): 
,I/jxcore-log(11632): JXcore Cordova bridge is ready!,
I/jxcore-log(11632): 
W/jxcore-log(11632): JXcore engine is started
,E/jxcore-log(11632): >> samsung-SM-A300FU
E/jxcore-log(11632): 
,I/jxcore-log(11632): Total memory 1451114496
I/jxcore-log(11632): 
,I/jxcore-log(11632): Free memory 217178112
I/jxcore-log(11632): 
I/jxcore-log(11632): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11632): 
I/jxcore-log(11632): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11632): 
,I/jxcore-log(11632): userPath [ 'www' ]
I/jxcore-log(11632): 
,I/jxcore-log(11632): Size 540 960
I/jxcore-log(11632): 
,I/jxcore-log(11632): Screen Brightness 255
I/jxcore-log(11632): 
,E/jxcore-log(11632): Dummy Error Log.
E/jxcore-log(11632): 
,I/jxcore-log(11632): getBuffer is called!!!!
I/jxcore-log(11632): 
,I/jxcore-log(11632): ****TEST TOOK:  5086  ms ****
I/jxcore-log(11632): 
,I/jxcore-log(11632): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11632): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(28483): Initializing JXcore engine
W/jxcore-log(28483): JXcore engine is ready
W/jxcore-log(28483): Starting JXcore engine
W/jxcore-log(28483): Platform android
W/jxcore-log(28483): 
W/jxcore-log(28483): Process ARCH arm
W/jxcore-log(28483): 
I/jxcore-log(28483): JXcore Cordova bridge is ready!
I/jxcore-log(28483): 
W/jxcore-log(28483): JXcore engine is started
E/jxcore-log(28483): >> HTC-HTC Desire 820
E/jxcore-log(28483): 
I/jxcore-log(28483): Total memory 1964650496
I/jxcore-log(28483): 
I/jxcore-log(28483): Free memory 226381824
I/jxcore-log(28483): 
I/jxcore-log(28483): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28483): 
I/jxcore-log(28483): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28483): 
I/jxcore-log(28483): userPath [ 'www' ]
I/jxcore-log(28483): 
I/jxcore-log(28483): Size 720 1184
I/jxcore-log(28483): 
I/jxcore-log(28483): Screen Brightness 10
I/jxcore-log(28483): 
E/jxcore-log(28483): Dummy Error Log.
E/jxcore-log(28483): 
,I/jxcore-log(28483): getBuffer is called!!!!
I/jxcore-log(28483): 
,I/jxcore-log(28483): ****TEST TOOK:  5180  ms ****
I/jxcore-log(28483): 
I/jxcore-log(28483): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28483): 


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(23121): Initializing JXcore engine
,W/jxcore-log(23121): JXcore engine is ready
,W/jxcore-log(23121): Starting JXcore engine
,W/jxcore-log(23198): Initializing JXcore engine
,W/jxcore-log(23198): JXcore engine is ready
,W/jxcore-log(23198): Starting JXcore engine
,W/jxcore-log(23198): Platform android
W/jxcore-log(23198): 
,W/jxcore-log(23198): Process ARCH arm
W/jxcore-log(23198): 
,I/jxcore-log(23198): JXcore Cordova bridge is ready!
I/jxcore-log(23198): 
,W/jxcore-log(23198): JXcore engine is started
,E/jxcore-log(23198): >> LGE-Nexus 5
E/jxcore-log(23198): 
,I/jxcore-log(23198): Total memory 1945137152
I/jxcore-log(23198): 
I/jxcore-log(23198): Free memory 45256704
I/jxcore-log(23198): 
I/jxcore-log(23198): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23198): 
,I/jxcore-log(23198): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23198): 
,I/jxcore-log(23198): userPath [ 'www' ]
I/jxcore-log(23198): 
,I/jxcore-log(23198): Size 1080 1776
I/jxcore-log(23198): 
,I/jxcore-log(23198): Screen Brightness 82
I/jxcore-log(23198): 
,E/jxcore-log(23198): Dummy Error Log.
E/jxcore-log(23198): 
,W/jxcore-log(23329): Initializing JXcore engine
,W/jxcore-log(23329): JXcore engine is ready
,W/jxcore-log(23329): Starting JXcore engine
,W/jxcore-log(23437): Initializing JXcore engine
,W/jxcore-log(23437): JXcore engine is ready
,W/jxcore-log(23437): Starting JXcore engine
,W/jxcore-log(23437): Platform android
W/jxcore-log(23437): 
,W/jxcore-log(23437): Process ARCH arm
W/jxcore-log(23437): 
,I/jxcore-log(23437): JXcore Cordova bridge is ready!
I/jxcore-log(23437): 
,W/jxcore-log(23437): JXcore engine is started
,E/jxcore-log(23437): >> LGE-Nexus 5
E/jxcore-log(23437): 
,I/jxcore-log(23437): Total memory 1945137152
I/jxcore-log(23437): 
I/jxcore-log(23437): Free memory 41283584
I/jxcore-log(23437): 
I/jxcore-log(23437): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23437): 
,I/jxcore-log(23437): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23437): 
,I/jxcore-log(23437): userPath [ 'www' ]
I/jxcore-log(23437): 
,I/jxcore-log(23437): Size 1080 1776
I/jxcore-log(23437): 
,I/jxcore-log(23437): Screen Brightness 82
I/jxcore-log(23437): 
,E/jxcore-log(23437): Dummy Error Log.
E/jxcore-log(23437): 
,W/jxcore-log(23521): Initializing JXcore engine
,W/jxcore-log(23521): JXcore engine is ready
,W/jxcore-log(23521): Starting JXcore engine
,W/jxcore-log(23521): Platform android
W/jxcore-log(23521): 
,W/jxcore-log(23521): Process ARCH arm
W/jxcore-log(23521): 
,I/jxcore-log(23521): JXcore Cordova bridge is ready!
I/jxcore-log(23521): 
,W/jxcore-log(23521): JXcore engine is started
,E/jxcore-log(23521): >> LGE-Nexus 5
E/jxcore-log(23521): 
,I/jxcore-log(23521): Total memory 1945137152
I/jxcore-log(23521): 
I/jxcore-log(23521): Free memory 47366144
I/jxcore-log(23521): 
I/jxcore-log(23521): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23521): 
,I/jxcore-log(23521): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23521): 
,I/jxcore-log(23521): userPath [ 'www' ]
I/jxcore-log(23521): 
,I/jxcore-log(23521): Size 1080 1776
I/jxcore-log(23521): 
,I/jxcore-log(23521): Screen Brightness 82
I/jxcore-log(23521): 
,E/jxcore-log(23521): Dummy Error Log.
E/jxcore-log(23521): 
,I/jxcore-log(23521): getBuffer is called!!!!
I/jxcore-log(23521): 
,W/jxcore-log(23677): Initializing JXcore engine
,W/jxcore-log(23677): JXcore engine is ready
,W/jxcore-log(23677): Starting JXcore engine
,W/jxcore-log(23677): Platform android
W/jxcore-log(23677): 
,W/jxcore-log(23677): Process ARCH arm
W/jxcore-log(23677): 
,I/jxcore-log(23677): JXcore Cordova bridge is ready!
I/jxcore-log(23677): 
,W/jxcore-log(23677): JXcore engine is started
,E/jxcore-log(23677): >> LGE-Nexus 5
E/jxcore-log(23677): 
,I/jxcore-log(23677): Total memory 1945137152
I/jxcore-log(23677): 
I/jxcore-log(23677): Free memory 42143744
I/jxcore-log(23677): 
I/jxcore-log(23677): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23677): 
,I/jxcore-log(23677): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23677): 
,I/jxcore-log(23677): userPath [ 'www' ]
I/jxcore-log(23677): 
,I/jxcore-log(23677): Size 1080 1776
I/jxcore-log(23677): 
,I/jxcore-log(23677): Screen Brightness 82
I/jxcore-log(23677): 
,E/jxcore-log(23677): Dummy Error Log.
E/jxcore-log(23677): 
,I/jxcore-log(23677): getBuffer is called!!!!
I/jxcore-log(23677): 
,W/jxcore-log(23836): Initializing JXcore engine
,W/jxcore-log(23836): JXcore engine is ready
,W/jxcore-log(23836): Starting JXcore engine
,W/jxcore-log(23836): Platform android
W/jxcore-log(23836): 
,W/jxcore-log(23836): Process ARCH arm
W/jxcore-log(23836): 
,I/jxcore-log(23836): JXcore Cordova bridge is ready!
I/jxcore-log(23836): 
,W/jxcore-log(23836): JXcore engine is started
,E/jxcore-log(23836): >> LGE-Nexus 5
E/jxcore-log(23836): 
,I/jxcore-log(23836): Total memory 1945137152
I/jxcore-log(23836): 
I/jxcore-log(23836): Free memory 51355648
I/jxcore-log(23836): 
I/jxcore-log(23836): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23836): 
,I/jxcore-log(23836): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23836): 
,I/jxcore-log(23836): userPath [ 'www' ]
I/jxcore-log(23836): 
,I/jxcore-log(23836): Size 1080 1776
I/jxcore-log(23836): 
,I/jxcore-log(23836): Screen Brightness 82
I/jxcore-log(23836): 
,E/jxcore-log(23836): Dummy Error Log.
E/jxcore-log(23836): 
,I/jxcore-log(23836): getBuffer is called!!!!
I/jxcore-log(23836): 
,W/jxcore-log(24199): Initializing JXcore engine
,W/jxcore-log(24199): JXcore engine is ready
,W/jxcore-log(24199): Starting JXcore engine
,W/jxcore-log(24199): Platform android
W/jxcore-log(24199): 
,W/jxcore-log(24199): Process ARCH arm
W/jxcore-log(24199): 
,I/jxcore-log(24199): JXcore Cordova bridge is ready!
I/jxcore-log(24199): 
,W/jxcore-log(24199): JXcore engine is started
,E/jxcore-log(24199): >> LGE-Nexus 5
E/jxcore-log(24199): 
,I/jxcore-log(24199): Total memory 1945137152
I/jxcore-log(24199): 
I/jxcore-log(24199): Free memory 43188224
I/jxcore-log(24199): 
I/jxcore-log(24199): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24199): 
,I/jxcore-log(24199): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24199): 
,I/jxcore-log(24199): userPath [ 'www' ]
I/jxcore-log(24199): 
,I/jxcore-log(24199): Size 1080 1776
I/jxcore-log(24199): 
,I/jxcore-log(24199): Screen Brightness 82
I/jxcore-log(24199): 
,E/jxcore-log(24199): Dummy Error Log.
E/jxcore-log(24199): 
,W/jxcore-log(24363): Initializing JXcore engine
,W/jxcore-log(24363): JXcore engine is ready
,W/jxcore-log(24363): Starting JXcore engine
,W/jxcore-log(24363): Platform android
W/jxcore-log(24363): 
,W/jxcore-log(24363): Process ARCH arm
W/jxcore-log(24363): 
,I/jxcore-log(24363): JXcore Cordova bridge is ready!
I/jxcore-log(24363): 
,W/jxcore-log(24363): JXcore engine is started
,W/jxcore-log(24473): Initializing JXcore engine
,W/jxcore-log(24473): JXcore engine is ready
,W/jxcore-log(24473): Starting JXcore engine
,W/jxcore-log(24473): Platform android
W/jxcore-log(24473): 
,W/jxcore-log(24473): Process ARCH arm
W/jxcore-log(24473): 
,I/jxcore-log(24473): JXcore Cordova bridge is ready!
I/jxcore-log(24473): 
W/jxcore-log(24473): JXcore engine is started
,E/jxcore-log(24473): >> LGE-Nexus 5
E/jxcore-log(24473): 
,I/jxcore-log(24473): Total memory 1945137152
I/jxcore-log(24473): 
I/jxcore-log(24473): Free memory 47722496
I/jxcore-log(24473): 
I/jxcore-log(24473): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24473): 
I/jxcore-log(24473): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24473): 
I/jxcore-log(24473): userPath [ 'www' ]
I/jxcore-log(24473): 
I/jxcore-log(24473): Size 1080 1776
I/jxcore-log(24473): 
I/jxcore-log(24473): Screen Brightness 82
I/jxcore-log(24473): 
E/jxcore-log(24473): Dummy Error Log.
E/jxcore-log(24473): 
,W/jxcore-log(24733): Initializing JXcore engine
,W/jxcore-log(24733): JXcore engine is ready
,W/jxcore-log(24733): Starting JXcore engine
,W/jxcore-log(24733): Platform android
W/jxcore-log(24733): 
,W/jxcore-log(24733): Process ARCH arm
W/jxcore-log(24733): 
,I/jxcore-log(24733): JXcore Cordova bridge is ready!
I/jxcore-log(24733): 
,W/jxcore-log(24733): JXcore engine is started
,E/jxcore-log(24733): >> LGE-Nexus 5
E/jxcore-log(24733): 
,I/jxcore-log(24733): Total memory 1945137152
I/jxcore-log(24733): 
I/jxcore-log(24733): Free memory 44646400
I/jxcore-log(24733): 
I/jxcore-log(24733): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24733): 
,I/jxcore-log(24733): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24733): 
,I/jxcore-log(24733): userPath [ 'www' ]
I/jxcore-log(24733): 
,I/jxcore-log(24733): Size 1080 1776
I/jxcore-log(24733): 
,I/jxcore-log(24733): Screen Brightness 82
I/jxcore-log(24733): 
,E/jxcore-log(24733): Dummy Error Log.
E/jxcore-log(24733): 
,W/jxcore-log(25025): Initializing JXcore engine
,W/jxcore-log(25025): JXcore engine is ready
,W/jxcore-log(25025): Starting JXcore engine
,W/jxcore-log(25025): Platform android
W/jxcore-log(25025): 
,W/jxcore-log(25025): Process ARCH arm
W/jxcore-log(25025): 
,I/jxcore-log(25025): JXcore Cordova bridge is ready!
I/jxcore-log(25025): 
,W/jxcore-log(25025): JXcore engine is started
,E/jxcore-log(25025): >> LGE-Nexus 5
E/jxcore-log(25025): 
,I/jxcore-log(25025): Total memory 1945137152
I/jxcore-log(25025): 
I/jxcore-log(25025): Free memory 45670400
I/jxcore-log(25025): 
I/jxcore-log(25025): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25025): 
,I/jxcore-log(25025): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25025): 
,I/jxcore-log(25025): userPath [ 'www' ]
I/jxcore-log(25025): 
,I/jxcore-log(25025): Size 1080 1776
I/jxcore-log(25025): 
,I/jxcore-log(25025): Screen Brightness 82
I/jxcore-log(25025): 
,E/jxcore-log(25025): Dummy Error Log.
E/jxcore-log(25025): 
,W/jxcore-log(25253): Initializing JXcore engine
,W/jxcore-log(25253): JXcore engine is ready
,W/jxcore-log(25253): Starting JXcore engine
,W/jxcore-log(25253): Platform android
W/jxcore-log(25253): 
,W/jxcore-log(25253): Process ARCH arm
W/jxcore-log(25253): 
,I/jxcore-log(25253): JXcore Cordova bridge is ready!
I/jxcore-log(25253): 
,W/jxcore-log(25253): JXcore engine is started
,E/jxcore-log(25253): >> LGE-Nexus 5
E/jxcore-log(25253): 
,I/jxcore-log(25253): Total memory 1945137152
I/jxcore-log(25253): 
I/jxcore-log(25253): Free memory 41930752
I/jxcore-log(25253): 
I/jxcore-log(25253): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25253): 
,I/jxcore-log(25253): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25253): 
,I/jxcore-log(25253): userPath [ 'www' ]
I/jxcore-log(25253): 
,I/jxcore-log(25253): Size 1080 1776
I/jxcore-log(25253): 
,I/jxcore-log(25253): Screen Brightness 82
I/jxcore-log(25253): 
,E/jxcore-log(25253): Dummy Error Log.
E/jxcore-log(25253): 
,W/jxcore-log(25505): Initializing JXcore engine
W/jxcore-log(25505): JXcore engine is ready
,W/jxcore-log(25505): Starting JXcore engine
,W/jxcore-log(25505): Platform android
W/jxcore-log(25505): 
,W/jxcore-log(25505): Process ARCH arm
W/jxcore-log(25505): 
,I/jxcore-log(25505): JXcore Cordova bridge is ready!
I/jxcore-log(25505): 
,W/jxcore-log(25505): JXcore engine is started
,E/jxcore-log(25505): >> LGE-Nexus 5
E/jxcore-log(25505): 
,I/jxcore-log(25505): Total memory 1945137152
I/jxcore-log(25505): 
I/jxcore-log(25505): Free memory 45625344
I/jxcore-log(25505): 
I/jxcore-log(25505): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25505): 
,I/jxcore-log(25505): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25505): 
,I/jxcore-log(25505): userPath [ 'www' ]
I/jxcore-log(25505): 
,I/jxcore-log(25505): Size 1080 1776
I/jxcore-log(25505): 
,I/jxcore-log(25505): Screen Brightness 82
I/jxcore-log(25505): 
,E/jxcore-log(25505): Dummy Error Log.
E/jxcore-log(25505): 
,W/jxcore-log(25604): Initializing JXcore engine
,W/jxcore-log(25604): JXcore engine is ready
,W/jxcore-log(25604): Starting JXcore engine
,W/jxcore-log(25604): Platform android
W/jxcore-log(25604): 
,W/jxcore-log(25604): Process ARCH arm
W/jxcore-log(25604): 
,I/jxcore-log(25604): JXcore Cordova bridge is ready!
I/jxcore-log(25604): 
,W/jxcore-log(25604): JXcore engine is started
,E/jxcore-log(25604): >> LGE-Nexus 5
E/jxcore-log(25604): 
,I/jxcore-log(25604): Total memory 1945137152
I/jxcore-log(25604): 
I/jxcore-log(25604): Free memory 42098688
I/jxcore-log(25604): 
I/jxcore-log(25604): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25604): 
,I/jxcore-log(25604): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25604): 
,I/jxcore-log(25604): userPath [ 'www' ]
I/jxcore-log(25604): 
,I/jxcore-log(25604): Size 1080 1776
I/jxcore-log(25604): 
,I/jxcore-log(25604): Screen Brightness 82
I/jxcore-log(25604): 
E/jxcore-log(25604): Dummy Error Log.
E/jxcore-log(25604): 
,W/jxcore-log(25664): Initializing JXcore engine
,W/jxcore-log(25664): JXcore engine is ready
,W/jxcore-log(25664): Starting JXcore engine
,W/jxcore-log(25664): Platform android
W/jxcore-log(25664): 
,W/jxcore-log(25664): Process ARCH arm
W/jxcore-log(25664): 
,I/jxcore-log(25664): JXcore Cordova bridge is ready!
I/jxcore-log(25664): 
,W/jxcore-log(25664): JXcore engine is started
,E/jxcore-log(25664): >> LGE-Nexus 5
E/jxcore-log(25664): 
,I/jxcore-log(25664): Total memory 1945137152
I/jxcore-log(25664): 
I/jxcore-log(25664): Free memory 46919680
I/jxcore-log(25664): 
I/jxcore-log(25664): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25664): 
,I/jxcore-log(25664): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25664): 
,I/jxcore-log(25664): userPath [ 'www' ]
I/jxcore-log(25664): 
,I/jxcore-log(25664): Size 1080 1776
I/jxcore-log(25664): 
,I/jxcore-log(25664): Screen Brightness 82
I/jxcore-log(25664): 
,E/jxcore-log(25664): Dummy Error Log.
E/jxcore-log(25664): 
,I/jxcore-log(25664): getBuffer is called!!!!
I/jxcore-log(25664): 
,W/jxcore-log(25809): Initializing JXcore engine
,W/jxcore-log(25809): JXcore engine is ready
,W/jxcore-log(25809): Starting JXcore engine
,W/jxcore-log(25939): Initializing JXcore engine
,W/jxcore-log(25939): JXcore engine is ready
,W/jxcore-log(25939): Starting JXcore engine
,W/jxcore-log(25939): Platform android
W/jxcore-log(25939): 
,W/jxcore-log(25939): Process ARCH arm
W/jxcore-log(25939): 
,I/jxcore-log(25939): JXcore Cordova bridge is ready!
I/jxcore-log(25939): 
,W/jxcore-log(25939): JXcore engine is started
,E/jxcore-log(25939): >> LGE-Nexus 5
E/jxcore-log(25939): 
,I/jxcore-log(25939): Total memory 1945137152
I/jxcore-log(25939): 
I/jxcore-log(25939): Free memory 53846016
I/jxcore-log(25939): 
I/jxcore-log(25939): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25939): 
,I/jxcore-log(25939): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25939): 
,I/jxcore-log(25939): userPath [ 'www' ]
I/jxcore-log(25939): 
,I/jxcore-log(25939): Size 1080 1776
I/jxcore-log(25939): 
I/jxcore-log(25939): Screen Brightness 82
I/jxcore-log(25939): 
,E/jxcore-log(25939): Dummy Error Log.
E/jxcore-log(25939): 
,I/jxcore-log(25939): getBuffer is called!!!!
I/jxcore-log(25939): 
,I/jxcore-log(25939): ****TEST TOOK:  5024  ms ****
I/jxcore-log(25939): 
,I/jxcore-log(25939): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25939): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(27848): Initializing JXcore engine
,W/jxcore-log(27848): JXcore engine is ready
,W/jxcore-log(27848): Starting JXcore engine
,W/jxcore-log(27848): Platform android
W/jxcore-log(27848): 
,W/jxcore-log(27848): Process ARCH arm
W/jxcore-log(27848): 
,I/jxcore-log(27848): JXcore Cordova bridge is ready!
I/jxcore-log(27848): 
,W/jxcore-log(27848): JXcore engine is started
,E/jxcore-log(27848): >> HTC-HTC Desire 820
E/jxcore-log(27848): 
,I/jxcore-log(27848): Total memory 1964650496
I/jxcore-log(27848): 
I/jxcore-log(27848): Free memory 248926208
I/jxcore-log(27848): 
I/jxcore-log(27848): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27848): 
,I/jxcore-log(27848): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27848): 
,I/jxcore-log(27848): userPath [ 'www' ]
I/jxcore-log(27848): 
,I/jxcore-log(27848): Size 720 1184
I/jxcore-log(27848): 
,I/jxcore-log(27848): Screen Brightness 142
I/jxcore-log(27848): 
,E/jxcore-log(27848): Dummy Error Log.
E/jxcore-log(27848): 
,I/jxcore-log(27848): getBuffer is called!!!!
I/jxcore-log(27848): 
,I/jxcore-log(27848): ****TEST TOOK:  5175  ms ****
I/jxcore-log(27848): 
,I/jxcore-log(27848): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27848): 


```


