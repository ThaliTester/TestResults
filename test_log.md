#### Test 476722341143541 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_476722341143541/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }



android : false
```


###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2D3F6949-0C92-463D-BE53-5E28CC729FC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D3F6949-0C92-463D-BE53-5E28CC729FC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7C27C3F-2CA7-417A-9B1A-02208CAD6B06/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51961"
,(lldb)     command script import "/tmp/2D3F6949-0C92-463D-BE53-5E28CC729FC4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 14:59:41.674 HelloWorld[224:18484] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B1358EA3-FCAD-4B80-BEEC-CFDC376101A4/Library/Cookies/Cookies.binarycookies
,2015-10-22 14:59:42.035 HelloWorld[224:18484] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 14:59:42.036 HelloWorld[224:18484] Multi-tasking -> Device: YES, App: YES
,2015-10-22 14:59:42.039 HelloWorld[224:18484] Unlimited access to network resources
,2015-10-22 14:59:42.045 HelloWorld[224:18484] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 14:59:45.783 HelloWorld[224:18484] Resetting plugins due to page load.
,2015-10-22 14:59:46.141 HelloWorld[224:18484] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F7C27C3F-2CA7-417A-9B1A-02208CAD6B06/HelloWorld.app/www/index.html
,2015-10-22 14:59:46.237 HelloWorld[224:18484] JXcore Cordova plugin initializing
2015-10-22 14:59:46.239 HelloWorld[224:18595] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
,Free memory 202022912
,execPath /private/var/mobile/Containers/Bundle/Application/F7C27C3F-2CA7-417A-9B1A-02208CAD6B06/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/F7C27C3F-2CA7-417A-9B1A-02208CAD6B06/HelloWorld.app/www/jxcore/
userPath []
,2015-10-22 14:59:46.509 HelloWorld[224:18595] Native method ScreenInfo not found.
2015-10-22 14:59:46.510 HelloWorld[224:18595] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5113  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/802C196E-A204-42CD-B810-8FEC261AA7DD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/802C196E-A204-42CD-B810-8FEC261AA7DD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/7BEC218E-E274-468B-89EF-056DD7ABC004/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51965"
,(lldb)     command script import "/tmp/802C196E-A204-42CD-B810-8FEC261AA7DD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 15:00:28.121 HelloWorld[621:60b] Apache Cordova native platform version 3.9.1 is starting.
2015-10-22 15:00:28.126 HelloWorld[621:60b] Multi-tasking -> Device: YES, App: YES
2015-10-22 15:00:28.132 HelloWorld[621:60b] Unlimited access to netwo,rk resources
,2015-10-22 15:00:28.139 HelloWorld[621:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 15:00:39.035 HelloWorld[621:60b] Resetting plugins due to page load.
,2015-10-22 15:00:39.870 HelloWorld[621:60b] Finished load of: file:///var/mobile/Applications/7BEC218E-E274-468B-89EF-056DD7ABC004/HelloWorld.app/www/index.html
,2015-10-22 15:00:39.934 HelloWorld[621:60b] JXcore Cordova plugin initializing
,2015-10-22 15:00:39.936 HelloWorld[621:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 598872064
execPath /private/var/mobile/Applications/7BEC218E-E274-468B-89EF-056DD7ABC004/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/7BEC218E-E274-468B-89EF-056DD7ABC004/HelloWorld.app/www/jxcore/
userPath []
,2015-10-22 15:00:40.413 HelloWorld[621:6607] Native method ScreenInfo not found.
,2015-10-22 15:00:40.415 HelloWorld[621:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5259  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6B120CB3-6D35-4946-BCFA-627F5108E0E7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6B120CB3-6D35-4946-BCFA-627F5108E0E7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38276470-125D-42D6-A084-96431B130D8D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51960"
,(lldb)     command script import "/tmp/6B120CB3-6D35-4946-BCFA-627F5108E0E7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 14:59:42.102 HelloWorld[1189:970367] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/47979462-D307-4203-B80C-4541FA3C51EA/Library/Cookies/Cookies.binarycookies
,2015-10-22 14:59:42.472 HelloWorld[1189:970367] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 14:59:42.473 HelloWorld[1189:970367] Multi-tasking -> Device: YES, App: YES
,2015-10-22 14:59:42.475 HelloWorld[1189:970367] Unlimited access to network resources
,2015-10-22 14:59:42.480 HelloWorld[1189:970367] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 14:59:46.031 HelloWorld[1189:970367] Resetting plugins due to page load.
,2015-10-22 14:59:46.392 HelloWorld[1189:970367] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/38276470-125D-42D6-A084-96431B130D8D/HelloWorld.app/www/index.html
,2015-10-22 14:59:46.434 HelloWorld[1189:970367] JXcore Cordova plugin initializing
,2015-10-22 14:59:46.436 HelloWorld[1189:970489] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
,Free memory 171692032
execPath /private/var/mobile/Containers/Bundle/Application/38276470-125D-42D6-A084-96431B130D8D/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/38276470-125D-42D6-A084-96431B130D8D/HelloWorld.,app/www/jxcore/
userPath []
2015-10-22 14:59:46.639 HelloWorld[1189:970489] Native method ScreenInfo not found.
2015-10-22 14:59:46.640 HelloWorld[1189:970489] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5109  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/494CDCF2-EEFE-41F5-A67D-1CA2C3CA3E09/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/494CDCF2-EEFE-41F5-A67D-1CA2C3CA3E09/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722341143541/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/571EB3B8-73A7-4394-89C3-9DFA823DC8D9/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51959"
,(lldb)     command script import "/tmp/494CDCF2-EEFE-41F5-A67D-1CA2C3CA3E09/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 14:59:48.105 HelloWorld[845:1225363] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5E60648C-BE73-4CEF-AAA2-F58BD9EDC68B/Library/Cookies/Cookies.binarycookies
,2015-10-22 14:59:48.536 HelloWorld[845:1225363] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 14:59:48.537 HelloWorld[845:1225363] Multi-tasking -> Device: YES, App: YES
,2015-10-22 14:59:48.547 HelloWorld[845:1225363] Unlimited access to network resources
,2015-10-22 14:59:48.558 HelloWorld[845:1225363] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 14:59:57.640 HelloWorld[845:1225363] Resetting plugins due to page load.
,2015-10-22 15:00:01.147 HelloWorld[845:1225363] Finished load of: file:///var/mobile/Containers/Bundle/Application/571EB3B8-73A7-4394-89C3-9DFA823DC8D9/HelloWorld.app/www/index.html
,2015-10-22 15:00:01.205 HelloWorld[845:1225363] JXcore Cordova plugin initializing
,2015-10-22 15:00:01.206 HelloWorld[845:1225569] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 306364416
,execPath /private/var/mobile/Containers/Bundle/Application/571EB3B8-73A7-4394-89C3-9DFA823DC8D9/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/571EB3B8-73A7-4394-89C3-9DFA823DC8D9/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-22 15:00:01.394 HelloWorld[845:1225569] Native method ScreenInfo not found.
2015-10-22 15:00:01.395 HelloWorld[845:1225569] Native method ScreenBrightness not found.
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
  '/home/pi/Test/server_476722341143541/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }


```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Device test finished on LGH8153b36be34 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(24200): Initializing JXcore engine
W/jxcore-log(24200): JXcore engine is ready
W/jxcore-log(24200): Starting JXcore engine
W/jxcore-log(24200): Platform android
W/jxcore-log(24200): 
W/jxcore-log(24200): Process ARCH arm
W/jxcore-log(24200): 
I/jxcore-log(24200): JXcore Cordova bridge is ready!
I/jxcore-log(24200): 
W/jxcore-log(24200): JXcore engine is started
E/jxcore-log(24200): >> samsung-SM-G920F
E/jxcore-log(24200): 
I/jxcore-log(24200): Total memory 2829074432
I/jxcore-log(24200): 
I/jxcore-log(24200): Free memory 233201664
I/jxcore-log(24200): 
I/jxcore-log(24200): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24200): 
I/jxcore-log(24200): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(24200): 
I/jxcore-log(24200): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(24200): 
I/jxcore-log(24200): Size 1440 2560
I/jxcore-log(24200): 
I/jxcore-log(24200): Screen Brightness 255
I/jxcore-log(24200): 
E/jxcore-log(24200): Dummy Error Log.
E/jxcore-log(24200): 
,I/jxcore-log(24200): getBuffer is called!!!!
I/jxcore-log(24200): 
,I/jxcore-log(24200): ****TEST TOOK:  5148  ms ****
I/jxcore-log(24200): 
,I/jxcore-log(24200): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(24200): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(25636): Initializing JXcore engine
W/jxcore-log(25636): JXcore engine is ready
W/jxcore-log(25636): Starting JXcore engine
,W/jxcore-log(25636): Platform android
W/jxcore-log(25636): 
W/jxcore-log(25636): Process ARCH arm
W/jxcore-log(25636): 
I/jxcore-log(25636): JXcore Cordova bridge is ready!
I/jxcore-log(25636): 
W/jxcore-log(25636): JXcore engine is started
E/jxcore-log(25636): >> samsung-SM-T232
E/jxcore-log(25636): 
I/jxcore-log(25636): Total memory 1352024064
I/jxcore-log(25636): 
I/jxcore-log(25636): Free memory 100937728
I/jxcore-log(25636): 
I/jxcore-log(25636): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25636): 
I/jxcore-log(25636): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25636): 
I/jxcore-log(25636): userPath [ 'www' ]
I/jxcore-log(25636): 
I/jxcore-log(25636): Size 800 1280
I/jxcore-log(25636): 
I/jxcore-log(25636): Screen Brightness 255
I/jxcore-log(25636): 
E/jxcore-log(25636): Dummy Error Log.
E/jxcore-log(25636): 
,I/jxcore-log(25636): getBuffer is called!!!!
I/jxcore-log(25636): 
,I/jxcore-log(25636): ****TEST TOOK:  5223  ms ****
I/jxcore-log(25636): 
,I/jxcore-log(25636): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25636): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15605): Initializing JXcore engine
W/jxcore-log(15605): JXcore engine is ready
,W/jxcore-log(15605): Starting JXcore engine
,W/jxcore-log(15605): Platform android
W/jxcore-log(15605): 
W/jxcore-log(15605): Process ARCH arm
W/jxcore-log(15605): 
,I/jxcore-log(15605): JXcore Cordova bridge is ready!
I/jxcore-log(15605): 
,W/jxcore-log(15605): JXcore engine is started
,E/jxcore-log(15605): >> LGE-LG-H815
E/jxcore-log(15605): 
,I/jxcore-log(15605): Total memory 2968948736
I/jxcore-log(15605): 
,I/jxcore-log(15605): Free memory 445480960
I/jxcore-log(15605): 
I/jxcore-log(15605): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15605): 
I/jxcore-log(15605): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15605): 
,I/jxcore-log(15605): userPath [ 'www' ]
I/jxcore-log(15605): 
,I/jxcore-log(15605): Size 1440 2392
I/jxcore-log(15605): 
,I/jxcore-log(15605): Screen Brightness 255
I/jxcore-log(15605): 
,E/jxcore-log(15605): Dummy Error Log.
E/jxcore-log(15605): 
,I/jxcore-log(15605): getBuffer is called!!!!
I/jxcore-log(15605): 
,I/jxcore-log(15605): ****TEST TOOK:  5086  ms ****,
I/jxcore-log(15605): 
I/jxcore-log(15605): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15605): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log( 3287): Initializing JXcore engine
W/jxcore-log( 3287): JXcore engine is ready
W/jxcore-log( 3287): Starting JXcore engine
W/jxcore-log( 3287): Platform android
W/jxcore-log( 3287): 
W/jxcore-log( 3287): Process ARCH arm
W/jxcore-log( 3287): 
I/jxcore-log( 3287): JXcore Cordova bridge is ready!
I/jxcore-log( 3287): 
W/jxcore-log( 3287): JXcore engine is started
,E/jxcore-log( 3287): >> HUAWEI-ALE-L21
E/jxcore-log( 3287): 
I/jxcore-log( 3287): Total memory 1949741056
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Free memory 126255104
I/jxcore-log( 3287): 
I/jxcore-log( 3287): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3287): 
I/jxcore-log( 3287): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3287): 
I/jxcore-log( 3287): userPath [ 'www' ]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Size 720 1184
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Screen Brightness 242
I/jxcore-log( 3287): 
E/jxcore-log( 3287): Dummy Error Log.
E/jxcore-log( 3287): 
I/jxcore-log( 3287): getBuffer is called!!!!
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): ****TEST TOOK:  5115  ms ****
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3287): 


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
,W/jxcore-log( 1547): Initializing JXcore engine
W/jxcore-log( 1547): JXcore engine is ready
,W/jxcore-log( 1547): Starting JXcore engine
,W/jxcore-log( 1547): Platform android
W/jxcore-log( 1547): 
W/jxcore-log( 1547): Process ARCH arm
W/jxcore-log( 1547): 
,I/jxcore-log( 1547): JXcore Cordova bridge is ready!
I/jxcore-log( 1547): 
,W/jxcore-log( 1547): JXcore engine is started
,E/jxcore-log( 1547): >> LGE-Nexus 5
E/jxcore-log( 1547): 
I/jxcore-log( 1547): Total memory 1946181632
I/jxcore-log( 1547): 
I/jxcore-log( 1547): Free memory 347586560
I/jxcore-log( 1547): 
I/jxcore-log( 1547): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1547): 
I/jxcore-log( 1547): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1547): 
I/jxcore-log( 1547): userPath [ 'www' ]
I/jxcore-log( 1547): 
,I/jxcore-log( 1547): Size 1080 1776
I/jxcore-log( 1547): 
,I/jxcore-log( 1547): Screen Brightness 82
I/jxcore-log( 1547): 
,E/jxcore-log( 1547): Dummy Error Log.
E/jxcore-log( 1547): 
,I/jxcore-log( 1547): getBuffer is called!!!!
I/jxcore-log( 1547): 
,I/jxcore-log( 1547): ****TEST TOOK:  5144  ms ****
I/jxcore-log( 1547): 
I/jxcore-log( 1547): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1547): 


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(15200): Initializing JXcore engine
W/jxcore-log(15200): JXcore engine is ready
,W/jxcore-log(15200): Starting JXcore engine
,W/jxcore-log(15200): Platform android
W/jxcore-log(15200): 
,W/jxcore-log(15200): Process ARCH arm
W/jxcore-log(15200): 
I/jxcore-log(15200): JXcore Cordova bridge is ready!
I/jxcore-log(15200): 
W/jxcore-log(15200): JXcore engine is started
,E/jxcore-log(15200): >> LGE-LG-D722
E/jxcore-log(15200): 
,I/jxcore-log(15200): Total memory 906309632
I/jxcore-log(15200): 
I/jxcore-log(15200): Free memory 26320896
I/jxcore-log(15200): 
I/jxcore-log(15200): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15200): 
I/jxcore-log(15200): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15200): 
I/jxcore-log(15200): userPath [ 'www' ]
I/jxcore-log(15200): 
I/jxcore-log(15200): Size 720 1196
I/jxcore-log(15200): 
,I/jxcore-log(15200): Screen Brightness 255
I/jxcore-log(15200): 
E/jxcore-log(15200): Dummy Error Log.
E/jxcore-log(15200): 
,I/jxcore-log(15200): getBuffer is called!!!!
I/jxcore-log(15200): 
,I/jxcore-log(15200): ****TEST TOOK:  5221  ms ****
I/jxcore-log(15200): 
,I/jxcore-log(15200): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15200): 


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
,W/jxcore-log(18547): Initializing JXcore engine
,W/jxcore-log(18547): JXcore engine is ready
,W/jxcore-log(18547): Starting JXcore engine
,W/jxcore-log(18547): Platform android
W/jxcore-log(18547): 
,W/jxcore-log(18547): Process ARCH arm
W/jxcore-log(18547): 
,I/jxcore-log(18547): JXcore Cordova bridge is ready!
I/jxcore-log(18547): 
,W/jxcore-log(18547): JXcore engine is started
,E/jxcore-log(18547): >> motorola-XT1039
E/jxcore-log(18547): 
,I/jxcore-log(18547): Total memory 893136896
I/jxcore-log(18547): 
I/jxcore-log(18547): Free memory 119390208
I/jxcore-log(18547): 
I/jxcore-log(18547): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18547): 
,I/jxcore-log(18547): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18547): 
,I/jxcore-log(18547): userPath [ 'www' ]
I/jxcore-log(18547): 
,I/jxcore-log(18547): Size 720 1184
I/jxcore-log(18547): 
,I/jxcore-log(18547): Screen Brightness 210
I/jxcore-log(18547): 
,E/jxcore-log(18547): Dummy Error Log.
E/jxcore-log(18547): 
,I/jxcore-log(18547): getBuffer is called!!!!
I/jxcore-log(18547): 
,I/jxcore-log(18547): ****TEST TOOK:  5192  ms ****
I/jxcore-log(18547): 
,I/jxcore-log(18547): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18547): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 1622): Initializing JXcore engine
,W/jxcore-log( 1622): JXcore engine is ready
,W/jxcore-log( 1622): Starting JXcore engine
,W/jxcore-log( 1622): Platform android
W/jxcore-log( 1622): 
,W/jxcore-log( 1622): Process ARCH arm
W/jxcore-log( 1622): 
,I/jxcore-log( 1622): JXcore Cordova bridge is ready!
I/jxcore-log( 1622): 
,W/jxcore-log( 1622): JXcore engine is started
,E/jxcore-log( 1622): >> LGE-LG-D855
E/jxcore-log( 1622): 
,I/jxcore-log( 1622): Total memory 2995761152
I/jxcore-log( 1622): 
,I/jxcore-log( 1622): Free memory 388960256
I/jxcore-log( 1622): 
I/jxcore-log( 1622): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1622): 
,I/jxcore-log( 1622): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1622): 
,I/jxcore-log( 1622): userPath [ 'www' ]
I/jxcore-log( 1622): 
,I/jxcore-log( 1622): Size 1440 2392
I/jxcore-log( 1622): 
I/jxcore-log( 1622): Screen Brightness 177
I/jxcore-log( 1622): 
,E/jxcore-log( 1622): Dummy Error Log.
E/jxcore-log( 1622): 
,I/jxcore-log( 1622): getBuffer is called!!!!
I/jxcore-log( 1622): 
,I/jxcore-log( 1622): ****TEST TOOK:  5239  ms ****
I/jxcore-log( 1622): 
I/jxcore-log( 1622): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1622): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(26515): Initializing JXcore engine
W/jxcore-log(26515): JXcore engine is ready
W/jxcore-log(26515): Starting JXcore engine
,W/jxcore-log(26515): Platform android
W/jxcore-log(26515): 
,W/jxcore-log(26515): Process ARCH arm
W/jxcore-log(26515): 
,I/jxcore-log(26515): JXcore Cordova bridge is ready!
I/jxcore-log(26515): 
,W/jxcore-log(26515): JXcore engine is started
,E/jxcore-log(26515): >> samsung-SM-G800F
E/jxcore-log(26515): 
,I/jxcore-log(26515): Total memory 1319530496
I/jxcore-log(26515): 
,I/jxcore-log(26515): Free memory 33841152
I/jxcore-log(26515): 
I/jxcore-log(26515): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26515): 
,I/jxcore-log(26515): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26515): 
,I/jxcore-log(26515): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Size 720 1280
I/jxcore-log(26515): 
,I/jxcore-log(26515): Screen Brightness 255
I/jxcore-log(26515): 
,E/jxcore-log(26515): Dummy Error Log.
E/jxcore-log(26515): 
,I/jxcore-log(26515): getBuffer is called!!!!
I/jxcore-log(26515): 
,I/jxcore-log(26515): ****TEST TOOK:  5177  ms ****
I/jxcore-log(26515): 
I/jxcore-log(26515): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26515): 


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(20159): Initializing JXcore engine
W/jxcore-log(20159): JXcore engine is ready
,W/jxcore-log(20159): Starting JXcore engine
,W/jxcore-log(20159): Platform android
W/jxcore-log(20159): 
,W/jxcore-log(20159): Process ARCH arm
W/jxcore-log(20159): 
,I/jxcore-log(20159): JXcore Cordova bridge is ready!
I/jxcore-log(20159): 
,W/jxcore-log(20159): JXcore engine is started
,E/jxcore-log(20159): >> motorola-XT1072
E/jxcore-log(20159): 
,I/jxcore-log(20159): Total memory 916258816
,I/jxcore-log(20159): 
I/jxcore-log(20159): Free memory 63127552
I/jxcore-log(20159): 
I/jxcore-log(20159): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20159): 
I/jxcore-log(20159): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20159): 
,I/jxcore-log(20159): userPath [ 'www' ]
I/jxcore-log(20159): 
,I/jxcore-log(20159): Size 720 1184
I/jxcore-log(20159): 
,I/jxcore-log(20159): Screen Brightness 82
I/jxcore-log(20159): 
E/jxcore-log(20159): Dummy Error Log.
E/jxcore-log(20159): 
,I/jxcore-log(20159): getBuffer is called!!!!
I/jxcore-log(20159): 
,I/jxcore-log(20159): ****TEST TOOK:  5192  ms ****
I/jxcore-log(20159): 
I/jxcore-log(20159): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20159): 


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(10176): Initializing JXcore engine
W/jxcore-log(10176): JXcore engine is ready
W/jxcore-log(10176): Starting JXcore engine
W/jxcore-log(10176): Platform android
W/jxcore-log(10176): 
W/jxcore-log(10176): Process ARCH arm
W/jxcore-log(10176): 
I/jxcore-log(10176): JXcore Cordova bridge is ready!
I/jxcore-log(10176): 
W/jxcore-log(10176): JXcore engine is started
E/jxcore-log(10176): >> samsung-SM-N910C
E/jxcore-log(10176): 
I/jxcore-log(10176): Total memory 2971066368
I/jxcore-log(10176): 
I/jxcore-log(10176): Free memory 336060416
I/jxcore-log(10176): 
I/jxcore-log(10176): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10176): 
I/jxcore-log(10176): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10176): 
I/jxcore-log(10176): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10176): 
I/jxcore-log(10176): Size 1440 2560
I/jxcore-log(10176): 
I/jxcore-log(10176): Screen Brightness 134
I/jxcore-log(10176): 
E/jxcore-log(10176): Dummy Error Log.
E/jxcore-log(10176): 
,I/jxcore-log(10176): getBuffer is called!!!!
I/jxcore-log(10176): 
,I/jxcore-log(10176): ****TEST TOOK:  5138  ms ****
I/jxcore-log(10176): 
,I/jxcore-log(10176): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10176): 


samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
W/jxcore-log( 8322): Initializing JXcore engine
W/jxcore-log( 8322): JXcore engine is ready
W/jxcore-log( 8322): Starting JXcore engine
,W/jxcore-log( 8322): Platform android
W/jxcore-log( 8322): 
W/jxcore-log( 8322): Process ARCH arm
W/jxcore-log( 8322): 
,I/jxcore-log( 8322): JXcore Cordova bridge is ready!
I/jxcore-log( 8322): 
,W/jxcore-log( 8322): JXcore engine is started
,E/jxcore-log( 8322): >> samsung-SM-A500FU
E/jxcore-log( 8322): 
,I/jxcore-log( 8322): Total memory 1983787008
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): Free memory 388767744
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8322): 
I/jxcore-log( 8322): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): Size 720 1280
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): Screen Brightness 255
I/jxcore-log( 8322): 
,E/jxcore-log( 8322): Dummy Error Log.
E/jxcore-log( 8322): 
,I/jxcore-log( 8322): getBuffer is called!!!!
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 8322): 
,I/jxcore-log( 8322): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8322): 


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 8978): Initializing JXcore engine
W/jxcore-log( 8978): JXcore engine is ready
,W/jxcore-log( 8978): Starting JXcore engine
,W/jxcore-log( 8978): Platform android
W/jxcore-log( 8978): 
W/jxcore-log( 8978): Process ARCH arm
W/jxcore-log( 8978): 
,I/jxcore-log( 8978): JXcore Cordova bridge is ready!
I/jxcore-log( 8978): 
,W/jxcore-log( 8978): JXcore engine is started
,E/jxcore-log( 8978): >> samsung-SM-G900F
E/jxcore-log( 8978): 
,I/jxcore-log( 8978): Total memory 1787449344
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): Free memory 49860608
I/jxcore-log( 8978): 
I/jxcore-log( 8978): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8978): 
I/jxcore-log( 8978): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): Size 1080 1920
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): Screen Brightness 255
I/jxcore-log( 8978): 
,E/jxcore-log( 8978): Dummy Error Log.
E/jxcore-log( 8978): 
,I/jxcore-log( 8978): getBuffer is called!!!!
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): ****TEST TOOK:  5213  ms ****
I/jxcore-log( 8978): 
,I/jxcore-log( 8978): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8978): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(18369): Initializing JXcore engine
,W/jxcore-log(18369): JXcore engine is ready
,W/jxcore-log(18369): Starting JXcore engine,
,W/jxcore-log(18369): Platform android,
W/jxcore-log(18369): 
W/jxcore-log(18369): Process ARCH arm
W/jxcore-log(18369): 
,I/jxcore-log(18369): JXcore Cordova bridge is ready!
I/jxcore-log(18369): 
,W/jxcore-log(18369): JXcore engine is started
,E/jxcore-log(18369): >> HTC-HTC One_M8,
E/jxcore-log(18369): 
,I/jxcore-log(18369): Total memory 1912020992,
I/jxcore-log(18369): 
I/jxcore-log(18369): Free memory 375214080
I/jxcore-log(18369): 
I/jxcore-log(18369): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18369): 
I/jxcore-log(18369): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18369): 
,I/jxcore-log(18369): userPath [ 'www' ],
I/jxcore-log(18369): 
,I/jxcore-log(18369): Size 1080 1776
I/jxcore-log(18369): 
,I/jxcore-log(18369): Screen Brightness 142,
I/jxcore-log(18369): 
E/jxcore-log(18369): Dummy Error Log.
E/jxcore-log(18369): 
,I/jxcore-log(18369): getBuffer is called!!!!,
I/jxcore-log(18369): 
,I/jxcore-log(18369): ****TEST TOOK:  5151  ms ****
I/jxcore-log(18369): 
I/jxcore-log(18369): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18369): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21309): Initializing JXcore engine
,W/jxcore-log(21309): JXcore engine is ready
,W/jxcore-log(21309): Starting JXcore engine
,W/jxcore-log(21309): Platform android
W/jxcore-log(21309): 
,W/jxcore-log(21309): Process ARCH arm
W/jxcore-log(21309): 
,I/jxcore-log(21309): JXcore Cordova bridge is ready!
I/jxcore-log(21309): 
,W/jxcore-log(21309): JXcore engine is started
,E/jxcore-log(21309): >> samsung-SM-N9005
E/jxcore-log(21309): 
,I/jxcore-log(21309): Total memory 2971471872
I/jxcore-log(21309): 
,I/jxcore-log(21309): Free memory 300146688
I/jxcore-log(21309): 
I/jxcore-log(21309): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21309): 
I/jxcore-log(21309): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21309): 
,I/jxcore-log(21309): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(21309): 
,I/jxcore-log(21309): Size 1080 1920
I/jxcore-log(21309): 
,I/jxcore-log(21309): Screen Brightness 255
I/jxcore-log(21309): 
,E/jxcore-log(21309): Dummy Error Log.
E/jxcore-log(21309): 
,I/jxcore-log(21309): getBuffer is called!!!!
I/jxcore-log(21309): 
,I/jxcore-log(21309): ****TEST TOOK:  5157  ms ****
I/jxcore-log(21309): 
,I/jxcore-log(21309): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,I/jxcore-log(21309): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 7298): Initializing JXcore engine
W/jxcore-log( 7298): JXcore engine is ready
W/jxcore-log( 7298): Starting JXcore engine
W/jxcore-log( 7298): Platform android
W/jxcore-log( 7298): 
W/jxcore-log( 7298): Process ARCH arm
W/jxcore-log( 7298): 
I/jxcore-log( 7298): JXcore Cordova bridge is ready!
I/jxcore-log( 7298): 
W/jxcore-log( 7298): JXcore engine is started
,E/jxcore-log( 7298): >> motorola-Nexus 6
E/jxcore-log( 7298): 
,I/jxcore-log( 7298): Total memory 3114405888
I/jxcore-log( 7298): 
I/jxcore-log( 7298): Free memory 561606656
I/jxcore-log( 7298): 
I/jxcore-log( 7298): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): userPath [ 'www' ]
I/jxcore-log( 7298): 
I/jxcore-log( 7298): Size 1440 2392
I/jxcore-log( 7298): 
I/jxcore-log( 7298): Screen Brightness 82
I/jxcore-log( 7298): 
E/jxcore-log( 7298): Dummy Error Log.
E/jxcore-log( 7298): 
,I/jxcore-log( 7298): getBuffer is called!!!!
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): ****TEST TOOK:  5130  ms ****
I/jxcore-log( 7298): 
I/jxcore-log( 7298): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7298): 


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(25552): Initializing JXcore engine,
W/jxcore-log(25552): JXcore engine is ready
,W/jxcore-log(25552): Starting JXcore engine,
,W/jxcore-log(25552): Platform android,
W/jxcore-log(25552): 
W/jxcore-log(25552): Process ARCH arm
W/jxcore-log(25552): 
,I/jxcore-log(25552): JXcore Cordova bridge is ready!,
I/jxcore-log(25552): 
W/jxcore-log(25552): JXcore engine is started
,E/jxcore-log(25552): >> HTC-HTC One M8s,
E/jxcore-log(25552): 
,I/jxcore-log(25552): Total memory 1931808768,
I/jxcore-log(25552): 
I/jxcore-log(25552): Free memory 302018560
I/jxcore-log(25552): 
I/jxcore-log(25552): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25552): 
I/jxcore-log(25552): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25552): 
,I/jxcore-log(25552): userPath [ 'www' ],
I/jxcore-log(25552): 
,I/jxcore-log(25552): Size 1080 1776,
I/jxcore-log(25552): 
I/jxcore-log(25552): Screen Brightness 142
I/jxcore-log(25552): 
,E/jxcore-log(25552): Dummy Error Log.
E/jxcore-log(25552): 
,I/jxcore-log(25552): getBuffer is called!!!!
I/jxcore-log(25552): 
,I/jxcore-log(25552): ****TEST TOOK:  5094  ms ****,
I/jxcore-log(25552): 
I/jxcore-log(25552): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25552): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13227): Initializing JXcore engine
W/jxcore-log(13227): JXcore engine is ready
,W/jxcore-log(13227): Starting JXcore engine
,W/jxcore-log(13227): Platform android
W/jxcore-log(13227): 
W/jxcore-log(13227): Process ARCH arm
W/jxcore-log(13227): 
,I/jxcore-log(13227): JXcore Cordova bridge is ready!
I/jxcore-log(13227): 
,W/jxcore-log(13227): JXcore engine is started
,E/jxcore-log(13227): >> samsung-SM-A300FU
E/jxcore-log(13227): 
,I/jxcore-log(13227): Total memory 1451114496,
I/jxcore-log(13227): 
I/jxcore-log(13227): Free memory 128024576
I/jxcore-log(13227): 
I/jxcore-log(13227): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13227): 
I/jxcore-log(13227): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13227): 
,I/jxcore-log(13227): userPath [ 'www' ]
I/jxcore-log(13227): 
,I/jxcore-log(13227): Size 540 960
I/jxcore-log(13227): 
,I/jxcore-log(13227): Screen Brightness 160
I/jxcore-log(13227): 
,E/jxcore-log(13227): Dummy Error Log.
E/jxcore-log(13227): 
,I/jxcore-log(13227): getBuffer is called!!!!
I/jxcore-log(13227): 
,I/jxcore-log(13227): ****TEST TOOK:  5071  ms ****
I/jxcore-log(13227): 
,I/jxcore-log(13227): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13227): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(11498): Initializing JXcore engine
W/jxcore-log(11498): JXcore engine is ready
W/jxcore-log(11498): Starting JXcore engine
W/jxcore-log(11498): Platform android
W/jxcore-log(11498): 
W/jxcore-log(11498): Process ARCH arm
W/jxcore-log(11498): 
I/jxcore-log(11498): JXcore Cordova bridge is ready!
I/jxcore-log(11498): 
W/jxcore-log(11498): JXcore engine is started
E/jxcore-log(11498): >> LGE-LG-D802
E/jxcore-log(11498): 
I/jxcore-log(11498): Total memory 1943035904
I/jxcore-log(11498): 
I/jxcore-log(11498): Free memory 255848448
I/jxcore-log(11498): 
I/jxcore-log(11498): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11498): 
I/jxcore-log(11498): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11498): 
I/jxcore-log(11498): userPath [ 'www' ]
I/jxcore-log(11498): 
I/jxcore-log(11498): Size 1080 1776
I/jxcore-log(11498): 
I/jxcore-log(11498): Screen Brightness 255
I/jxcore-log(11498): 
E/jxcore-log(11498): Dummy Error Log.
E/jxcore-log(11498): 
,I/jxcore-log(11498): getBuffer is called!!!!
I/jxcore-log(11498): 
,I/jxcore-log(11498): ****TEST TOOK:  5144  ms ****
I/jxcore-log(11498): 
,I/jxcore-log(11498): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11498): 


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
--------- beginning of system
,W/jxcore-log(26090): Initializing JXcore engine
W/jxcore-log(26090): JXcore engine is ready
,W/jxcore-log(26090): Starting JXcore engine
,W/jxcore-log(26090): Platform android
W/jxcore-log(26090): 
W/jxcore-log(26090): Process ARCH arm
W/jxcore-log(26090): 
,I/jxcore-log(26090): JXcore Cordova bridge is ready!
I/jxcore-log(26090): 
,W/jxcore-log(26090): JXcore engine is started
,E/jxcore-log(26090): >> samsung-SM-A500FU
E/jxcore-log(26090): 
,I/jxcore-log(26090): Total memory 1983787008
I/jxcore-log(26090): 
,I/jxcore-log(26090): Free memory 367509504
I/jxcore-log(26090): 
I/jxcore-log(26090): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26090): 
I/jxcore-log(26090): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26090): 
,I/jxcore-log(26090): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(26090): 
,I/jxcore-log(26090): Size 720 1280
I/jxcore-log(26090): 
,I/jxcore-log(26090): Screen Brightness 255
I/jxcore-log(26090): 
,E/jxcore-log(26090): Dummy Error Log.
E/jxcore-log(26090): 
,I/jxcore-log(26090): getBuffer is called!!!!
I/jxcore-log(26090): 
,I/jxcore-log(26090): ****TEST TOOK:  5073  ms ****
I/jxcore-log(26090): 
,I/jxcore-log(26090): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26090): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(23425): Initializing JXcore engine
W/jxcore-log(23425): JXcore engine is ready
W/jxcore-log(23425): Starting JXcore engine
,W/jxcore-log(23425): Platform android
W/jxcore-log(23425): 
,W/jxcore-log(23425): Process ARCH arm
W/jxcore-log(23425): 
,I/jxcore-log(23425): JXcore Cordova bridge is ready!
I/jxcore-log(23425): 
,W/jxcore-log(23425): JXcore engine is started
,E/jxcore-log(23425): >> samsung-SM-G900F
E/jxcore-log(23425): 
,I/jxcore-log(23425): Total memory 1787449344
I/jxcore-log(23425): 
,I/jxcore-log(23425): Free memory 68923392
I/jxcore-log(23425): 
I/jxcore-log(23425): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23425): 
I/jxcore-log(23425): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23425): 
,I/jxcore-log(23425): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(23425): 
,I/jxcore-log(23425): Size 1080 1920
I/jxcore-log(23425): 
,I/jxcore-log(23425): Screen Brightness 134
I/jxcore-log(23425): 
,E/jxcore-log(23425): Dummy Error Log.
E/jxcore-log(23425): 
,I/jxcore-log(23425): getBuffer is called!!!!
I/jxcore-log(23425): 
,I/jxcore-log(23425): ****TEST TOOK:  5253  ms ****
I/jxcore-log(23425): 
,I/jxcore-log(23425): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23425): 


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
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3160): Initializing JXcore engine
W/jxcore-log( 3160): JXcore engine is ready
,W/jxcore-log( 3160): Starting JXcore engine
,W/jxcore-log( 3160): Platform android
W/jxcore-log( 3160): 
W/jxcore-log( 3160): Process ARCH arm
W/jxcore-log( 3160): 
,I/jxcore-log( 3160): JXcore Cordova bridge is ready!
I/jxcore-log( 3160): 
,W/jxcore-log( 3160): JXcore engine is started
,E/jxcore-log( 3160): >> samsung-SM-A300FU
E/jxcore-log( 3160): 
,I/jxcore-log( 3160): Total memory 1451114496
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Free memory 270643200
I/jxcore-log( 3160): 
I/jxcore-log( 3160): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): userPath [ 'www' ]
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Size 540 960
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Screen Brightness 255
I/jxcore-log( 3160): 
,E/jxcore-log( 3160): Dummy Error Log.
E/jxcore-log( 3160): 
,I/jxcore-log( 3160): getBuffer is called!!!!
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): ****TEST TOOK:  5080  ms ****
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3160): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 2351): Initializing JXcore engine
,W/jxcore-log( 2351): JXcore engine is ready
,W/jxcore-log( 2351): Starting JXcore engine
,W/jxcore-log( 2351): Platform android
W/jxcore-log( 2351): 
W/jxcore-log( 2351): Process ARCH arm
W/jxcore-log( 2351): 
I/jxcore-log( 2351): JXcore Cordova bridge is ready!
I/jxcore-log( 2351): 
W/jxcore-log( 2351): JXcore engine is started
E/jxcore-log( 2351): >> HTC-HTC Desire 820
E/jxcore-log( 2351): 
I/jxcore-log( 2351): Total memory 1964650496
I/jxcore-log( 2351): 
I/jxcore-log( 2351): Free memory 234995712
I/jxcore-log( 2351): 
I/jxcore-log( 2351): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2351): 
I/jxcore-log( 2351): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2351): 
I/jxcore-log( 2351): userPath [ 'www' ]
I/jxcore-log( 2351): 
I/jxcore-log( 2351): Size 720 1184
I/jxcore-log( 2351): 
I/jxcore-log( 2351): Screen Brightness 10
I/jxcore-log( 2351): 
E/jxcore-log( 2351): Dummy Error Log.
E/jxcore-log( 2351): 
,I/jxcore-log( 2351): getBuffer is called!!!!
I/jxcore-log( 2351): 
,I/jxcore-log( 2351): ****TEST TOOK:  5157  ms ****
I/jxcore-log( 2351): 
,I/jxcore-log( 2351): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2351): 


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
LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 3033): Initializing JXcore engine
W/jxcore-log( 3033): JXcore engine is ready
W/jxcore-log( 3033): Starting JXcore engine
,W/jxcore-log( 3033): Platform android
W/jxcore-log( 3033): 
,W/jxcore-log( 3033): Process ARCH arm
W/jxcore-log( 3033): 
,I/jxcore-log( 3033): JXcore Cordova bridge is ready!
I/jxcore-log( 3033): 
,W/jxcore-log( 3033): JXcore engine is started
,E/jxcore-log( 3033): >> LGE-Nexus 5
E/jxcore-log( 3033): 
,I/jxcore-log( 3033): Total memory 1945137152
I/jxcore-log( 3033): 
I/jxcore-log( 3033): Free memory 45555712
I/jxcore-log( 3033): 
I/jxcore-log( 3033): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3033): 
,I/jxcore-log( 3033): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3033): 
,I/jxcore-log( 3033): userPath [ 'www' ]
I/jxcore-log( 3033): 
,I/jxcore-log( 3033): Size 1080 1776
I/jxcore-log( 3033): 
,I/jxcore-log( 3033): Screen Brightness 82
I/jxcore-log( 3033): 
,E/jxcore-log( 3033): Dummy Error Log.
E/jxcore-log( 3033): 
,W/jxcore-log( 3233): Initializing JXcore engine
,W/jxcore-log( 3233): JXcore engine is ready
,W/jxcore-log( 3233): Starting JXcore engine
,W/jxcore-log( 3233): Platform android
W/jxcore-log( 3233): 
,W/jxcore-log( 3233): Process ARCH arm
W/jxcore-log( 3233): 
,I/jxcore-log( 3233): JXcore Cordova bridge is ready!
I/jxcore-log( 3233): 
,W/jxcore-log( 3233): JXcore engine is started
,E/jxcore-log( 3233): >> LGE-Nexus 5
E/jxcore-log( 3233): 
,I/jxcore-log( 3233): Total memory 1945137152
I/jxcore-log( 3233): 
I/jxcore-log( 3233): Free memory 41074688
I/jxcore-log( 3233): 
I/jxcore-log( 3233): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3233): 
,I/jxcore-log( 3233): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3233): 
,I/jxcore-log( 3233): userPath [ 'www' ]
I/jxcore-log( 3233): 
,I/jxcore-log( 3233): Size 1080 1776
I/jxcore-log( 3233): 
I/jxcore-log( 3233): Screen Brightness 82
I/jxcore-log( 3233): 
,E/jxcore-log( 3233): Dummy Error Log.
E/jxcore-log( 3233): 
,I/jxcore-log( 3233): getBuffer is called!!!!
I/jxcore-log( 3233): 
,I/jxcore-log( 3233): ****TEST TOOK:  5027  ms ****
I/jxcore-log( 3233): 
,I/jxcore-log( 3233): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3233): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(30905): Initializing JXcore engine
,W/jxcore-log(30905): JXcore engine is ready
,W/jxcore-log(30905): Starting JXcore engine
,W/jxcore-log(30905): Platform android
W/jxcore-log(30905): 
,W/jxcore-log(30905): Process ARCH arm
W/jxcore-log(30905): 
,I/jxcore-log(30905): JXcore Cordova bridge is ready!
I/jxcore-log(30905): 
,W/jxcore-log(30905): JXcore engine is started
,E/jxcore-log(30905): >> HTC-HTC Desire 820
E/jxcore-log(30905): 
,I/jxcore-log(30905): Total memory 1964650496
I/jxcore-log(30905): 
I/jxcore-log(30905): Free memory 257523712
I/jxcore-log(30905): 
I/jxcore-log(30905): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30905): 
,I/jxcore-log(30905): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30905): 
,I/jxcore-log(30905): userPath [ 'www' ]
I/jxcore-log(30905): 
,I/jxcore-log(30905): Size 720 1184
I/jxcore-log(30905): 
,I/jxcore-log(30905): Screen Brightness 142
I/jxcore-log(30905): 
,E/jxcore-log(30905): Dummy Error Log.
E/jxcore-log(30905): 
,I/jxcore-log(30905): getBuffer is called!!!!
I/jxcore-log(30905): 
,I/jxcore-log(30905): ****TEST TOOK:  5194  ms ****
I/jxcore-log(30905): 
,I/jxcore-log(30905): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30905): 


```


