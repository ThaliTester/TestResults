#### Test 476722347fc8662 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_476722347fc8662/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":20,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 20, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E61207D2-9EA0-4588-8396-5E2FAEAFD192/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E61207D2-9EA0-4588-8396-5E2FAEAFD192/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BCF7E1AA-AAFA-4B07-B515-9E7E17C41A35/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62584"
,(lldb)     command script import "/tmp/E61207D2-9EA0-4588-8396-5E2FAEAFD192/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-05 13:46:22.492 HelloWorld[1534:1611063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/07FF698B-C53A-46DB-A7BA-951E66A20C40/Library/Cookies/Cookies.binarycookies
,2015-11-05 13:46:22.862 HelloWorld[1534:1611063] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-05 13:46:22.863 HelloWorld[1534:1611063] Multi-tasking -> Device: YES, App: YES
,2015-11-05 13:46:22.866 HelloWorld[1534:1611063] Unlimited access to network resources
,2015-11-05 13:46:22.871 HelloWorld[1534:1611063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-05 13:46:25.534 HelloWorld[1534:1611063] Resetting plugins due to page load.
,2015-11-05 13:46:25.740 HelloWorld[1534:1611063] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/BCF7E1AA-AAFA-4B07-B515-9E7E17C41A35/HelloWorld.app/www/index.html
,2015-11-05 13:46:25.799 HelloWorld[1534:1611063] JXcore Cordova plugin initializing
2015-11-05 13:46:25.800 HelloWorld[1534:1611457] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
,Free memory 124059648
,execPath /private/var/mobile/Containers/Bundle/Application/BCF7E1AA-AAFA-4B07-B515-9E7E17C41A35/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/BCF7E1AA-AAFA-4B07-B515-9E7E17C41A35/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-05 13:46:26.081 HelloWorld[1534:1611457] Native method ScreenInfo not found.
,2015-11-05 13:46:26.083 HelloWorld[1534:1611457] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5127  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AE5CCB2D-4581-496E-B948-4E651EE88AEF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AE5CCB2D-4581-496E-B948-4E651EE88AEF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/21D4B2D3-847B-42E4-9D63-790D4EE38021/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62600"
,(lldb)     command script import "/tmp/AE5CCB2D-4581-496E-B948-4E651EE88AEF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,error: process launch failed: timed out trying to launch app
,(lldb)     autoexit



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/08C000CE-56CB-4CCC-9175-FF3689A77381/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
Executing commands in '/tmp/08C000CE-56CB-4CCC-9175-FF3689A77381/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5957FE45-12E6-42E7-A5F5-7BC87163DAD3/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62585"
,(lldb)     command script import "/tmp/08C000CE-56CB-4CCC-9175-FF3689A77381/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-05 13:46:23.652 HelloWorld[2528:2663288] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5F8ED616-00AF-46C8-A951-151AFC8073ED/Library/Cookies/Cookies.binarycookies
,2015-11-05 13:46:24.018 HelloWorld[2528:2663288] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-05 13:46:24.019 HelloWorld[2528:2663288] Multi-tasking -> Device: YES, App: YES
,2015-11-05 13:46:24.021 HelloWorld[2528:2663288] Unlimited access to network resources
,2015-11-05 13:46:24.026 HelloWorld[2528:2663288] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-05 13:46:27.615 HelloWorld[2528:2663288] Resetting plugins due to page load.
,2015-11-05 13:46:28.045 HelloWorld[2528:2663288] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5957FE45-12E6-42E7-A5F5-7BC87163DAD3/HelloWorld.app/www/index.html
,2015-11-05 13:46:28.101 HelloWorld[2528:2663288] JXcore Cordova plugin initializing
2015-11-05 13:46:28.102 HelloWorld[2528:2663406] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 96845824
execPath /private/var/mobile/Containers/Bundle/Application/5957FE45-12E6-42E7-A5F5-7BC87163DAD3/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/5957FE45-12E6-42E7-A5F5-7BC87163DAD3/HelloWorld.app/www/jxcore/
,userPath []
2015-11-05 13:46:28.309 HelloWorld[2528:2663406] Native method ScreenInfo not found.
2015-11-05 13:46:28.309 HelloWorld[2528:2663406] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5107  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/64D00A2B-C559-4C27-8A6D-9B8CCE53D38B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/64D00A2B-C559-4C27-8A6D-9B8CCE53D38B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/001E1730-DEAF-4CDB-98A9-2056A2A88AB1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62583"
,(lldb)     command script import "/tmp/64D00A2B-C559-4C27-8A6D-9B8CCE53D38B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-05 13:46:30.040 HelloWorld[1689:3470161] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E478A438-545E-48D6-804F-37260FB74974/Library/Cookies/Cookies.binarycookies
,2015-11-05 13:46:30.548 HelloWorld[1689:3470161] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-05 13:46:30.549 HelloWorld[1689:3470161] Multi-tasking -> Device: YES, App: YES
,2015-11-05 13:46:30.553 HelloWorld[1689:3470161] Unlimited access to network resources
,2015-11-05 13:46:30.563 HelloWorld[1689:3470161] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-05 13:46:40.379 HelloWorld[1689:3470161] Resetting plugins due to page load.
,2015-11-05 13:46:43.934 HelloWorld[1689:3470161] Finished load of: file:///var/mobile/Containers/Bundle/Application/001E1730-DEAF-4CDB-98A9-2056A2A88AB1/HelloWorld.app/www/index.html
,2015-11-05 13:46:44.004 HelloWorld[1689:3470161] JXcore Cordova plugin initializing
,2015-11-05 13:46:44.005 HelloWorld[1689:3470406] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 359546880
,execPath /private/var/mobile/Containers/Bundle/Application/001E1730-DEAF-4CDB-98A9-2056A2A88AB1/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/001E1730-DEAF-4CDB-98A9-2056A2A88AB1/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-05 13:46:44.196 HelloWorld[1689:3470406] Native method ScreenInfo not found.
,2015-11-05 13:46:44.196 HelloWorld[1689:3470406] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5115  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



server: 
iOS application timeout
,Unexpected exit on device 17df3859480c382d3b761fa2643dde395ced1bd8 app:Iphone5-1 code:null


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 03157df360a1882a error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device W3D7N15428022572 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device LGH8153b36be34 error: device not found
 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
W/jxcore-log( 5513): Initializing JXcore engine
W/jxcore-log( 5513): JXcore engine is ready
W/jxcore-log( 5513): Starting JXcore engine
,W/jxcore-log( 5513): Platform android
W/jxcore-log( 5513): 
W/jxcore-log( 5513): Process ARCH arm
W/jxcore-log( 5513): 
I/jxcore-log( 5513): JXcore Cordova bridge is ready!
I/jxcore-log( 5513): 
W/jxcore-log( 5513): JXcore engine is started
E/jxcore-log( 5513): >> samsung-SM-T232
E/jxcore-log( 5513): 
I/jxcore-log( 5513): Total memory 1352024064
I/jxcore-log( 5513): 
I/jxcore-log( 5513): Free memory 130355200
I/jxcore-log( 5513): 
I/jxcore-log( 5513): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5513): 
I/jxcore-log( 5513): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5513): 
I/jxcore-log( 5513): userPath [ 'www' ]
I/jxcore-log( 5513): 
I/jxcore-log( 5513): Size 800 1280
I/jxcore-log( 5513): 
I/jxcore-log( 5513): Screen Brightness 143
I/jxcore-log( 5513): 
E/jxcore-log( 5513): Dummy Error Log.
E/jxcore-log( 5513): 
,I/jxcore-log( 5513): getBuffer is called!!!!
I/jxcore-log( 5513): 
,I/jxcore-log( 5513): ****TEST TOOK:  5163  ms ****
I/jxcore-log( 5513): 
I/jxcore-log( 5513): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5513): 


samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(10485): Initializing JXcore engine
W/jxcore-log(10485): JXcore engine is ready
,W/jxcore-log(10485): Starting JXcore engine
,W/jxcore-log(10485): Platform android
W/jxcore-log(10485): 
W/jxcore-log(10485): Process ARCH arm
W/jxcore-log(10485): 
,I/jxcore-log(10485): JXcore Cordova bridge is ready!
I/jxcore-log(10485): 
W/jxcore-log(10485): JXcore engine is started
,E/jxcore-log(10485): >> samsung-SM-G920F
E/jxcore-log(10485): 
,I/jxcore-log(10485): Total memory 2829074432
I/jxcore-log(10485): 
I/jxcore-log(10485): Free memory 49012736
I/jxcore-log(10485): 
I/jxcore-log(10485): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10485): 
I/jxcore-log(10485): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10485): 
,I/jxcore-log(10485): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10485): 
,I/jxcore-log(10485): Size 1440 2560
I/jxcore-log(10485): 
I/jxcore-log(10485): Screen Brightness 134
I/jxcore-log(10485): 
E/jxcore-log(10485): Dummy Error Log.
E/jxcore-log(10485): 
,I/jxcore-log(10485): getBuffer is called!!!!
I/jxcore-log(10485): 
,I/jxcore-log(10485): ****TEST TOOK:  5121  ms ****
I/jxcore-log(10485): 
,I/jxcore-log(10485): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10485): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log( 8259): Initializing JXcore engine
W/jxcore-log( 8259): JXcore engine is ready
,W/jxcore-log( 8259): Starting JXcore engine
,W/jxcore-log( 8259): Platform android
W/jxcore-log( 8259): 
W/jxcore-log( 8259): Process ARCH arm
W/jxcore-log( 8259): 
,I/jxcore-log( 8259): JXcore Cordova bridge is ready!
I/jxcore-log( 8259): 
,W/jxcore-log( 8259): JXcore engine is started
,E/jxcore-log( 8259): >> HUAWEI-ALE-L21
E/jxcore-log( 8259): 
,I/jxcore-log( 8259): Total memory 1949741056
I/jxcore-log( 8259): 
,I/jxcore-log( 8259): Free memory 18382848
I/jxcore-log( 8259): 
I/jxcore-log( 8259): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8259): 
I/jxcore-log( 8259): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8259): 
,I/jxcore-log( 8259): userPath [ 'www' ]
I/jxcore-log( 8259): 
,I/jxcore-log( 8259): Size 720 1184
I/jxcore-log( 8259): 
,I/jxcore-log( 8259): Screen Brightness 242
I/jxcore-log( 8259): 
,E/jxcore-log( 8259): Dummy Error Log.
E/jxcore-log( 8259): 
,I/jxcore-log( 8259): getBuffer is called!!!!
I/jxcore-log( 8259): 
,I/jxcore-log( 8259): ****TEST TOOK:  5424  ms ****
I/jxcore-log( 8259): 
I/jxcore-log( 8259): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8259): 


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 8581): Initializing JXcore engine
W/jxcore-log( 8581): JXcore engine is ready
W/jxcore-log( 8581): Starting JXcore engine
,W/jxcore-log( 8581): Platform android
W/jxcore-log( 8581): 
W/jxcore-log( 8581): Process ARCH arm
W/jxcore-log( 8581): 
,I/jxcore-log( 8581): JXcore Cordova bridge is ready!
I/jxcore-log( 8581): 
,W/jxcore-log( 8581): JXcore engine is started
,E/jxcore-log( 8581): >> LGE-LG-H815
E/jxcore-log( 8581): 
,I/jxcore-log( 8581): Total memory 2968948736
I/jxcore-log( 8581): 
,I/jxcore-log( 8581): Free memory 93802496
I/jxcore-log( 8581): 
I/jxcore-log( 8581): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8581): 
I/jxcore-log( 8581): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8581): 
I/jxcore-log( 8581): userPath [ 'www' ]
I/jxcore-log( 8581): 
,I/jxcore-log( 8581): Size 1440 2392
I/jxcore-log( 8581): 
I/jxcore-log( 8581): Screen Brightness 255
I/jxcore-log( 8581): 
E/jxcore-log( 8581): Dummy Error Log.
E/jxcore-log( 8581): 
,I/jxcore-log( 8581): getBuffer is called!!!!
I/jxcore-log( 8581): 
,I/jxcore-log( 8581): ****TEST TOOK:  5068  ms ****
I/jxcore-log( 8581): 
,I/jxcore-log( 8581): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8581): 


