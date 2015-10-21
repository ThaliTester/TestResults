#### Test 482277757fbcadc Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_482277757fbcadc/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }



android : false
```


###iOS Logs

```
Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6F4E8704-6DBC-4552-B2D5-B93B0DBF9CF4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6F4E8704-6DBC-4552-B2D5-B93B0DBF9CF4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/A9A9B94E-7A02-4A2B-8BB6-4151182728CC/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49628"
,(lldb)     command script import "/tmp/6F4E8704-6DBC-4552-B2D5-B93B0DBF9CF4/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 16:46:10.556 HelloWorld[550:60b] Apache Cordova native platform version 3.9.1 is starting.
2015-10-21 16:46:10.561 HelloWorld[550:60b] Multi-tasking -> Device: YES, App: YES
2015-10-21 16:46:10.566 HelloWorld[550:60b] Unlimited access to network resources
,2015-10-21 16:46:10.573 HelloWorld[550:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 16:46:21.660 HelloWorld[550:60b] Resetting plugins due to page load.
,2015-10-21 16:46:22.443 HelloWorld[550:60b] Finished load of: file:///var/mobile/Applications/A9A9B94E-7A02-4A2B-8BB6-4151182728CC/HelloWorld.app/www/index.html
,2015-10-21 16:46:22.506 HelloWorld[550:60b] JXcore Cordova plugin initializing
,2015-10-21 16:46:22.508 HelloWorld[550:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 612470784
execPath /private/var/mobile/Applications/A9A9B94E-7A02-4A2B-8BB6-4151182728CC/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/A9A9B94E-7A02-4A2B-8BB6-4151182728CC/HelloWor,ld.app/www/jxcore/
userPath []
,2015-10-21 16:46:22.955 HelloWorld[550:6607] Native method ScreenInfo not found.
,2015-10-21 16:46:22.958 HelloWorld[550:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5224  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/15984FD4-77F3-40CE-BA6A-7F4B587CA972/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/15984FD4-77F3-40CE-BA6A-7F4B587CA972/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A4363F34-D4DC-4ABA-B63E-947E620F301D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49623"
,(lldb)     command script import "/tmp/15984FD4-77F3-40CE-BA6A-7F4B587CA972/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 16:45:24.611 HelloWorld[1051:855433] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B453AC59-0555-4318-A9E9-3778BD80FBBA/Library/Cookies/Cookies.binarycookies
,2015-10-21 16:45:24.990 HelloWorld[1051:855433] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-21 16:45:24.991 HelloWorld[1051:855433] Multi-tasking -> Device: YES, App: YES
,2015-10-21 16:45:24.994 HelloWorld[1051:855433] Unlimited access to network resources
,2015-10-21 16:45:24.999 HelloWorld[1051:855433] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 16:45:28.626 HelloWorld[1051:855433] Resetting plugins due to page load.
,2015-10-21 16:45:28.975 HelloWorld[1051:855433] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/A4363F34-D4DC-4ABA-B63E-947E620F301D/HelloWorld.app/www/index.html
,2015-10-21 16:45:29.015 HelloWorld[1051:855433] JXcore Cordova plugin initializing
2015-10-21 16:45:29.015 HelloWorld[1051:855570] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
,Free memory 121344000
,execPath /private/var/mobile/Containers/Bundle/Application/A4363F34-D4DC-4ABA-B63E-947E620F301D/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/A4363F34-D4DC-4ABA-B63E-947E620F301D/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-21 16:45:29.218 HelloWorld[1051:855570] Native method ScreenInfo not found.
,2015-10-21 16:45:29.220 HelloWorld[1051:855570] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5104  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E9D3359C-B922-45E4-9637-E2D9F3FC4C2D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E9D3359C-B922-45E4-9637-E2D9F3FC4C2D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B63E5AB-8B06-47A7-B4C7-FBCBDEAFBFCB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49625"
,(lldb)     command script import "/tmp/E9D3359C-B922-45E4-9637-E2D9F3FC4C2D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 16:45:24.341 HelloWorld[970:848255] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B31FE304-731E-45AF-9A42-D0FE3B431EAC/Library/Cookies/Cookies.binarycookies
,2015-10-21 16:45:24.725 HelloWorld[970:848255] Apache Cordova native platform version 3.9.1 is starting.
2015-10-21 16:45:24.727 HelloWorld[970:848255] Multi-tasking -> Device: YES, App: YES
,2015-10-21 16:45:24.730 HelloWorld[970:848255] Unlimited access to network resources
,2015-10-21 16:45:24.736 HelloWorld[970:848255] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 16:45:28.577 HelloWorld[970:848255] Resetting plugins due to page load.
,2015-10-21 16:45:28.964 HelloWorld[970:848255] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/2B63E5AB-8B06-47A7-B4C7-FBCBDEAFBFCB/HelloWorld.app/www/index.html
,2015-10-21 16:45:29.006 HelloWorld[970:848255] JXcore Cordova plugin initializing
2015-10-21 16:45:29.007 HelloWorld[970:848383] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
,Free memory 129458176
,execPath /private/var/mobile/Containers/Bundle/Application/2B63E5AB-8B06-47A7-B4C7-FBCBDEAFBFCB/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/2B63E5AB-8B06-47A7-B4C7-FBCBDEAFBFCB/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-21 16:45:29.236 HelloWorld[970:848383] Native method ScreenInfo not found.
,2015-10-21 16:45:29.238 HelloWorld[970:848383] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5114  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D5C30CFF-9458-4555-A159-CBA31A1A5FE0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D5C30CFF-9458-4555-A159-CBA31A1A5FE0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/482277757fbcadc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8E93A532-76EA-4FAF-8E55-799CB7FA1964/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49622"
,(lldb)     command script import "/tmp/D5C30CFF-9458-4555-A159-CBA31A1A5FE0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 16:45:28.572 HelloWorld[754:1076719] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1B378F47-E618-4EB9-A4A5-0283E9AE325B/Library/Cookies/Cookies.binarycookies
,2015-10-21 16:45:28.958 HelloWorld[754:1076719] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-21 16:45:28.959 HelloWorld[754:1076719] Multi-tasking -> Device: YES, App: YES
,2015-10-21 16:45:28.968 HelloWorld[754:1076719] Unlimited access to network resources
,2015-10-21 16:45:28.975 HelloWorld[754:1076719] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 16:45:38.185 HelloWorld[754:1076719] Resetting plugins due to page load.
,2015-10-21 16:45:41.520 HelloWorld[754:1076719] Finished load of: file:///var/mobile/Containers/Bundle/Application/8E93A532-76EA-4FAF-8E55-799CB7FA1964/HelloWorld.app/www/index.html
,2015-10-21 16:45:41.607 HelloWorld[754:1076719] JXcore Cordova plugin initializing
,2015-10-21 16:45:41.608 HelloWorld[754:1076941] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 424525824
,execPath /private/var/mobile/Containers/Bundle/Application/8E93A532-76EA-4FAF-8E55-799CB7FA1964/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/8E93A532-76EA-4FAF-8E55-799CB7FA1964/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-21 16:45:41.803 HelloWorld[754:1076941] Native method ScreenInfo not found.
2015-10-21 16:45:41.803 HelloWorld[754:1076941] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5114  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_482277757fbcadc/Sub/serverApp/index.js',
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
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(20024): Initializing JXcore engine
W/jxcore-log(20024): JXcore engine is ready
,W/jxcore-log(20024): Starting JXcore engine
,W/jxcore-log(20024): Platform android
W/jxcore-log(20024): 
W/jxcore-log(20024): Process ARCH arm
W/jxcore-log(20024): 
,I/jxcore-log(20024): JXcore Cordova bridge is ready!
I/jxcore-log(20024): 
W/jxcore-log(20024): JXcore engine is started
,E/jxcore-log(20024): >> samsung-SM-G920F
E/jxcore-log(20024): 
,I/jxcore-log(20024): Total memory 2829074432
I/jxcore-log(20024): 
I/jxcore-log(20024): Free memory 100188160
I/jxcore-log(20024): 
I/jxcore-log(20024): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20024): 
I/jxcore-log(20024): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20024): 
,I/jxcore-log(20024): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(20024): 
,I/jxcore-log(20024): Size 1440 2560
I/jxcore-log(20024): 
,I/jxcore-log(20024): Screen Brightness 255
I/jxcore-log(20024): 
E/jxcore-log(20024): Dummy Error Log.
E/jxcore-log(20024): 
,I/jxcore-log(20024): getBuffer is called!!!!
I/jxcore-log(20024): 
,I/jxcore-log(20024): ****TEST TOOK:  5054  ms ****
I/jxcore-log(20024): 
,I/jxcore-log(20024): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20024): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(20989): Initializing JXcore engine
W/jxcore-log(20989): JXcore engine is ready
W/jxcore-log(20989): Starting JXcore engine
,W/jxcore-log(20989): Platform android
W/jxcore-log(20989): 
,W/jxcore-log(20989): Process ARCH arm
W/jxcore-log(20989): 
,I/jxcore-log(20989): JXcore Cordova bridge is ready!
I/jxcore-log(20989): 
,W/jxcore-log(20989): JXcore engine is started
,E/jxcore-log(20989): >> samsung-SM-T232
E/jxcore-log(20989): 
,I/jxcore-log(20989): Total memory 1352024064
I/jxcore-log(20989): 
I/jxcore-log(20989): Free memory 148512768
I/jxcore-log(20989): 
,I/jxcore-log(20989): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20989): 
,I/jxcore-log(20989): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20989): 
,I/jxcore-log(20989): userPath [ 'www' ]
I/jxcore-log(20989): 
,I/jxcore-log(20989): Size 800 1280
I/jxcore-log(20989): 
,I/jxcore-log(20989): Screen Brightness 255
I/jxcore-log(20989): 
,E/jxcore-log(20989): Dummy Error Log.
E/jxcore-log(20989): 
,I/jxcore-log(20989): getBuffer is called!!!!
I/jxcore-log(20989): 
,I/jxcore-log(20989): ****TEST TOOK:  5083  ms ****
I/jxcore-log(20989): 
,I/jxcore-log(20989): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20989): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(18930): Initializing JXcore engine
W/jxcore-log(18930): JXcore engine is ready
W/jxcore-log(18930): Starting JXcore engine
W/jxcore-log(18930): Platform android
W/jxcore-log(18930): 
W/jxcore-log(18930): Process ARCH arm
W/jxcore-log(18930): 
I/jxcore-log(18930): JXcore Cordova bridge is ready!
I/jxcore-log(18930): 
W/jxcore-log(18930): JXcore engine is started
E/jxcore-log(18930): >> LGE-LG-H815
E/jxcore-log(18930): 
I/jxcore-log(18930): Total memory 2968948736
I/jxcore-log(18930): 
I/jxcore-log(18930): Free memory 343617536
I/jxcore-log(18930): 
I/jxcore-log(18930): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18930): 
I/jxcore-log(18930): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18930): 
I/jxcore-log(18930): userPath [ 'www' ]
I/jxcore-log(18930): 
I/jxcore-log(18930): Size 1440 2392
I/jxcore-log(18930): 
I/jxcore-log(18930): Screen Brightness 255
I/jxcore-log(18930): 
E/jxcore-log(18930): Dummy Error Log.
E/jxcore-log(18930): 
I/jxcore-log(18930): getBuffer is called!!!!
I/jxcore-log(18930): 
,I/jxcore-log(18930): ****TEST TOOK:  5049  ms ****
I/jxcore-log(18930): 
,I/jxcore-log(18930): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18930): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(18333): Initializing JXcore engine
W/jxcore-log(18333): JXcore engine is ready
,W/jxcore-log(18333): Starting JXcore engine
,W/jxcore-log(18333): Platform android
W/jxcore-log(18333): 
W/jxcore-log(18333): Process ARCH arm
W/jxcore-log(18333): 
,I/jxcore-log(18333): JXcore Cordova bridge is ready!
I/jxcore-log(18333): 
W/jxcore-log(18333): JXcore engine is started
,E/jxcore-log(18333): >> HUAWEI-ALE-L21
E/jxcore-log(18333): 
,I/jxcore-log(18333): Total memory 1949741056
I/jxcore-log(18333): 
,I/jxcore-log(18333): Free memory 37531648
I/jxcore-log(18333): 
I/jxcore-log(18333): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18333): 
I/jxcore-log(18333): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18333): 
,I/jxcore-log(18333): userPath [ 'www' ]
I/jxcore-log(18333): 
,I/jxcore-log(18333): Size 720 1184
I/jxcore-log(18333): 
,I/jxcore-log(18333): Screen Brightness 242
I/jxcore-log(18333): 
E/jxcore-log(18333): Dummy Error Log.
E/jxcore-log(18333): 
,I/jxcore-log(18333): getBuffer is called!!!!
I/jxcore-log(18333): 
,I/jxcore-log(18333): ****TEST TOOK:  5077  ms ****
I/jxcore-log(18333): 
,I/jxcore-log(18333): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18333): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(19676): Initializing JXcore engine
W/jxcore-log(19676): JXcore engine is ready
,W/jxcore-log(19676): Starting JXcore engine
,W/jxcore-log(19676): Platform android
W/jxcore-log(19676): 
W/jxcore-log(19676): Process ARCH arm
W/jxcore-log(19676): 
,I/jxcore-log(19676): JXcore Cordova bridge is ready!
I/jxcore-log(19676): 
W/jxcore-log(19676): JXcore engine is started
,E/jxcore-log(19676): >> LGE-Nexus 5
E/jxcore-log(19676): 
I/jxcore-log(19676): Total memory 1946181632
I/jxcore-log(19676): 
I/jxcore-log(19676): Free memory 375988224
I/jxcore-log(19676): 
I/jxcore-log(19676): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19676): 
I/jxcore-log(19676): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19676): 
I/jxcore-log(19676): userPath [ 'www' ]
I/jxcore-log(19676): 
,I/jxcore-log(19676): Size 1080 1776
I/jxcore-log(19676): 
,I/jxcore-log(19676): Screen Brightness 82
I/jxcore-log(19676): 
E/jxcore-log(19676): Dummy Error Log.
E/jxcore-log(19676): 
,I/jxcore-log(19676): getBuffer is called!!!!
I/jxcore-log(19676): 
,I/jxcore-log(19676): ****TEST TOOK:  5157  ms ****
I/jxcore-log(19676): 
I/jxcore-log(19676): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19676): 
,--------- beginning of crash


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(30455): Initializing JXcore engine
W/jxcore-log(30455): JXcore engine is ready
W/jxcore-log(30455): Starting JXcore engine
W/jxcore-log(30455): Platform android
W/jxcore-log(30455): 
W/jxcore-log(30455): Process ARCH arm
W/jxcore-log(30455): 
I/jxcore-log(30455): JXcore Cordova bridge is ready!
I/jxcore-log(30455): 
W/jxcore-log(30455): JXcore engine is started
,E/jxcore-log(30455): >> LGE-LG-D722
E/jxcore-log(30455): 
,I/jxcore-log(30455): Total memory 906309632
I/jxcore-log(30455): 
I/jxcore-log(30455): Free memory 19656704
I/jxcore-log(30455): 
I/jxcore-log(30455): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30455): 
I/jxcore-log(30455): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30455): 
I/jxcore-log(30455): userPath [ 'www' ]
I/jxcore-log(30455): 
I/jxcore-log(30455): Size 720 1196
I/jxcore-log(30455): 
I/jxcore-log(30455): Screen Brightness 255
I/jxcore-log(30455): 
,E/jxcore-log(30455): Dummy Error Log.
E/jxcore-log(30455): 
,I/jxcore-log(30455): getBuffer is called!!!!
I/jxcore-log(30455): 
,I/jxcore-log(30455): ****TEST TOOK:  5260  ms ****
I/jxcore-log(30455): 
,I/jxcore-log(30455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30455): 


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 2199): Initializing JXcore engine
,W/jxcore-log( 2199): JXcore engine is ready
,W/jxcore-log( 2199): Starting JXcore engine
,W/jxcore-log( 2199): Platform android
W/jxcore-log( 2199): 
,W/jxcore-log( 2199): Process ARCH arm
W/jxcore-log( 2199): 
,I/jxcore-log( 2199): JXcore Cordova bridge is ready!
I/jxcore-log( 2199): 
,W/jxcore-log( 2199): JXcore engine is started
,E/jxcore-log( 2199): >> motorola-XT1039
E/jxcore-log( 2199): 
,I/jxcore-log( 2199): Total memory 893136896
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): Free memory 57651200
I/jxcore-log( 2199): 
I/jxcore-log( 2199): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): userPath [ 'www' ]
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): Size 720 1184
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): Screen Brightness 210
I/jxcore-log( 2199): 
,E/jxcore-log( 2199): Dummy Error Log.
E/jxcore-log( 2199): 
,I/jxcore-log( 2199): getBuffer is called!!!!
I/jxcore-log( 2199): 
,I/jxcore-log( 2199): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 2199): 
I/jxcore-log( 2199): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2199): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 5376): Initializing JXcore engine,
,W/jxcore-log( 5376): JXcore engine is ready
W/jxcore-log( 5376): Starting JXcore engine
,W/jxcore-log( 5376): Platform android
W/jxcore-log( 5376): 
,W/jxcore-log( 5376): Process ARCH arm
W/jxcore-log( 5376): 
,I/jxcore-log( 5376): JXcore Cordova bridge is ready!
I/jxcore-log( 5376): 
,W/jxcore-log( 5376): JXcore engine is started
,E/jxcore-log( 5376): >> LGE-LG-D855
E/jxcore-log( 5376): 
,I/jxcore-log( 5376): Total memory 2995761152
I/jxcore-log( 5376): 
I/jxcore-log( 5376): Free memory 245055488
I/jxcore-log( 5376): 
I/jxcore-log( 5376): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5376): 
I/jxcore-log( 5376): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5376): 
I/jxcore-log( 5376): userPath [ 'www' ]
I/jxcore-log( 5376): 
I/jxcore-log( 5376): Size 1440 2392
I/jxcore-log( 5376): 
I/jxcore-log( 5376): Screen Brightness 177
I/jxcore-log( 5376): 
E/jxcore-log( 5376): Dummy Error Log.
E/jxcore-log( 5376): 
I/jxcore-log( 5376): getBuffer is called!!!!
I/jxcore-log( 5376): 
,I/jxcore-log( 5376): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 5376): 
I/jxcore-log( 5376): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5376): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(21013): Initializing JXcore engine
,W/jxcore-log(21013): JXcore engine is ready
,W/jxcore-log(21013): Starting JXcore engine
,W/jxcore-log(21013): Platform android
W/jxcore-log(21013): 
W/jxcore-log(21013): Process ARCH arm
W/jxcore-log(21013): 
I/jxcore-log(21013): JXcore Cordova bridge is ready!
I/jxcore-log(21013): 
W/jxcore-log(21013): JXcore engine is started
E/jxcore-log(21013): >> samsung-SM-G800F
E/jxcore-log(21013): 
I/jxcore-log(21013): Total memory 1319530496
I/jxcore-log(21013): 
I/jxcore-log(21013): Free memory 37101568
I/jxcore-log(21013): 
I/jxcore-log(21013): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21013): 
I/jxcore-log(21013): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21013): 
I/jxcore-log(21013): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(21013): 
I/jxcore-log(21013): Size 720 1280
I/jxcore-log(21013): 
I/jxcore-log(21013): Screen Brightness 255
I/jxcore-log(21013): 
E/jxcore-log(21013): Dummy Error Log.
E/jxcore-log(21013): 
,I/jxcore-log(21013): getBuffer is called!!!!
I/jxcore-log(21013): 
,I/jxcore-log(21013): ****TEST TOOK:  5103  ms ****
I/jxcore-log(21013): 
,I/jxcore-log(21013): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21013): 


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on f56ad48d 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13915): Initializing JXcore engine
W/jxcore-log(13915): JXcore engine is ready
,W/jxcore-log(13915): Starting JXcore engine
,W/jxcore-log(13915): Platform android
W/jxcore-log(13915): 
,W/jxcore-log(13915): Process ARCH arm
W/jxcore-log(13915): 
,I/jxcore-log(13915): JXcore Cordova bridge is ready!
I/jxcore-log(13915): 
,W/jxcore-log(13915): JXcore engine is started
,E/jxcore-log(13915): >> motorola-XT1072
E/jxcore-log(13915): 
,I/jxcore-log(13915): Total memory 916258816
I/jxcore-log(13915): 
I/jxcore-log(13915): Free memory 71053312
I/jxcore-log(13915): 
,I/jxcore-log(13915): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13915): 
,I/jxcore-log(13915): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13915): 
,I/jxcore-log(13915): userPath [ 'www' ]
I/jxcore-log(13915): 
I/jxcore-log(13915): Size 720 1184
I/jxcore-log(13915): 
I/jxcore-log(13915): Screen Brightness 82
I/jxcore-log(13915): 
,E/jxcore-log(13915): Dummy Error Log.
E/jxcore-log(13915): 
,I/jxcore-log(13915): getBuffer is called!!!!
I/jxcore-log(13915): 
,I/jxcore-log(13915): ****TEST TOOK:  5056  ms ****
I/jxcore-log(13915): 
,I/jxcore-log(13915): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13915): 


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(25687): Initializing JXcore engine,
W/jxcore-log(25687): JXcore engine is ready
,W/jxcore-log(25687): Starting JXcore engine
,W/jxcore-log(25687): Platform android
W/jxcore-log(25687): 
W/jxcore-log(25687): Process ARCH arm
W/jxcore-log(25687): 
I/jxcore-log(25687): JXcore Cordova bridge is ready!
I/jxcore-log(25687): 
W/jxcore-log(25687): JXcore engine is started
E/jxcore-log(25687): >> samsung-SM-N910C
E/jxcore-log(25687): 
I/jxcore-log(25687): Total memory 2971066368
I/jxcore-log(25687): 
I/jxcore-log(25687): Free memory 325914624
I/jxcore-log(25687): 
I/jxcore-log(25687): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25687): 
I/jxcore-log(25687): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25687): 
I/jxcore-log(25687): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(25687): 
I/jxcore-log(25687): Size 1440 2560
I/jxcore-log(25687): 
I/jxcore-log(25687): Screen Brightness 134
I/jxcore-log(25687): 
E/jxcore-log(25687): Dummy Error Log.
E/jxcore-log(25687): 
,I/jxcore-log(25687): getBuffer is called!!!!
I/jxcore-log(25687): 
,I/jxcore-log(25687): ****TEST TOOK:  5037  ms ****
I/jxcore-log(25687): 
,I/jxcore-log(25687): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25687): 