```

####Node name: thali02
Console output:
```
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on FA533YJ03104 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device FA533YJ03104 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device LGD7228ee9cf5b error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 09a9416e0297d102 error: device not found
 
```

Logcat output:
```
HTC-HTC One M9: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6579): Initializing JXcore engine
W/jxcore-log( 6579): JXcore engine is ready
W/jxcore-log( 6579): Starting JXcore engine
W/jxcore-log( 6579): Platform android
W/jxcore-log( 6579): 
W/jxcore-log( 6579): Process ARCH arm
W/jxcore-log( 6579): 
I/jxcore-log( 6579): JXcore Cordova bridge is ready!
I/jxcore-log( 6579): 
W/jxcore-log( 6579): JXcore engine is started
E/jxcore-log( 6579): >> HTC-HTC One M9
E/jxcore-log( 6579): 
I/jxcore-log( 6579): Total memory 2860257280
I/jxcore-log( 6579): 
I/jxcore-log( 6579): Free memory 166215680
I/jxcore-log( 6579): 
I/jxcore-log( 6579): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6579): 
I/jxcore-log( 6579): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6579): 
I/jxcore-log( 6579): userPath [ 'www' ]
I/jxcore-log( 6579): 
I/jxcore-log( 6579): Size 1080 1776
I/jxcore-log( 6579): 
I/jxcore-log( 6579): Screen Brightness 142
I/jxcore-log( 6579): 
E/jxcore-log( 6579): Dummy Error Log.
E/jxcore-log( 6579): 
I/jxcore-log( 6579): getBuffer is called!!!!
I/jxcore-log( 6579): 
,I/jxcore-log( 6579): ****TEST TOOK:  5102  ms ****
I/jxcore-log( 6579): 
,I/jxcore-log( 6579): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6579): 


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 4419): Initializing JXcore engine
W/jxcore-log( 4419): JXcore engine is ready
,W/jxcore-log( 4419): Starting JXcore engine
,W/jxcore-log( 4419): Platform android
W/jxcore-log( 4419): 
W/jxcore-log( 4419): Process ARCH arm
W/jxcore-log( 4419): 
,I/jxcore-log( 4419): JXcore Cordova bridge is ready!
I/jxcore-log( 4419): 
W/jxcore-log( 4419): JXcore engine is started
,E/jxcore-log( 4419): >> LGE-LG-D722
E/jxcore-log( 4419): 
I/jxcore-log( 4419): Total memory 906309632
I/jxcore-log( 4419): 
I/jxcore-log( 4419): Free memory 20422656
I/jxcore-log( 4419): 
I/jxcore-log( 4419): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4419): 
I/jxcore-log( 4419): userPath [ 'www' ]
I/jxcore-log( 4419): 
I/jxcore-log( 4419): Size 720 1196
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): Screen Brightness 255
I/jxcore-log( 4419): 
E/jxcore-log( 4419): Dummy Error Log.
E/jxcore-log( 4419): 
,I/jxcore-log( 4419): getBuffer is called!!!!
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): ****TEST TOOK:  5099  ms ****
I/jxcore-log( 4419): 
I/jxcore-log( 4419): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4419): 


LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 2466): Initializing JXcore engine
W/jxcore-log( 2466): JXcore engine is ready
,W/jxcore-log( 2466): Starting JXcore engine
,W/jxcore-log( 2466): Platform android
W/jxcore-log( 2466): 
,W/jxcore-log( 2466): Process ARCH arm
W/jxcore-log( 2466): 
,I/jxcore-log( 2466): JXcore Cordova bridge is ready!
I/jxcore-log( 2466): 
W/jxcore-log( 2466): JXcore engine is started
,E/jxcore-log( 2466): >> LGE-Nexus 5
E/jxcore-log( 2466): 
,I/jxcore-log( 2466): Total memory 1946181632
I/jxcore-log( 2466): 
I/jxcore-log( 2466): Free memory 336887808
I/jxcore-log( 2466): 
I/jxcore-log( 2466): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2466): 
I/jxcore-log( 2466): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2466): 
,I/jxcore-log( 2466): userPath [ 'www' ]
I/jxcore-log( 2466): 
,I/jxcore-log( 2466): Size 1080 1776
I/jxcore-log( 2466): 
,I/jxcore-log( 2466): Screen Brightness 82
I/jxcore-log( 2466): 
E/jxcore-log( 2466): Dummy Error Log.
E/jxcore-log( 2466): 
,I/jxcore-log( 2466): getBuffer is called!!!!
I/jxcore-log( 2466): 
,I/jxcore-log( 2466): ****TEST TOOK:  5082  ms ****
I/jxcore-log( 2466): 
I/jxcore-log( 2466): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2466): 


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
Error: problem stopping Android apk(com.example.hello) to device 320414cd475f91e3 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device TA4750HV7I error: device not found
 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system,
--------- beginning of /dev/log/main
,W/jxcore-log( 6936): Initializing JXcore engine
,W/jxcore-log( 6936): JXcore engine is ready
,W/jxcore-log( 6936): Starting JXcore engine
,W/jxcore-log( 6936): Platform android
W/jxcore-log( 6936): 
,W/jxcore-log( 6936): Process ARCH arm
W/jxcore-log( 6936): 
,I/jxcore-log( 6936): JXcore Cordova bridge is ready!
I/jxcore-log( 6936): 
,W/jxcore-log( 6936): JXcore engine is started
,E/jxcore-log( 6936): >> samsung-SM-G800F
E/jxcore-log( 6936): 
,I/jxcore-log( 6936): Total memory 1319530496
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): Free memory 40738816
I/jxcore-log( 6936): 
I/jxcore-log( 6936): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): Size 720 1280
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): Screen Brightness 134
I/jxcore-log( 6936): 
,E/jxcore-log( 6936): Dummy Error Log.
E/jxcore-log( 6936): 
,I/jxcore-log( 6936): getBuffer is called!!!!
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): ****TEST TOOK:  5176  ms ****
I/jxcore-log( 6936): 
,I/jxcore-log( 6936): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6936): 


motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 3820): Initializing JXcore engine
,W/jxcore-log( 3820): JXcore engine is ready
,W/jxcore-log( 3820): Starting JXcore engine
,W/jxcore-log( 3820): Platform android
W/jxcore-log( 3820): 
,W/jxcore-log( 3820): Process ARCH arm
W/jxcore-log( 3820): 
,I/jxcore-log( 3820): JXcore Cordova bridge is ready!
I/jxcore-log( 3820): 
,W/jxcore-log( 3820): JXcore engine is started
,E/jxcore-log( 3820): >> motorola-XT1039
E/jxcore-log( 3820): 
,I/jxcore-log( 3820): Total memory 893136896
I/jxcore-log( 3820): 
I/jxcore-log( 3820): Free memory 56381440
I/jxcore-log( 3820): 
I/jxcore-log( 3820): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): userPath [ 'www' ]
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): Size 720 1184
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): Screen Brightness 10
I/jxcore-log( 3820): 
,E/jxcore-log( 3820): Dummy Error Log.
E/jxcore-log( 3820): 
,I/jxcore-log( 3820): getBuffer is called!!!!
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): ****TEST TOOK:  5243  ms ****
I/jxcore-log( 3820): 
,I/jxcore-log( 3820): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3820): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6414): Initializing JXcore engine
W/jxcore-log( 6414): JXcore engine is ready
W/jxcore-log( 6414): Starting JXcore engine
W/jxcore-log( 6414): Platform android
W/jxcore-log( 6414): 
W/jxcore-log( 6414): Process ARCH arm
W/jxcore-log( 6414): 
I/jxcore-log( 6414): JXcore Cordova bridge is ready!
I/jxcore-log( 6414): 
W/jxcore-log( 6414): JXcore engine is started
E/jxcore-log( 6414): >> LGE-LG-D855
E/jxcore-log( 6414): 
I/jxcore-log( 6414): Total memory 2995761152
I/jxcore-log( 6414): 
I/jxcore-log( 6414): Free memory 586457088
I/jxcore-log( 6414): 
I/jxcore-log( 6414): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6414): 
I/jxcore-log( 6414): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6414): 
I/jxcore-log( 6414): userPath [ 'www' ]
I/jxcore-log( 6414): 
I/jxcore-log( 6414): Size 1440 2392
I/jxcore-log( 6414): 
,I/jxcore-log( 6414): Screen Brightness 177
I/jxcore-log( 6414): 
E/jxcore-log( 6414): Dummy Error Log.
E/jxcore-log( 6414): 
,I/jxcore-log( 6414): getBuffer is called!!!!
I/jxcore-log( 6414): 
,I/jxcore-log( 6414): ****TEST TOOK:  5226  ms ****
I/jxcore-log( 6414): 
I/jxcore-log( 6414): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6414): 


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on 1d6a772d 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.example.hello code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device ZX1G429CRK error: device not found
 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6921): Initializing JXcore engine