samsung-SM-A500FU: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(20203): Initializing JXcore engine
,W/jxcore-log(20203): JXcore engine is ready
,W/jxcore-log(20203): Starting JXcore engine,
,W/jxcore-log(20203): Platform android,
W/jxcore-log(20203): 
W/jxcore-log(20203): Process ARCH arm
W/jxcore-log(20203): 
,I/jxcore-log(20203): JXcore Cordova bridge is ready!,
I/jxcore-log(20203): 
W/jxcore-log(20203): JXcore engine is started
,E/jxcore-log(20203): >> samsung-SM-A500FU
E/jxcore-log(20203): 
,I/jxcore-log(20203): Total memory 1983787008
I/jxcore-log(20203): 
,I/jxcore-log(20203): Free memory 365023232
I/jxcore-log(20203): 
,I/jxcore-log(20203): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20203): 
I/jxcore-log(20203): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20203): 
,I/jxcore-log(20203): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(20203): 
,I/jxcore-log(20203): Size 720 1280
I/jxcore-log(20203): 
,I/jxcore-log(20203): Screen Brightness 255
I/jxcore-log(20203): 
,E/jxcore-log(20203): Dummy Error Log.
E/jxcore-log(20203): 
,I/jxcore-log(20203): getBuffer is called!!!!
I/jxcore-log(20203): 
,I/jxcore-log(20203): ****TEST TOOK:  5036  ms ****
I/jxcore-log(20203): 
,I/jxcore-log(20203): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20203): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(16751): Initializing JXcore engine
W/jxcore-log(16751): JXcore engine is ready
W/jxcore-log(16751): Starting JXcore engine
W/jxcore-log(16751): Platform android
W/jxcore-log(16751): 
W/jxcore-log(16751): Process ARCH arm
W/jxcore-log(16751): 
I/jxcore-log(16751): JXcore Cordova bridge is ready!
I/jxcore-log(16751): 
W/jxcore-log(16751): JXcore engine is started
E/jxcore-log(16751): >> samsung-SM-G900F
E/jxcore-log(16751): 
I/jxcore-log(16751): Total memory 1787449344
I/jxcore-log(16751): 
I/jxcore-log(16751): Free memory 44982272
I/jxcore-log(16751): 
I/jxcore-log(16751): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16751): 
I/jxcore-log(16751): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16751): 
I/jxcore-log(16751): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16751): 
I/jxcore-log(16751): Size 1080 1920
I/jxcore-log(16751): 
I/jxcore-log(16751): Screen Brightness 255
I/jxcore-log(16751): 
E/jxcore-log(16751): Dummy Error Log.
E/jxcore-log(16751): 
,I/jxcore-log(16751): getBuffer is called!!!!
I/jxcore-log(16751): 
,I/jxcore-log(16751): ****TEST TOOK:  5066  ms ****
I/jxcore-log(16751): 
,I/jxcore-log(16751): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16751): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(23997): Initializing JXcore engine
W/jxcore-log(23997): JXcore engine is ready
,W/jxcore-log(23997): Starting JXcore engine
,W/jxcore-log(23997): Platform android
W/jxcore-log(23997): 
,W/jxcore-log(23997): Process ARCH arm
W/jxcore-log(23997): 
,I/jxcore-log(23997): JXcore Cordova bridge is ready!
I/jxcore-log(23997): 
,W/jxcore-log(23997): JXcore engine is started
,E/jxcore-log(23997): >> HTC-HTC One_M8
E/jxcore-log(23997): 
,I/jxcore-log(23997): Total memory 1912020992
I/jxcore-log(23997): 
,I/jxcore-log(23997): Free memory 394690560
I/jxcore-log(23997): 
I/jxcore-log(23997): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23997): 
I/jxcore-log(23997): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23997): 
,I/jxcore-log(23997): userPath [ 'www' ]
I/jxcore-log(23997): 
,I/jxcore-log(23997): Size 1080 1776
I/jxcore-log(23997): 
,I/jxcore-log(23997): Screen Brightness 142
I/jxcore-log(23997): 
,E/jxcore-log(23997): Dummy Error Log.
E/jxcore-log(23997): 
,I/jxcore-log(23997): getBuffer is called!!!!
I/jxcore-log(23997): 
,I/jxcore-log(23997): ****TEST TOOK:  5095  ms ****,
I/jxcore-log(23997): 
I/jxcore-log(23997): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23997): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(19921): Initializing JXcore engine
,W/jxcore-log(19921): JXcore engine is ready
,W/jxcore-log(19921): Starting JXcore engine
,W/jxcore-log(19921): Platform android
W/jxcore-log(19921): 
,W/jxcore-log(19921): Process ARCH arm
W/jxcore-log(19921): 
,I/jxcore-log(19921): JXcore Cordova bridge is ready!
I/jxcore-log(19921): 
,W/jxcore-log(19921): JXcore engine is started
,E/jxcore-log(19921): >> samsung-SM-N9005
E/jxcore-log(19921): 
,I/jxcore-log(19921): Total memory 2971471872
I/jxcore-log(19921): 
,I/jxcore-log(19921): Free memory 276246528
I/jxcore-log(19921): 
I/jxcore-log(19921): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19921): 
I/jxcore-log(19921): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19921): 
,I/jxcore-log(19921): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(19921): 
,I/jxcore-log(19921): Size 1080 1920
I/jxcore-log(19921): 
,I/jxcore-log(19921): Screen Brightness 255
I/jxcore-log(19921): 
,E/jxcore-log(19921): Dummy Error Log.
E/jxcore-log(19921): 
,I/jxcore-log(19921): getBuffer is called!!!!
I/jxcore-log(19921): 
,I/jxcore-log(19921): ****TEST TOOK:  5052  ms ****
I/jxcore-log(19921): 
I/jxcore-log(19921): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19921): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 4109): Initializing JXcore engine
,W/jxcore-log( 4109): JXcore engine is ready
,W/jxcore-log( 4109): Starting JXcore engine
,W/jxcore-log( 4109): Platform android
W/jxcore-log( 4109): 
W/jxcore-log( 4109): Process ARCH arm
W/jxcore-log( 4109): 
,I/jxcore-log( 4109): JXcore Cordova bridge is ready!
I/jxcore-log( 4109): 
,W/jxcore-log( 4109): JXcore engine is started,
,E/jxcore-log( 4109): >> motorola-Nexus 6
E/jxcore-log( 4109): 
,I/jxcore-log( 4109): Total memory 3114405888
I/jxcore-log( 4109): 
,I/jxcore-log( 4109): Free memory 593326080
I/jxcore-log( 4109): 
,I/jxcore-log( 4109): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4109): 
,I/jxcore-log( 4109): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4109): 
I/jxcore-log( 4109): userPath [ 'www' ]
I/jxcore-log( 4109): 
I/jxcore-log( 4109): Size 1440 2392
I/jxcore-log( 4109): 
,I/jxcore-log( 4109): Screen Brightness 82
I/jxcore-log( 4109): 
,E/jxcore-log( 4109): Dummy Error Log.
E/jxcore-log( 4109): 
,I/jxcore-log( 4109): getBuffer is called!!!!
I/jxcore-log( 4109): 
,I/jxcore-log( 4109): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 4109): 
I/jxcore-log( 4109): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4109): 