W/jxcore-log( 6921): JXcore engine is ready
,W/jxcore-log( 6921): Starting JXcore engine
,W/jxcore-log( 6921): Platform android
W/jxcore-log( 6921): 
W/jxcore-log( 6921): Process ARCH arm
W/jxcore-log( 6921): 
,I/jxcore-log( 6921): JXcore Cordova bridge is ready!
I/jxcore-log( 6921): 
,W/jxcore-log( 6921): JXcore engine is started
,E/jxcore-log( 6921): >> samsung-SM-N9005
E/jxcore-log( 6921): 
,I/jxcore-log( 6921): Total memory 2971471872
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): Free memory 354512896
I/jxcore-log( 6921): 
I/jxcore-log( 6921): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6921): 
I/jxcore-log( 6921): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): Size 1080 1920
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): Screen Brightness 162
I/jxcore-log( 6921): 
,E/jxcore-log( 6921): Dummy Error Log.
E/jxcore-log( 6921): 
,I/jxcore-log( 6921): getBuffer is called!!!!
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): ****TEST TOOK:  5265  ms ****
I/jxcore-log( 6921): 
,I/jxcore-log( 6921): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6921): 


HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 5746): Initializing JXcore engine
W/jxcore-log( 5746): JXcore engine is ready
W/jxcore-log( 5746): Starting JXcore engine
W/jxcore-log( 5746): Platform android
W/jxcore-log( 5746): 
W/jxcore-log( 5746): Process ARCH arm
W/jxcore-log( 5746): 
I/jxcore-log( 5746): JXcore Cordova bridge is ready!
I/jxcore-log( 5746): 
W/jxcore-log( 5746): JXcore engine is started
,E/jxcore-log( 5746): >> HTC-HTC One_M8,
E/jxcore-log( 5746): 
,I/jxcore-log( 5746): Total memory 1912020992
I/jxcore-log( 5746): 
I/jxcore-log( 5746): Free memory 148471808
I/jxcore-log( 5746): 
I/jxcore-log( 5746): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5746): 
I/jxcore-log( 5746): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5746): 
,I/jxcore-log( 5746): userPath [ 'www' ],
I/jxcore-log( 5746): 
I/jxcore-log( 5746): Size 1080 1776
I/jxcore-log( 5746): 
,I/jxcore-log( 5746): Screen Brightness 142
I/jxcore-log( 5746): 
E/jxcore-log( 5746): Dummy Error Log.
E/jxcore-log( 5746): 
,I/jxcore-log( 5746): getBuffer is called!!!!
I/jxcore-log( 5746): 
,I/jxcore-log( 5746): ****TEST TOOK:  5069  ms ****,
I/jxcore-log( 5746): 
I/jxcore-log( 5746): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5746): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,TIME-OUT KILL (timeout was 150000ms)

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
Error: problem stopping Android apk(com.example.hello) to device 7970f88c error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device FA55PYS00566 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 022678fb504e29b0 error: device not found
 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 6522): Initializing JXcore engine
W/jxcore-log( 6522): JXcore engine is ready
,W/jxcore-log( 6522): Starting JXcore engine
,W/jxcore-log( 6522): Platform android
W/jxcore-log( 6522): 
W/jxcore-log( 6522): Process ARCH arm
W/jxcore-log( 6522): 
,I/jxcore-log( 6522): JXcore Cordova bridge is ready!
I/jxcore-log( 6522): 
,W/jxcore-log( 6522): JXcore engine is started
,E/jxcore-log( 6522): >> samsung-SM-A300FU
E/jxcore-log( 6522): 
,I/jxcore-log( 6522): Total memory 1451114496
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): Free memory 25567232
I/jxcore-log( 6522): 
I/jxcore-log( 6522): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6522): 
I/jxcore-log( 6522): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): userPath [ 'www' ]
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): Size 540 960
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): Screen Brightness 160
I/jxcore-log( 6522): 
,E/jxcore-log( 6522): Dummy Error Log.
E/jxcore-log( 6522): 
,I/jxcore-log( 6522): getBuffer is called!!!!
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): ****TEST TOOK:  5092  ms ****
I/jxcore-log( 6522): 
,I/jxcore-log( 6522): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6522): 


HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 5214): Initializing JXcore engine
W/jxcore-log( 5214): JXcore engine is ready
W/jxcore-log( 5214): Starting JXcore engine
,W/jxcore-log( 5214): Platform android,
W/jxcore-log( 5214): 
W/jxcore-log( 5214): Process ARCH arm
W/jxcore-log( 5214): 
,I/jxcore-log( 5214): JXcore Cordova bridge is ready!
I/jxcore-log( 5214): 
,W/jxcore-log( 5214): JXcore engine is started
,E/jxcore-log( 5214): >> HTC-HTC One M8s,
E/jxcore-log( 5214): 
,I/jxcore-log( 5214): Total memory 1931808768
I/jxcore-log( 5214): 
I/jxcore-log( 5214): Free memory 86142976
I/jxcore-log( 5214): 
I/jxcore-log( 5214): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5214): 
I/jxcore-log( 5214): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5214): 
,I/jxcore-log( 5214): userPath [ 'www' ],
I/jxcore-log( 5214): 
,I/jxcore-log( 5214): Size 1080 1776,
I/jxcore-log( 5214): 
I/jxcore-log( 5214): Screen Brightness 142
I/jxcore-log( 5214): 
,E/jxcore-log( 5214): Dummy Error Log.
E/jxcore-log( 5214): 
,I/jxcore-log( 5214): getBuffer is called!!!!,
I/jxcore-log( 5214): 
,I/jxcore-log( 5214): ****TEST TOOK:  5260  ms ****,
I/jxcore-log( 5214): 
I/jxcore-log( 5214): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5214): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 4660): Initializing JXcore engine
W/jxcore-log( 4660): JXcore engine is ready
W/jxcore-log( 4660): Starting JXcore engine
,W/jxcore-log( 4660): Platform android
W/jxcore-log( 4660): 
,W/jxcore-log( 4660): Process ARCH arm
W/jxcore-log( 4660): 
,I/jxcore-log( 4660): JXcore Cordova bridge is ready!
I/jxcore-log( 4660): 
,W/jxcore-log( 4660): JXcore engine is started
,E/jxcore-log( 4660): >> LGE-LG-D802
E/jxcore-log( 4660): 
,I/jxcore-log( 4660): Total memory 1943035904
I/jxcore-log( 4660): 
I/jxcore-log( 4660): Free memory 418758656
I/jxcore-log( 4660): 
I/jxcore-log( 4660): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): userPath [ 'www' ]
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): Size 1080 1776
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): Screen Brightness 255
I/jxcore-log( 4660): 
,E/jxcore-log( 4660): Dummy Error Log.
E/jxcore-log( 4660): 
,I/jxcore-log( 4660): getBuffer is called!!!!
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): ****TEST TOOK:  5143  ms ****
I/jxcore-log( 4660): 
,I/jxcore-log( 4660): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4660): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Error! Unexpected exit on device f56ad48d app:com.example.hello code:0 
child process exited with code 0 on device f56ad48d 
Device test finished on c5afcdcb 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device c5afcdcb error: device not found
 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6323): Initializing JXcore engine
W/jxcore-log( 6323): JXcore engine is ready
,W/jxcore-log( 6323): Starting JXcore engine
,W/jxcore-log( 6323): Platform android
W/jxcore-log( 6323): 
W/jxcore-log( 6323): Process ARCH arm
W/jxcore-log( 6323): 
,I/jxcore-log( 6323): JXcore Cordova bridge is ready!
I/jxcore-log( 6323): 
,W/jxcore-log( 6323): JXcore engine is started
,E/jxcore-log( 6323): >> samsung-SM-G900F
E/jxcore-log( 6323): 
,I/jxcore-log( 6323): Total memory 1787449344
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): Free memory 61964288
I/jxcore-log( 6323): 
I/jxcore-log( 6323): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6323): 
I/jxcore-log( 6323): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): Size 1080 1920
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): Screen Brightness 134
I/jxcore-log( 6323): 
,E/jxcore-log( 6323): Dummy Error Log.
E/jxcore-log( 6323): 
,I/jxcore-log( 6323): getBuffer is called!!!!
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 6323): 
,I/jxcore-log( 6323): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6323): 