```

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15641): Initializing JXcore engine,
W/jxcore-log(15641): JXcore engine is ready
,W/jxcore-log(15641): Starting JXcore engine,
,W/jxcore-log(15641): Platform android
W/jxcore-log(15641): 
,W/jxcore-log(15641): Process ARCH arm
W/jxcore-log(15641): 
,I/jxcore-log(15641): JXcore Cordova bridge is ready!,
I/jxcore-log(15641): 
W/jxcore-log(15641): JXcore engine is started
,E/jxcore-log(15641): >> HTC-HTC One M8s
E/jxcore-log(15641): 
,I/jxcore-log(15641): Total memory 1931808768,
I/jxcore-log(15641): 
I/jxcore-log(15641): Free memory 298446848
I/jxcore-log(15641): 
I/jxcore-log(15641): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15641): 
I/jxcore-log(15641): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15641): 
,I/jxcore-log(15641): userPath [ 'www' ],
I/jxcore-log(15641): 
,I/jxcore-log(15641): Size 1080 1776
I/jxcore-log(15641): 
,I/jxcore-log(15641): Screen Brightness 142,
I/jxcore-log(15641): 
E/jxcore-log(15641): Dummy Error Log.
E/jxcore-log(15641): 
,I/jxcore-log(15641): getBuffer is called!!!!
I/jxcore-log(15641): 
,I/jxcore-log(15641): ****TEST TOOK:  5040  ms ****
I/jxcore-log(15641): 
,I/jxcore-log(15641): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15641): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(12801): Initializing JXcore engine
W/jxcore-log(12801): JXcore engine is ready
W/jxcore-log(12801): Starting JXcore engine
W/jxcore-log(12801): Platform android
W/jxcore-log(12801): 
W/jxcore-log(12801): Process ARCH arm
W/jxcore-log(12801): 
I/jxcore-log(12801): JXcore Cordova bridge is ready!
I/jxcore-log(12801): 
W/jxcore-log(12801): JXcore engine is started
E/jxcore-log(12801): >> samsung-SM-A300FU
E/jxcore-log(12801): 
I/jxcore-log(12801): Total memory 1451114496
I/jxcore-log(12801): 
I/jxcore-log(12801): Free memory 187473920
I/jxcore-log(12801): 
I/jxcore-log(12801): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12801): 
I/jxcore-log(12801): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12801): 
I/jxcore-log(12801): userPath [ 'www' ]
I/jxcore-log(12801): 
I/jxcore-log(12801): Size 540 960
I/jxcore-log(12801): 
I/jxcore-log(12801): Screen Brightness 160
I/jxcore-log(12801): 
E/jxcore-log(12801): Dummy Error Log.
E/jxcore-log(12801): 
I/jxcore-log(12801): getBuffer is called!!!!
I/jxcore-log(12801): 
,I/jxcore-log(12801): ****TEST TOOK:  5036  ms ****
I/jxcore-log(12801): 
,I/jxcore-log(12801): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12801): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
W/jxcore-log( 9621): Initializing JXcore engine
W/jxcore-log( 9621): JXcore engine is ready
W/jxcore-log( 9621): Starting JXcore engine
W/jxcore-log( 9621): Platform android
W/jxcore-log( 9621): 
W/jxcore-log( 9621): Process ARCH arm
W/jxcore-log( 9621): 
I/jxcore-log( 9621): JXcore Cordova bridge is ready!
I/jxcore-log( 9621): 
W/jxcore-log( 9621): JXcore engine is started
E/jxcore-log( 9621): >> LGE-LG-D802
E/jxcore-log( 9621): 
I/jxcore-log( 9621): Total memory 1943035904
I/jxcore-log( 9621): 
I/jxcore-log( 9621): Free memory 226893824
I/jxcore-log( 9621): 
I/jxcore-log( 9621): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9621): 
I/jxcore-log( 9621): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9621): 
I/jxcore-log( 9621): userPath [ 'www' ]
I/jxcore-log( 9621): 
I/jxcore-log( 9621): Size 1080 1776
I/jxcore-log( 9621): 
I/jxcore-log( 9621): Screen Brightness 255
I/jxcore-log( 9621): 
E/jxcore-log( 9621): Dummy Error Log.
E/jxcore-log( 9621): 
,I/jxcore-log( 9621): getBuffer is called!!!!
I/jxcore-log( 9621): 
,I/jxcore-log( 9621): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 9621): 
I/jxcore-log( 9621): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9621): 


```

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(22374): Initializing JXcore engine
W/jxcore-log(22374): JXcore engine is ready
W/jxcore-log(22374): Starting JXcore engine
,W/jxcore-log(22374): Platform android
W/jxcore-log(22374): 
W/jxcore-log(22374): Process ARCH arm
W/jxcore-log(22374): 
,I/jxcore-log(22374): JXcore Cordova bridge is ready!
I/jxcore-log(22374): 
,W/jxcore-log(22374): JXcore engine is started
,E/jxcore-log(22374): >> samsung-SM-A500FU
E/jxcore-log(22374): 
,I/jxcore-log(22374): Total memory 1983787008
I/jxcore-log(22374): 
,I/jxcore-log(22374): Free memory 390017024
I/jxcore-log(22374): 
I/jxcore-log(22374): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22374): 
I/jxcore-log(22374): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22374): 
,I/jxcore-log(22374): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(22374): 
,I/jxcore-log(22374): Size 720 1280
I/jxcore-log(22374): 
,I/jxcore-log(22374): Screen Brightness 255
I/jxcore-log(22374): 
,E/jxcore-log(22374): Dummy Error Log.
E/jxcore-log(22374): 
,I/jxcore-log(22374): getBuffer is called!!!!
I/jxcore-log(22374): 
,I/jxcore-log(22374): ****TEST TOOK:  5039  ms ****
I/jxcore-log(22374): 
,I/jxcore-log(22374): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22374): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(24037): Initializing JXcore engine
W/jxcore-log(24037): JXcore engine is ready
,W/jxcore-log(24037): Starting JXcore engine
,W/jxcore-log(24037): Platform android
W/jxcore-log(24037): 
W/jxcore-log(24037): Process ARCH arm
W/jxcore-log(24037): 
,I/jxcore-log(24037): JXcore Cordova bridge is ready!
I/jxcore-log(24037): 
,W/jxcore-log(24037): JXcore engine is started
,E/jxcore-log(24037): >> samsung-SM-G900F
E/jxcore-log(24037): 
,I/jxcore-log(24037): Total memory 1787449344
I/jxcore-log(24037): 
,I/jxcore-log(24037): Free memory 106979328
I/jxcore-log(24037): 
I/jxcore-log(24037): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24037): 
I/jxcore-log(24037): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24037): 
,I/jxcore-log(24037): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(24037): 
,I/jxcore-log(24037): Size 1080 1920
I/jxcore-log(24037): 
,I/jxcore-log(24037): Screen Brightness 134
I/jxcore-log(24037): 
,E/jxcore-log(24037): Dummy Error Log.
E/jxcore-log(24037): 
,I/jxcore-log(24037): getBuffer is called!!!!
I/jxcore-log(24037): 
,I/jxcore-log(24037): ****TEST TOOK:  5072  ms ****
I/jxcore-log(24037): 
,I/jxcore-log(24037): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24037): 


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15798): Initializing JXcore engine
W/jxcore-log(15798): JXcore engine is ready
W/jxcore-log(15798): Starting JXcore engine
W/jxcore-log(15798): Platform android
W/jxcore-log(15798): 
W/jxcore-log(15798): Process ARCH arm
W/jxcore-log(15798): 
I/jxcore-log(15798): JXcore Cordova bridge is ready!
I/jxcore-log(15798): 
W/jxcore-log(15798): JXcore engine is started
E/jxcore-log(15798): >> samsung-SM-A300FU
E/jxcore-log(15798): 
I/jxcore-log(15798): Total memory 1451114496
I/jxcore-log(15798): 
I/jxcore-log(15798): Free memory 243298304
I/jxcore-log(15798): 
I/jxcore-log(15798): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15798): 
I/jxcore-log(15798): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15798): 
I/jxcore-log(15798): userPath [ 'www' ]
I/jxcore-log(15798): 
I/jxcore-log(15798): Size 540 960
I/jxcore-log(15798): 
I/jxcore-log(15798): Screen Brightness 255
I/jxcore-log(15798): 
E/jxcore-log(15798): Dummy Error Log.
E/jxcore-log(15798): 
,I/jxcore-log(15798): getBuffer is called!!!!
I/jxcore-log(15798): 
,I/jxcore-log(15798): ****TEST TOOK:  5038  ms ****
I/jxcore-log(15798): 
,I/jxcore-log(15798): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15798): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(24165): Initializing JXcore engine
,W/jxcore-log(24165): JXcore engine is ready
,W/jxcore-log(24165): Starting JXcore engine
,W/jxcore-log(24165): Platform android
W/jxcore-log(24165): 
,W/jxcore-log(24165): Process ARCH arm
W/jxcore-log(24165): 
,I/jxcore-log(24165): JXcore Cordova bridge is ready!
I/jxcore-log(24165): 
,W/jxcore-log(24165): JXcore engine is started
,E/jxcore-log(24165): >> HTC-HTC Desire 820
E/jxcore-log(24165): 
,I/jxcore-log(24165): Total memory 1964650496
I/jxcore-log(24165): 
I/jxcore-log(24165): Free memory 247234560
I/jxcore-log(24165): 
I/jxcore-log(24165): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24165): 
,I/jxcore-log(24165): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24165): 
,I/jxcore-log(24165): userPath [ 'www' ]
I/jxcore-log(24165): 
,I/jxcore-log(24165): Size 720 1184
I/jxcore-log(24165): 
,I/jxcore-log(24165): Screen Brightness 10
I/jxcore-log(24165): 
,E/jxcore-log(24165): Dummy Error Log.
E/jxcore-log(24165): 
,I/jxcore-log(24165): getBuffer is called!!!!
I/jxcore-log(24165): 
,I/jxcore-log(24165): ****TEST TOOK:  5066  ms ****
I/jxcore-log(24165): 
I/jxcore-log(24165): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24165): 


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
,W/jxcore-log(21229): Initializing JXcore engine
W/jxcore-log(21229): JXcore engine is ready
,W/jxcore-log(21229): Starting JXcore engine
,W/jxcore-log(21440): Initializing JXcore engine
,W/jxcore-log(21440): JXcore engine is ready
,W/jxcore-log(21440): Starting JXcore engine
,W/jxcore-log(21440): Platform android
W/jxcore-log(21440): 
,W/jxcore-log(21440): Process ARCH arm
W/jxcore-log(21440): 
,I/jxcore-log(21440): JXcore Cordova bridge is ready!
I/jxcore-log(21440): 
,W/jxcore-log(21440): JXcore engine is started
,E/jxcore-log(21440): >> LGE-Nexus 5
E/jxcore-log(21440): 
,I/jxcore-log(21440): Total memory 1945137152
I/jxcore-log(21440): 
I/jxcore-log(21440): Free memory 41562112
I/jxcore-log(21440): 
I/jxcore-log(21440): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21440): 
,I/jxcore-log(21440): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21440): 
,I/jxcore-log(21440): userPath [ 'www' ]
I/jxcore-log(21440): 
,I/jxcore-log(21440): Size 1080 1776
I/jxcore-log(21440): 
,I/jxcore-log(21440): Screen Brightness 82
I/jxcore-log(21440): 
,E/jxcore-log(21440): Dummy Error Log.
E/jxcore-log(21440): 
,I/jxcore-log(21440): getBuffer is called!!!!
I/jxcore-log(21440): 
,I/jxcore-log(21440): ****TEST TOOK:  5033  ms ****
I/jxcore-log(21440): 
,I/jxcore-log(21440): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21440): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(19145): Initializing JXcore engine
,W/jxcore-log(19145): JXcore engine is ready
,W/jxcore-log(19145): Starting JXcore engine
,W/jxcore-log(19145): Platform android
W/jxcore-log(19145): 
,W/jxcore-log(19145): Process ARCH arm
W/jxcore-log(19145): 
,I/jxcore-log(19145): JXcore Cordova bridge is ready!
I/jxcore-log(19145): 
,W/jxcore-log(19145): JXcore engine is started
,E/jxcore-log(19145): >> HTC-HTC Desire 820
E/jxcore-log(19145): 
,I/jxcore-log(19145): Total memory 1964650496
I/jxcore-log(19145): 
I/jxcore-log(19145): Free memory 231100416
I/jxcore-log(19145): 
,I/jxcore-log(19145): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19145): 
,I/jxcore-log(19145): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19145): 
,I/jxcore-log(19145): userPath [ 'www' ]
I/jxcore-log(19145): 
,I/jxcore-log(19145): Size 720 1184
I/jxcore-log(19145): 
,I/jxcore-log(19145): Screen Brightness 142
I/jxcore-log(19145): 
,E/jxcore-log(19145): Dummy Error Log.
E/jxcore-log(19145): 
,I/jxcore-log(19145): getBuffer is called!!!!
I/jxcore-log(19145): 
,I/jxcore-log(19145): ****TEST TOOK:  5067  ms ****
I/jxcore-log(19145): 
I/jxcore-log(19145): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19145): 


```