samsung-SM-A500FU: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 3833): Initializing JXcore engine
W/jxcore-log( 3833): JXcore engine is ready
,W/jxcore-log( 3833): Starting JXcore engine
,W/jxcore-log( 3833): Platform android
W/jxcore-log( 3833): 
W/jxcore-log( 3833): Process ARCH arm
W/jxcore-log( 3833): 
,I/jxcore-log( 3833): JXcore Cordova bridge is ready!
I/jxcore-log( 3833): 
,W/jxcore-log( 3833): JXcore engine is started
,E/jxcore-log( 3833): >> samsung-SM-A500FU
E/jxcore-log( 3833): 
,I/jxcore-log( 3833): Total memory 1983787008
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): Free memory 38957056
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3833): 
I/jxcore-log( 3833): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): Size 720 1280
I/jxcore-log( 3833): 
,I/jxcore-log( 3833): Screen Brightness 255
I/jxcore-log( 3833): 
,E/jxcore-log( 3833): Dummy Error Log.
E/jxcore-log( 3833): 
,I/jxcore-log( 3833): getBuffer is called!!!!
I/jxcore-log( 3833): 


```

####Node name: thali08
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/476722347fc8662/build_android/android_0_476722347fc8662.apk) to device 4325e43f protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_476722347fc8662.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device CC51WYC03425 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 0c6a0f3c0bdb4e77 error: device not found
 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log( 3216): Initializing JXcore engine
W/jxcore-log( 3216): JXcore engine is ready
W/jxcore-log( 3216): Starting JXcore engine
W/jxcore-log( 3216): Platform android
W/jxcore-log( 3216): 
W/jxcore-log( 3216): Process ARCH arm
W/jxcore-log( 3216): 
I/jxcore-log( 3216): JXcore Cordova bridge is ready!
I/jxcore-log( 3216): 
W/jxcore-log( 3216): JXcore engine is started
E/jxcore-log( 3216): >> HTC-HTC Desire 820
E/jxcore-log( 3216): 
I/jxcore-log( 3216): Total memory 1964650496
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Free memory 660348928
I/jxcore-log( 3216): 
I/jxcore-log( 3216): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3216): 
I/jxcore-log( 3216): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3216): 
I/jxcore-log( 3216): userPath [ 'www' ]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Size 720 1184
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Screen Brightness 142
I/jxcore-log( 3216): 
E/jxcore-log( 3216): Dummy Error Log.
E/jxcore-log( 3216): 
,I/jxcore-log( 3216): getBuffer is called!!!!
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ****TEST TOOK:  5124  ms ****
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3216): 


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 2276): Initializing JXcore engine
,W/jxcore-log( 2276): JXcore engine is ready
,W/jxcore-log( 2276): Starting JXcore engine
,W/jxcore-log( 2276): Platform android
W/jxcore-log( 2276): 
,W/jxcore-log( 2276): Process ARCH arm
W/jxcore-log( 2276): 
,I/jxcore-log( 2276): JXcore Cordova bridge is ready!
I/jxcore-log( 2276): 
,W/jxcore-log( 2276): JXcore engine is started
,E/jxcore-log( 2276): >> LGE-Nexus 5
E/jxcore-log( 2276): 
,I/jxcore-log( 2276): Total memory 1945137152
I/jxcore-log( 2276): 
I/jxcore-log( 2276): Free memory 882692096
I/jxcore-log( 2276): 
I/jxcore-log( 2276): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): userPath [ 'www' ]
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): Size 1080 1776
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): Screen Brightness 82
I/jxcore-log( 2276): 
,E/jxcore-log( 2276): Dummy Error Log.
E/jxcore-log( 2276): 
,I/jxcore-log( 2276): getBuffer is called!!!!
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): ****TEST TOOK:  5063  ms ****
I/jxcore-log( 2276): 
,I/jxcore-log( 2276): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2276): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_476722347fc8662/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":20,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 20, cancel: 1 } }


```

