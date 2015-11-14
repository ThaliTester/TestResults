#### Test 503880191f8da65 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":21,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_503880191f8da65/serverApp/index.js',
  '{"devices":{"ios":5,"android":21,"cancel":1}}' ]

JSON { devices: { ios: 5, android: 21, cancel: 1 } }



android : false
```


###iOS Logs

```
IpadAir1-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app
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
,(lldb) command source -s 0 '/tmp/339DEC8B-1905-4907-B63B-C73BAAEE0B14/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'
,Executing commands in '/tmp/339DEC8B-1905-4907-B63B-C73BAAEE0B14/fruitstrap-lldb-prep-cmds-72077319a5ba6195ddfb95f3a55e9fa0d62da640'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.3 (12F69)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DB954777-C04C-46F7-82DE-B23FBE3F4BD9/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49441"
,(lldb)     command script import "/tmp/339DEC8B-1905-4907-B63B-C73BAAEE0B14/fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.py"
,(lldb)     command script add -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_72077319a5ba6195ddfb95f3a55e9fa0d62da640.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 01:50:48.207 HelloWorld[219:10702] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5CF6C741-DA11-49E3-94EE-6452C9504571/Library/Cookies/Cookies.binarycookies
,2015-11-14 01:50:48.567 HelloWorld[219:10702] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 01:50:48.568 HelloWorld[219:10702] Multi-tasking -> Device: YES, App: YES
,2015-11-14 01:50:48.572 HelloWorld[219:10702] Unlimited access to network resources
,2015-11-14 01:50:48.577 HelloWorld[219:10702] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 01:50:50.887 HelloWorld[219:10702] Resetting plugins due to page load.
,2015-11-14 01:50:51.087 HelloWorld[219:10702] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/DB954777-C04C-46F7-82DE-B23FBE3F4BD9/HelloWorld.app/www/index.html
,2015-11-14 01:50:51.149 HelloWorld[219:10702] JXcore Cordova plugin initializing
,2015-11-14 01:50:51.150 HelloWorld[219:10790] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir1-1
,Total memory 1022865408
,Free memory 228675584
,execPath /private/var/mobile/Containers/Bundle/Application/DB954777-C04C-46F7-82DE-B23FBE3F4BD9/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/DB954777-C04C-46F7-82DE-B23FBE3F4BD9/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-14 01:50:51.380 HelloWorld[219:10790] Native method ScreenInfo not found.
,2015-11-14 01:50:51.381 HelloWorld[219:10790] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5097  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E01D77CE-8BF5-4E4F-BDDE-B90C1FCA643E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E01D77CE-8BF5-4E4F-BDDE-B90C1FCA643E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5E68AF0B-8A8E-4DEE-80D0-CBEAE176D766/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49435"
,(lldb)     command script import "/tmp/E01D77CE-8BF5-4E4F-BDDE-B90C1FCA643E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 01:50:49.234 HelloWorld[221:12079] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7F8924B9-47D8-45DC-93C5-FE5B0782A766/Library/Cookies/Cookies.binarycookies
,2015-11-14 01:50:49.589 HelloWorld[221:12079] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 01:50:49.591 HelloWorld[221:12079] Multi-tasking -> Device: YES, App: YES
,2015-11-14 01:50:49.594 HelloWorld[221:12079] Unlimited access to network resources
,2015-11-14 01:50:49.599 HelloWorld[221:12079] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 01:50:53.522 HelloWorld[221:12079] Resetting plugins due to page load.
,2015-11-14 01:50:53.733 HelloWorld[221:12079] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5E68AF0B-8A8E-4DEE-80D0-CBEAE176D766/HelloWorld.app/www/index.html
,2015-11-14 01:50:53.781 HelloWorld[221:12079] JXcore Cordova plugin initializing
,2015-11-14 01:50:53.783 HelloWorld[221:12204] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 323399680
execPath /private/var/mobile/Containers/Bundle/Application/5E68AF0B-8A8E-4DEE-80D0-CBEAE176D766/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/5E,68AF0B-8A8E-4DEE-80D0-CBEAE176D766/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 01:50:54.016 HelloWorld[221:12204] Native method ScreenInfo not found.
2015-11-14 01:50:54.016 HelloWorld[221:12204] Native method ScreenBrightness not found.
Dummy Er,ror Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5117  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ABDA738F-450B-437E-B6F6-50BEA50D5886/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ABDA738F-450B-437E-B6F6-50BEA50D5886/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D14B9FBC-7766-4574-891A-6EF2162ABBCF/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49434"
,(lldb)     command script import "/tmp/ABDA738F-450B-437E-B6F6-50BEA50D5886/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 01:50:49.259 HelloWorld[239:12590] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A5F9B6D6-6523-4028-A65C-5234B6EEA44B/Library/Cookies/Cookies.binarycookies
,2015-11-14 01:50:49.648 HelloWorld[239:12590] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 01:50:49.649 HelloWorld[239:12590] Multi-tasking -> Device: YES, App: YES
,2015-11-14 01:50:49.652 HelloWorld[239:12590] Unlimited access to network resources
,2015-11-14 01:50:49.657 HelloWorld[239:12590] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 01:50:53.262 HelloWorld[239:12590] Resetting plugins due to page load.
,2015-11-14 01:50:53.574 HelloWorld[239:12590] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/D14B9FBC-7766-4574-891A-6EF2162ABBCF/HelloWorld.app/www/index.html
,2015-11-14 01:50:53.668 HelloWorld[239:12590] JXcore Cordova plugin initializing
2015-11-14 01:50:53.669 HelloWorld[239:12715] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 236154880
execPath /private/var/mobile/Containers/Bundle/Application/D14B9FBC-7766-4574-891A-6EF2162ABBCF/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/D14,B9FBC-7766-4574-891A-6EF2162ABBCF/HelloWorld.app/www/jxcore/
userPath []
2015-11-14 01:50:53.919 HelloWorld[239:12715] Native method ScreenInfo not found.
2015-11-14 01:50:53.920 HelloWorld[239:12715] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5100  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/909FDF1A-61A1-425E-A4D0-20F5DD8A8E9F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/909FDF1A-61A1-425E-A4D0-20F5DD8A8E9F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/67C3ED04-A54C-4D6A-AB7F-BF357F38BC60/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49438"
,(lldb)     command script import "/tmp/909FDF1A-61A1-425E-A4D0-20F5DD8A8E9F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 01:51:36.535 HelloWorld[173:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 01:51:36.538 HelloWorld[173:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-14 01:51:36.546 HelloWorld[173:60b] Unlimited access to network resources
,2015-11-14 01:51:36.555 HelloWorld[173:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 01:51:47.534 HelloWorld[173:60b] Resetting plugins due to page load.
,2015-11-14 01:51:47.894 HelloWorld[173:60b] Finished load of: file:///var/mobile/Applications/67C3ED04-A54C-4D6A-AB7F-BF357F38BC60/HelloWorld.app/www/index.html
,2015-11-14 01:51:48.431 HelloWorld[173:60b] JXcore Cordova plugin initializing
,2015-11-14 01:51:48.433 HelloWorld[173:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 661733376
execPath /private/var/mobile/Applications/67C3ED04-A54C-4D6A-AB7F-BF357F38BC60/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/67C3ED04-A54C-4D6A-AB7F-BF357F38BC60/HelloWorld.app/www/jxcore/
userPath []
,2015-11-14 01:51:48.881 HelloWorld[173:6707] Native method ScreenInfo not found.
,2015-11-14 01:51:48.883 HelloWorld[173:6707] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5225  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E10CEFB4-647F-4B9E-A0E5-714134C20080/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E10CEFB4-647F-4B9E-A0E5-714134C20080/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880191f8da65/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8124D8F9-DC75-4332-B7BE-48CE67C9399D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49432"
,(lldb)     command script import "/tmp/E10CEFB4-647F-4B9E-A0E5-714134C20080/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-14 01:50:45.954 HelloWorld[249:17046] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C6A44ECD-82A1-481E-B4ED-9B045E8EDBDB/Library/Cookies/Cookies.binarycookies
,2015-11-14 01:50:46.229 HelloWorld[249:17046] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-14 01:50:46.230 HelloWorld[249:17046] Multi-tasking -> Device: YES, App: YES
,2015-11-14 01:50:46.232 HelloWorld[249:17046] Unlimited access to network resources
,2015-11-14 01:50:46.237 HelloWorld[249:17046] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-14 01:50:50.321 HelloWorld[249:17046] Resetting plugins due to page load.
,2015-11-14 01:50:51.612 HelloWorld[249:17046] Finished load of: file:///var/mobile/Containers/Bundle/Application/8124D8F9-DC75-4332-B7BE-48CE67C9399D/HelloWorld.app/www/index.html
,2015-11-14 01:50:51.667 HelloWorld[249:17046] JXcore Cordova plugin initializing
,2015-11-14 01:50:51.668 HelloWorld[249:17220] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 810336256
,execPath /private/var/mobile/Containers/Bundle/Application/8124D8F9-DC75-4332-B7BE-48CE67C9399D/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/8124D8F9-DC75-4332-B7BE-48CE67C9399D/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-14 01:50:51.853 HelloWorld[249:17220] Native method ScreenInfo not found.
,2015-11-14 01:50:51.854 HelloWorld[249:17220] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5107  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":21,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_503880191f8da65/serverApp/index.js',
  '{"devices":{"ios":5,"android":21,"cancel":1}}' ]

JSON { devices: { ios: 5, android: 21, cancel: 1 } }


```

###Android Logs
####Node name: thali01
Console output:
```
Warning: Phone 30049d9501da2100	offline OFFLINE
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of main
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/ActivityManager( 3489): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3489): mDVFSHelper.acquire()
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3489): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9186 uid=10188 gids={50188, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 9186): Added TimaKeyStore provider
V/ActivityManager( 3489): Display changed displayId=0
V/ActivityThread( 4260): updateVisibility : ActivityRecord{12ccfa27 token=android.os.BinderProxy@10b8d66b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,W/ActivityManager( 3489): Activity pause timeout for ActivityRecord{207279f7 u0 com.example.hello/.MainActivity t46}
D/ActivityManager( 3489): post active user change for 0 fullscreen true record.isFloatingActivity() false
V/ActivityThread( 9186): updateVisibility : ActivityRecord{22c7e62 token=android.os.BinderProxy@26826b7c {com.example.hello/com.example.hello.MainActivity}} show : true
I/ActivityManager( 3489): Displayed Component not be shown by security: +901ms
W/ActivityManager( 3489): mDVFSHelper.release()
W/jxcore-log( 9186): Initializing JXcore engine
W/jxcore-log( 9186): JXcore engine is ready
W/jxcore-log( 9186): Starting JXcore engine
W/jxcore-log( 9186): Platform android
W/jxcore-log( 9186): 
W/jxcore-log( 9186): Process ARCH arm
W/jxcore-log( 9186): 
I/jxcore-log( 9186): JXcore Cordova bridge is ready!
I/jxcore-log( 9186): 
W/jxcore-log( 9186): JXcore engine is started
E/jxcore-log( 9186): >> samsung-SM-G920F
E/jxcore-log( 9186): 
I/jxcore-log( 9186): Total memory 2829074432
I/jxcore-log( 9186): 
I/jxcore-log( 9186): Free memory 49909760
I/jxcore-log( 9186): 
I/jxcore-log( 9186): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9186): 
I/jxcore-log( 9186): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9186): 
I/jxcore-log( 9186): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9186): 
I/jxcore-log( 9186): Size 1440 2560
I/jxcore-log( 9186): 
I/jxcore-log( 9186): Screen Brightness 2
I/jxcore-log( 9186): 
E/jxcore-log( 9186): Dummy Error Log.
E/jxcore-log( 9186): 
I/jxcore-log( 9186): getBuffer is called!!!!
I/jxcore-log( 9186): 
,I/jxcore-log( 9186): ****TEST TOOK:  5078  ms ****
I/jxcore-log( 9186): 
,I/jxcore-log( 9186): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9186): 
,I/ActivityManager( 3489): Force stopping com.example.hello appid=10188 user=-1: uninstall pkg
,I/ActivityManager( 3489): Killing 9186:com.example.hello/u0a188 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3489):   Force finishing activity ActivityRecord{207279f7 u0 com.example.hello/.MainActivity t46}
,I/ActivityManager( 3489): Force stopping com.example.hello appid=10188 user=0: pkg removed
,W/ActivityManager( 3489): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9295 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5076, uid=10127 that is not exported from uid 10125
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,D/ActivityThread( 9295): Added TimaKeyStore provider
,I/ActivityManager( 3489): Killing 8567:com.osp.app.signin/u0a37 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9315 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,D/ActivityThread( 9315): Added TimaKeyStore provider
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3489): Killing 8609:com.samsung.android.coreapps/u0a98 (adj 15): empty #25
,D/ActivityThread( 9332): Added TimaKeyStore provider
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9347 uid=10027 gids={50027, 9997, 1028, 1015, 3003, 3002} abi=arm64-v8a
,I/ActivityManager( 3489): Killing 8590:com.android.mms/u0a48 (adj 15): empty #25
,D/ActivityThread( 9347): Added TimaKeyStore provider
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=9366 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 3489): Killing 7550:com.samsung.android.SettingsReceiver/1000 (adj 15): empty #25
,D/ActivityThread( 9366): Added TimaKeyStore provider
,I/ActivityManager( 3489): Killing 8663:com.sec.android.provider.badge/u0a82 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=9387 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 1003} abi=arm64-v8a
,D/ActivityThread( 9387): Added TimaKeyStore provider


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1282): Start proc 8305:com.lge.lgdmsclient/1000 for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver
I/ActivityManager( 1282): Killing 7656:com.lge.gcuv/1000 (adj 15): empty #22
I/ActivityManager( 1282): Start proc 8337:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,I/ActivityManager( 1282): Start proc 8364:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider
I/ActivityManager( 1282): Waited long enough for: ServiceRecord{3061681 u0 com.android.calendar/.alerts.InitAlarmsService}
I/ActivityManager( 1282): Start proc 8396:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
I/ActivityManager( 1282): Killing 7680:com.lge.hiddenmenu/1000 (adj 15): empty #22
I/ActivityManager( 1282): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1282): setTaskToReturnTo : TaskRecord{1ed8bddd #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1282): setTaskToReturnTo : TaskRecord{1ed8bddd #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1282): Start proc 8433:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1282): Killing 7701:com.lge.lgfota.permission/1000 (adj 15): empty #22
I/ActivityManager( 1282): Start proc 8456:com.android.browser/u0a24 for broadcast com.android.browser/com.lge.browser.settings.BrowserSettingReceiver
I/ActivityManager( 1282): Killing 7723:com.lge.springcleaning/1000 (adj 15): empty #22
I/ActivityManager( 1282): Start proc 8508:com.lge.appbox.client:SingleBinaryService/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver
I/ActivityManager( 1282): Killing 7763:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
I/ActivityManager( 1282): Waited long enough for: ServiceRecord{57a634 u0 com.lge.lpd/.service.LPDRegistReceiverService}
I/ActivityManager( 1282): Start proc 8533:com.lge.appbox.client/u0a9 for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider
I/ActivityManager( 1282): Displayed com.example.hello/.MainActivity: +821ms (total +14s328ms)
I/ActivityManager( 1282): Killing 7303:com.lge.lockscreensettings/1000 (adj 15): empty #22
I/ActivityManager( 1282): Start proc 8560:com.android.cellbroadcastreceiver/u0a14 for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver
I/ActivityManager( 1282): Killing 7787:com.android.vending/u0a62 (adj 15): empty #22
,W/jxcore-log( 8433): Initializing JXcore engine
W/jxcore-log( 8433): JXcore engine is ready
,W/jxcore-log( 8433): Starting JXcore engine
,I/ActivityManager( 1282): Start proc 8584:com.android.contacts/u0a18 for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver
,W/jxcore-log( 8433): Platform android
W/jxcore-log( 8433): 
W/jxcore-log( 8433): Process ARCH arm
W/jxcore-log( 8433): 
,I/jxcore-log( 8433): JXcore Cordova bridge is ready!
I/jxcore-log( 8433): 
W/jxcore-log( 8433): JXcore engine is started
,E/jxcore-log( 8433): >> LGE-LG-H815
E/jxcore-log( 8433): 
,I/jxcore-log( 8433): Total memory 2968948736
I/jxcore-log( 8433): 
I/jxcore-log( 8433): Free memory 88154112
I/jxcore-log( 8433): 
I/jxcore-log( 8433): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8433): 
I/jxcore-log( 8433): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8433): 
,I/jxcore-log( 8433): userPath [ 'www' ]
I/jxcore-log( 8433): 
,I/jxcore-log( 8433): Size 1440 2392
I/jxcore-log( 8433): 
,I/jxcore-log( 8433): Screen Brightness 255
I/jxcore-log( 8433): 
,E/jxcore-log( 8433): Dummy Error Log.
E/jxcore-log( 8433): 
,I/ActivityManager( 1282): Start proc 8610:com.lge.email/u0a56 for broadcast com.lge.email/.receiver.EmailSimChangedReceiver
,I/ActivityManager( 1282): Killing 7829:com.google.android.talk/u0a121 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 7864:com.lge.ia.task.incalagent/u0a8 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8636:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
,I/jxcore-log( 8433): getBuffer is called!!!!
I/jxcore-log( 8433): 
,I/ActivityManager( 1282): Start proc 8660:com.android.settings/1000 for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver
,I/ActivityManager( 1282): Killing 7906:com.google.android.gm/u0a113 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 7375:com.google.android.apps.maps/u0a119 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8681:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.SVC.log_service.FactorySIMReceiver
,I/ActivityManager( 1282): Killing 7946:com.google.android.youtube/u0a124 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8701:com.android.providers.partnerbookmarks/u0a103 for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver
,I/ActivityManager( 1282): Start proc 8722:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseSIMObserver
,I/ActivityManager( 1282): Killing 8045:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8743:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1282): Killing 7118:com.android.defcontainer/u0a3 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8767:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,I/ActivityManager( 1282): Start proc 8790:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
,I/ActivityManager( 1282): Killing 8162:com.lge.qmemoplus/1000 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 8206:com.lge.lgaccount/u0a107 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 8227:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8811:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
,I/ActivityManager( 1282): Killing 8249:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 8185:com.lge.lifetracker/u0a137 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8832:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
,I/ActivityManager( 1282): Killing 7885:com.android.providers.calendar/u0a19 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 8337:com.lge.task/u0a20 (adj 15): empty #22
,I/ActivityManager( 1282): Waited long enough for: ServiceRecord{3ebd98b7 u0 com.lge.springcleaning/.service.AppCleanupService}
,I/ActivityManager( 1282): Start proc 8866:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,I/ActivityManager( 1282): Start proc 8886:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,I/ActivityManager( 1282): Start proc 8908:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,I/ActivityManager( 1282): Killing 8075:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1282): Start proc 8943:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.NetworkStatusReceiver
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 8433): ****TEST TOOK:  5078  ms ****
I/jxcore-log( 8433): 
,I/jxcore-log( 8433): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8433): 
,I/ActivityManager( 1282): Killing 8456:com.android.browser/u0a24 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 8988:com.lge.settings.easy/1000 for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver
,I/ActivityManager( 1282): Killing 8508:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 9022:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
,I/ActivityManager( 1282): Force stopping com.example.hello appid=10360 user=0: pkg removed
,I/ActivityManager( 1282): Killing 8433:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1282): Force removing ActivityRecord{22105d52 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1282): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
,W/ActivityManager( 1282): Spurious death for ProcessRecord{11742b05 8433:com.example.hello/u0a360}, curProc for 8433: null
,I/ActivityManager( 1282): Killing 8560:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/ActivityManager( 1282): Start proc 9048:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/ActivityManager( 1282): Killing 8584:com.android.contacts/u0a18 (adj 15): empty #22
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1282): Start proc 9083:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1282): Displayed com.lge.launcher2/.Launcher: +369ms (total +19s813ms)
,I/ActivityManager( 1282): Killing 8681:com.lge.hiddenmenu/1000 (adj 15): empty #22


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2966): filter receiver for action = com.android.providers.calendar.intent.CalendarProvider2
I/ActivityManager( 2966): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
I/ActivityManager( 2966): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2966): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager( 2966): Displayed com.example.hello/.MainActivity: +1s362ms
,W/jxcore-log( 5229): Initializing JXcore engine
W/jxcore-log( 5229): JXcore engine is ready
,W/jxcore-log( 5229): Starting JXcore engine
,W/jxcore-log( 5229): Platform android
W/jxcore-log( 5229): 
W/jxcore-log( 5229): Process ARCH arm
W/jxcore-log( 5229): 
,I/jxcore-log( 5229): JXcore Cordova bridge is ready!
I/jxcore-log( 5229): 
,W/jxcore-log( 5229): JXcore engine is started
,E/jxcore-log( 5229): >> HUAWEI-ALE-L21
E/jxcore-log( 5229): 
,I/jxcore-log( 5229): Total memory 1949741056
I/jxcore-log( 5229): 
,I/jxcore-log( 5229): Free memory 19714048
I/jxcore-log( 5229): 
I/jxcore-log( 5229): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5229): 
I/jxcore-log( 5229): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5229): 
,I/jxcore-log( 5229): userPath [ 'www' ]
I/jxcore-log( 5229): 
,I/jxcore-log( 5229): Size 720 1184
I/jxcore-log( 5229): 
,I/jxcore-log( 5229): Screen Brightness 242
I/jxcore-log( 5229): 
,E/jxcore-log( 5229): Dummy Error Log.
E/jxcore-log( 5229): 
,I/jxcore-log( 5229): getBuffer is called!!!!
I/jxcore-log( 5229): 
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.MEDIA_MOUNTED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.MEDIA_SCANNER_STARTED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.MEDIA_SCANNER_STARTED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 5229): ****TEST TOOK:  5116  ms ****
I/jxcore-log( 5229): 
,I/jxcore-log( 5229): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5229): 
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2966): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2966): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2966): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager( 2966): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


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
LGE-LG-D722: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  846): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3972 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  846): Killing 3705:com.lge.voicerecorder/u0a34 (adj 15): empty #11
I/ActivityManager(  846): Killing 3731:com.lge.drmservice/u0a51 (adj 15): empty #11
I/ActivityManager(  846): Waited long enough for: ServiceRecord{4a0b0cb u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{6494131 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{6494131 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  846): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4014 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  846): Waited long enough for: ServiceRecord{151cfe11 u0 com.lge.sizechangable.weather/.service.WeatherService}
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4100 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  846): Displayed com.example.hello/.MainActivity: +1s191ms
,W/jxcore-log( 4014): Initializing JXcore engine
,W/jxcore-log( 4014): JXcore engine is ready
W/jxcore-log( 4014): Starting JXcore engine
,I/ActivityManager(  846): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4140 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 4014): Platform android
W/jxcore-log( 4014): 
W/jxcore-log( 4014): Process ARCH arm
W/jxcore-log( 4014): 
,I/ActivityManager(  846): Waited long enough for: ServiceRecord{1d5dc6d8 u0 com.google.android.gms/.gcm.GcmService}
I/jxcore-log( 4014): JXcore Cordova bridge is ready!
I/jxcore-log( 4014): 
,W/jxcore-log( 4014): JXcore engine is started
E/jxcore-log( 4014): >> LGE-LG-D722
E/jxcore-log( 4014): 
,I/jxcore-log( 4014): Total memory 906309632
I/jxcore-log( 4014): 
I/jxcore-log( 4014): Free memory 29581312
I/jxcore-log( 4014): 
I/jxcore-log( 4014): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4014): 
I/jxcore-log( 4014): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4014): 
I/jxcore-log( 4014): userPath [ 'www' ]
I/jxcore-log( 4014): 
I/jxcore-log( 4014): Size 720 1196
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): Screen Brightness 255
I/jxcore-log( 4014): 
E/jxcore-log( 4014): Dummy Error Log.
E/jxcore-log( 4014): 
,I/jxcore-log( 4014): getBuffer is called!!!!
I/jxcore-log( 4014): 
,I/ActivityManager(  846): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4235 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Process com.lge.cloudhub (pid 3756) has died
,I/ActivityManager(  846): Process com.android.providers.calendar (pid 3854) has died
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4235): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1f5a2921 that was originally bound here
E/ActivityThread( 4235): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1f5a2921 that was originally bound here
E/ActivityThread( 4235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4235): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4235): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4235): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4235): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4235): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4235): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4235): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4235): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4235): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4235): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4235): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  846): Unbind failed: could not find connection for android.os.BinderProxy@e883791
,I/ActivityManager(  846): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4279 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4304 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 3778:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4350 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  846): Killing 3796:com.lge.lgfota.permission/1000 (adj 15): empty #11
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  846): Killing 3836:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ActivityManager(  846): Killing 3871:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4384 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 3899:com.lge.springcleaning/1000 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4412 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  846): Waited long enough for: ServiceRecord{9d1fa57 u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4433 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4470 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 3937:com.google.android.configupdater/u0a3 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4496 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  846): Killing 3972:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4517 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 4100:com.google.android.talk/u0a61 (adj 15): empty #11
,I/ActivityManager(  846): Killing 4140:com.google.android.youtube/u0a100 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4541 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 4014): ****TEST TOOK:  5172  ms ****
I/jxcore-log( 4014): 
I/jxcore-log( 4014): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4014): 
,I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4562 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 4235:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4603 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 4279:com.lge.bnr/1000 (adj 15): empty #11
,I/ActivityManager(  846): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  846): Killing 4014:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  846): Force removing ActivityRecord{1bf3e016 u0 com.example.hello/.MainActivity t219}: app died, no saved state
,W/ActivityManager(  846): Spurious death for ProcessRecord{18cffe84 4014:com.example.hello/u0a30}, curProc for 4014: null
,I/ActivityManager(  846): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  846): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4630 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 4304:com.android.vending/u0a36 (adj 15): empty #11
,I/ActivityManager(  846): Killing 4350:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/ActivityManager(  846): Waited long enough for: ServiceRecord{1aaf3cb3 u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  846): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4663 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a


LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=1979 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2020 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2091 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2124 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +952ms (total +17s354ms)
,I/ActivityManager(  760): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2211 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 2091): Initializing JXcore engine
W/jxcore-log( 2091): JXcore engine is ready
,W/jxcore-log( 2091): Starting JXcore engine
,W/jxcore-log( 2091): Platform android
W/jxcore-log( 2091): 
,W/jxcore-log( 2091): Process ARCH arm
W/jxcore-log( 2091): 
,I/jxcore-log( 2091): JXcore Cordova bridge is ready!
I/jxcore-log( 2091): 
,W/jxcore-log( 2091): JXcore engine is started
,E/jxcore-log( 2091): >> LGE-Nexus 5
E/jxcore-log( 2091): 
,I/jxcore-log( 2091): Total memory 1946181632
I/jxcore-log( 2091): 
,I/jxcore-log( 2091): Free memory 490524672
I/jxcore-log( 2091): 
I/jxcore-log( 2091): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2091): 
I/jxcore-log( 2091): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2091): 
,I/jxcore-log( 2091): userPath [ 'www' ]
I/jxcore-log( 2091): 
,I/jxcore-log( 2091): Size 1080 1776
I/jxcore-log( 2091): 
,I/jxcore-log( 2091): Screen Brightness 82
I/jxcore-log( 2091): 
,E/jxcore-log( 2091): Dummy Error Log.
E/jxcore-log( 2091): 
,I/ActivityManager(  760): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2246 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2275 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 2091): getBuffer is called!!!!
I/jxcore-log( 2091): 
,I/ActivityManager(  760): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=2323 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2350 uid=10012 gids={50012, 9997} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2375 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2400 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2426 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2460 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2486 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1338:com.android.printspooler/u0a72 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2503 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1654:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  760): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2573 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2665 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1753:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2687 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1979:com.android.musicfx/u0a15 (adj 15): empty #17
,D/ActivityThread( 2687): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  760): Killing 2020:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2713 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2751 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  760): Killing 2211:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2246:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2275:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2780 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 2091): ****TEST TOOK:  5022  ms ****
I/jxcore-log( 2091): 
,I/jxcore-log( 2091): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2091): 
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2091:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  760): Force removing ActivityRecord{1f5b4275 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  760): Spurious death for ProcessRecord{1d64b0a3 2091:com.example.hello/u0a277}, curProc for 2091: null
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=0: pkg removed
,W/ActivityThread( 2780): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  760): Killing 2350:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2865 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  760): Process android.process.acore (pid 1365) has died
,W/ActivityManager(  760): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,I/ActivityManager(  760): Killing 1066:com.google.android.inputmethod.latin/u0a56 (adj 2): depends on provider com.android.providers.userdictionary/.UserDictionaryProvider in dying proc android.process.acore
,W/ActivityManager(  760): Scheduling restart of crashed service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME in 10963ms


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
W/ActivityManager( 2407): mDVFSHelper.acquire()
D/ActivityThread( 6449): Added TimaKesytore provider
,W/ActivityManager( 2407): mDVFSHelper.release()
,W/jxcore-log( 6449): Initializing JXcore engine
,W/jxcore-log( 6449): JXcore engine is ready
,W/jxcore-log( 6449): Starting JXcore engine
,W/jxcore-log( 6449): Platform android
W/jxcore-log( 6449): 
,W/jxcore-log( 6449): Process ARCH arm
W/jxcore-log( 6449): 
,I/jxcore-log( 6449): JXcore Cordova bridge is ready!
I/jxcore-log( 6449): 
,W/jxcore-log( 6449): JXcore engine is started
,E/jxcore-log( 6449): >> samsung-SM-G800F
E/jxcore-log( 6449): 
,I/jxcore-log( 6449): Total memory 1319530496
I/jxcore-log( 6449): 
I/jxcore-log( 6449): Free memory 45776896
I/jxcore-log( 6449): 
I/jxcore-log( 6449): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6449): 
,I/jxcore-log( 6449): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6449): 
,I/jxcore-log( 6449): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6449): 
,I/jxcore-log( 6449): Size 720 1280
I/jxcore-log( 6449): 
,I/jxcore-log( 6449): Screen Brightness 134
I/jxcore-log( 6449): 
,E/jxcore-log( 6449): Dummy Error Log.
E/jxcore-log( 6449): 
,I/jxcore-log( 6449): getBuffer is called!!!!
I/jxcore-log( 6449): 
,I/jxcore-log( 6449): ****TEST TOOK:  5102  ms ****
I/jxcore-log( 6449): 
I/jxcore-log( 6449): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6449): 
,I/ActivityManager( 2407): Killing 6449:com.example.hello/u0a424 (adj 0): stop com.example.hello
,D/ActivityThread( 6537): Added TimaKesytore provider
,I/ActivityManager( 2407): Killing 5653:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/ActivityThread( 6550): Added TimaKesytore provider
,D/ActivityThread( 6568): Added TimaKesytore provider
,I/ActivityManager( 2407): Killing 5725:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/ActivityManager( 2407): Process com.samsung.android.magazine.service (pid 6230) (adj 5) has died.
,D/ActivityThread( 6585): Added TimaKesytore provider
,I/ActivityManager( 2407): Process com.android.keychain (pid 6585) (adj 5) has died.
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 2846) (adj 0) has died.
,I/ActivityManager( 2407): Process com.google.android.gms (pid 3149) (adj 5) has died.
,D/ActivityThread( 6612): Added TimaKesytore provider
,I/ActivityManager( 2407): Killing 5743:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/ActivityManager( 2407): Process com.android.documentsui (pid 6612) (adj 9) has died.
,D/ActivityThread( 6627): Added TimaKesytore provider
,D/ActivityThread( 6631): Added TimaKesytore provider
,D/ActivityThread( 6655): Added TimaKesytore provider
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 6655) (adj 0) has died.
,W/ActivityManager( 2407): Service crashed 2 times, stopping: ServiceRecord{43231820 u0 com.google.android.gms/.gcm.GcmService}
,W/ActivityManager( 2407): Service crashed 2 times, stopping: ServiceRecord{43017928 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
,D/ActivityThread( 6670): Added TimaKesytore provider
,W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 6670:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 6631): Failed to find provider info for com.google.android.gsf.gservices
,D/ActivityThread( 6686): Added TimaKesytore provider
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 6686) (adj 0) has died.
,D/ActivityThread( 6701): Added TimaKesytore provider
,W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 6701:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 6631): Failed to find provider info for com.google.android.gsf.gservices
,D/ActivityThread( 6716): Added TimaKesytore provider
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 6716) (adj 0) has died.
,D/ActivityThread( 6731): Added TimaKesytore provider
,W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 6731:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 6631): Failed to find provider info for com.google.android.gsf.gservices
,D/ActivityThread( 6750): Added TimaKesytore provider
,D/ActivityThread( 6754): Added TimaKesytore provider
,I/ActivityManager( 2407): Killing 5778:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 6754) (adj 0) has died.
,D/ActivityThread( 6777): Added TimaKesytore provider
,W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 6777:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 6631): Failed to find provider info for com.google.android.gsf.gservices


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  988): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3436
I/ActivityManager(  988): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3452 uid=10355 gids={50355, 3003, 3001, 3002}
,I/ActivityManager(  988): Displayed com.example.hello/.MainActivity: +340ms (total +369ms)
,W/jxcore-log( 3452): Initializing JXcore engine
,W/jxcore-log( 3452): JXcore engine is ready
,W/jxcore-log( 3452): Starting JXcore engine
,W/jxcore-log( 3452): Platform android
W/jxcore-log( 3452): 
,W/jxcore-log( 3452): Process ARCH arm
W/jxcore-log( 3452): 
,I/jxcore-log( 3452): JXcore Cordova bridge is ready!
I/jxcore-log( 3452): 
,W/jxcore-log( 3452): JXcore engine is started
,E/jxcore-log( 3452): >> motorola-XT1039
E/jxcore-log( 3452): 
,I/jxcore-log( 3452): Total memory 893136896
I/jxcore-log( 3452): 
I/jxcore-log( 3452): Free memory 40755200
I/jxcore-log( 3452): 
I/jxcore-log( 3452): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3452): 
,I/jxcore-log( 3452): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3452): 
,I/jxcore-log( 3452): userPath [ 'www' ]
I/jxcore-log( 3452): 
,I/jxcore-log( 3452): Size 720 1184
I/jxcore-log( 3452): 
,I/jxcore-log( 3452): Screen Brightness 10
I/jxcore-log( 3452): 
,E/jxcore-log( 3452): Dummy Error Log.
E/jxcore-log( 3452): 
,I/jxcore-log( 3452): getBuffer is called!!!!
I/jxcore-log( 3452): 
,I/jxcore-log( 3452): ****TEST TOOK:  5045  ms ****
I/jxcore-log( 3452): 
I/jxcore-log( 3452): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3452): 
,I/ActivityManager(  988): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  988): Killing 3452:com.example.hello/u0a355 (adj 0): stop com.example.hello
,I/ActivityManager(  988):   Force finishing activity ActivityRecord{4278ada0 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  988): Force stopping com.example.hello appid=10355 user=0: pkg removed
I/ActivityManager(  988):   Force finishing activity ActivityRecord{4278ada0 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager(  988): Duplicate finish request for ActivityRecord{4278ada0 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager(  988): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3562 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager(  988): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3581 uid=10058 gids={50058}
,I/ActivityManager(  988): Killing 3331:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager(  988): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3600 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager(  988): Killing 3355:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager(  988): Killing 3267:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager(  988): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3616 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager(  988): Killing 3089:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1031): Killing 3662:com.android.keychain/1000 (adj 15): empty #17
I/ActivityManager( 1031): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=4239 uid=10042 gids={50042, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1031): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=4258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1031): Killing 3701:com.google.android.onetimeinitializer/u0a7 (adj 15): empty #17
I/ActivityManager( 1031): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4281 uid=10043 gids={50043, 9997, 1028, 3003} abi=armeabi-v7a
I/ActivityManager( 1031): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4302 uid=10050 gids={50050, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 3743:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/ActivityManager( 1031): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4337 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 3804:com.lge.clock/u0a10 (adj 15): empty #17
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{1671e79b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{1671e79b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1031): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4383 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4402 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4449 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 3854:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #17
,I/ActivityManager( 1031): Displayed com.example.hello/.MainActivity: +710ms
,I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4483 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 3885:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4501 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 4383): Initializing JXcore engine
W/jxcore-log( 4383): JXcore engine is ready
I/ActivityManager( 1031): Killing 3923:com.android.browser/u0a12 (adj 15): empty #17
W/jxcore-log( 4383): Starting JXcore engine
,I/ActivityManager( 1031): Start proc com.lge.clock for content provider com.lge.clock/.alarmclock.ALProvider: pid=4519 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/jxcore-log( 4383): Platform android
W/jxcore-log( 4383): 
,W/jxcore-log( 4383): Process ARCH arm
W/jxcore-log( 4383): 
,I/jxcore-log( 4383): JXcore Cordova bridge is ready!
I/jxcore-log( 4383): 
W/jxcore-log( 4383): JXcore engine is started
,I/ActivityManager( 1031): Killing 3966:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #17
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/ActivityManager( 1031): Killing 2972:com.android.contacts/u0a19 (adj 15): empty #17
E/jxcore-log( 4383): >> LGE-LG-D855
E/jxcore-log( 4383): 
,I/jxcore-log( 4383): Total memory 2995761152
I/jxcore-log( 4383): 
I/jxcore-log( 4383): Free memory 841261056
I/jxcore-log( 4383): 
I/jxcore-log( 4383): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4383): 
I/jxcore-log( 4383): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4383): 
I/jxcore-log( 4383): userPath [ 'www' ]
I/jxcore-log( 4383): 
I/jxcore-log( 4383): Size 1440 2392
I/jxcore-log( 4383): 
I/jxcore-log( 4383): Screen Brightness 50
I/jxcore-log( 4383): 
E/jxcore-log( 4383): Dummy Error Log.
E/jxcore-log( 4383): 
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 4501): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1031): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4560 uid=10065 gids={50065, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4501): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2479b81c that was originally bound here
E/ActivityThread( 4501): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2479b81c that was originally bound here
E/ActivityThread( 4501): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4501): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4501): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4501): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4501): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4501): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4501): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4501): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4501): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4501): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4501): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4501): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4501): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4501): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1031): Unbind failed: could not find connection for android.os.BinderProxy@1043a7e9
,I/ActivityManager( 1031): Killing 2517:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/jxcore-log( 4383): getBuffer is called!!!!
I/jxcore-log( 4383): 
,I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4584 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.lgodm.LGODMReceiver: pid=4621 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1031): Killing 4047:com.lge.email/u0a23 (adj 15): empty #17
,I/ActivityManager( 1031): Waited long enough for: ServiceRecord{251b097d u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager( 1031): Killing 4011:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4640 uid=10073 gids={50073, 9997} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4662 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 3594:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,I/ActivityManager( 1031): Killing 4159:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4679 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1031): Killing 4120:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4697 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1031): Killing 4191:com.android.settings/1000 (adj 15): empty #17
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4715 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 4239:com.lge.voicerecorder/u0a42 (adj 15): empty #17
,I/ActivityManager( 1031): Process com.lge.defaultaccount (pid 4640) has died
,I/ActivityManager( 1031): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4733 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4753 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 4281:com.android.managedprovisioning/u0a43 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=4771 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 4337:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/ActivityManager( 1031): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=4808 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 4074:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/ActivityManager( 1031): Killing 4402:com.lge.cloudhub/u0a58 (adj 15): empty #17
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/ActivityManager( 1031): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4893 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1031): Start proc com.qualcomm.wfd.service:wfd_service for service com.qualcomm.wfd.service/.WfdService: pid=4910 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4949 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1031): Start proc com.nuance.voicemate for broadcast com.nuance.voicemate/com.nuance.androidcore.manifest.receivers.UploadServiceBootStart: pid=4969 uid=10117 gids={50117, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi
,I/jxcore-log( 4383): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 4383): 
I/jxcore-log( 4383): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4383): 
,I/ActivityManager( 1031): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=5008 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 4449:com.google.android.configupdater/u0a59 (adj 15): empty #17
,I/ActivityManager( 1031): Killing 4483:com.lge.drmservice/u0a62 (adj 15): empty #17
,I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 4383:com.example.hello/u0a318 (adj 0): stop com.example.hello
,W/ActivityManager( 1031): Force removing ActivityRecord{3ff30738 u0 com.example.hello/.MainActivity t4}: app died, no saved state
,W/ActivityManager( 1031): Spurious death for ProcessRecord{17dbcd3e 4383:com.example.hello/u0a318}, curProc for 4383: null
,I/ActivityManager( 1031): Force stopping com.example.hello appid=10318 user=0: pkg removed
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,W/ActivityManager( 1031): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/ActivityManager( 1031): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5067 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 4519:com.lge.clock/u0a10 (adj 15): empty #17
,W/ActivityThread( 5067): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1031): Killing 4501:com.google.android.gm/u0a64 (adj 15): empty #17


```

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4444 uid=10109 gids={50109, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager(  881): Display changed displayId=0
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{1d16a4ac u0 com.example.hello/.MainActivity t181}
,I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +829ms (total +931ms)
,W/jxcore-log( 4444): Initializing JXcore engine
W/jxcore-log( 4444): JXcore engine is ready
,W/jxcore-log( 4444): Starting JXcore engine
,W/jxcore-log( 4444): Platform android
W/jxcore-log( 4444): 
W/jxcore-log( 4444): Process ARCH arm
W/jxcore-log( 4444): 
,I/jxcore-log( 4444): JXcore Cordova bridge is ready!
I/jxcore-log( 4444): 
W/jxcore-log( 4444): JXcore engine is started
,E/jxcore-log( 4444): >> motorola-XT1072
E/jxcore-log( 4444): 
,I/jxcore-log( 4444): Total memory 916258816
I/jxcore-log( 4444): 
,I/jxcore-log( 4444): Free memory 34594816
I/jxcore-log( 4444): 
I/jxcore-log( 4444): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4444): 
,I/jxcore-log( 4444): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4444): 
I/jxcore-log( 4444): userPath [ 'www' ]
I/jxcore-log( 4444): 
,I/jxcore-log( 4444): Size 720 1184
I/jxcore-log( 4444): 
,I/jxcore-log( 4444): Screen Brightness 82
I/jxcore-log( 4444): 
,E/jxcore-log( 4444): Dummy Error Log.
E/jxcore-log( 4444): 
,I/jxcore-log( 4444): getBuffer is called!!!!
I/jxcore-log( 4444): 
,I/jxcore-log( 4444): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 4444): 
I/jxcore-log( 4444): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4444): 
,I/ActivityManager(  881): Force stopping com.example.hello appid=10109 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 4444:com.example.hello/u0a109 (adj 0): stop com.example.hello
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{1d16a4ac u0 com.example.hello/.MainActivity t181}
,W/ActivityManager(  881): Spurious death for ProcessRecord{c59e90c 4444:com.example.hello/u0a109}, curProc for 4444: null
,I/ActivityManager(  881): Force stopping com.example.hello appid=10109 user=0: pkg removed
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4542 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4568 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 4279:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4589 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a


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
I/ActivityManager( 3527): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11918 uid=10383 gids={50383, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread(11918): Added TimaKeyStore provider
V/ActivityThread( 4001): updateVisibility : ActivityRecord{8bfdcc0 token=android.os.BinderProxy@1b841ab {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/ActivityThread( 4001): updateVisibility : ActivityRecord{8bfdcc0 token=android.os.BinderProxy@1b841ab {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityManager( 3527): post active user change for 0
I/ActivityManager( 3527): Displayed com.example.hello/.MainActivity: +348ms (total +5s603ms)
W/jxcore-log(11918): Initializing JXcore engine
W/jxcore-log(11918): JXcore engine is ready
W/jxcore-log(11918): Starting JXcore engine
W/jxcore-log(11918): Platform android
W/jxcore-log(11918): 
W/jxcore-log(11918): Process ARCH arm
W/jxcore-log(11918): 
I/jxcore-log(11918): JXcore Cordova bridge is ready!
I/jxcore-log(11918): 
W/jxcore-log(11918): JXcore engine is started
E/jxcore-log(11918): >> samsung-SM-N910C
E/jxcore-log(11918): 
I/jxcore-log(11918): Total memory 2970812416
I/jxcore-log(11918): 
I/jxcore-log(11918): Free memory 114130944
I/jxcore-log(11918): 
I/jxcore-log(11918): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11918): 
I/jxcore-log(11918): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11918): 
I/jxcore-log(11918): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11918): 
I/jxcore-log(11918): Size 1440 2560
I/jxcore-log(11918): 
I/jxcore-log(11918): Screen Brightness 134
I/jxcore-log(11918): 
E/jxcore-log(11918): Dummy Error Log.
E/jxcore-log(11918): 
W/ActivityManager( 3527): mDVFSHelper.release()
I/jxcore-log(11918): getBuffer is called!!!!
I/jxcore-log(11918): 
,I/jxcore-log(11918): ****TEST TOOK:  5076  ms ****
I/jxcore-log(11918): 
,I/jxcore-log(11918): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11918): 
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12007 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12007): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 11126:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12048 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Process com.android.bluetooth (pid 5692)(adj 0) has died(86,1258)
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10383 user=-1: uninstall pkg
,I/ActivityManager( 3527): Killing 11918:com.example.hello/u0a383 (adj 0): stop com.example.hello
,W/ActivityManager( 3527): Force removing ActivityRecord{708a128 u0 com.example.hello/.MainActivity t443}: app died, no saved state
,W/ActivityManager( 3527): mDVFSHelper.acquire()
,D/ActivityThread(12048): Added TimaKeyStore provider
,I/ActivityManager( 3527): Force stopping com.example.hello appid=10383 user=0: pkg removed
,D/ActivityManager( 3527): handle home activity for 0
D/ActivityManager( 3527): post active user change for 0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11240:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ActivityThread(12068): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 11222:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12091 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/ActivityThread(12091): Added TimaKeyStore provider
,I/ActivityManager( 3527): Killing 11313:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12107 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12107): Added TimaKeyStore provider
,W/ActivityManager( 3527): mDVFSHelper.release()
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12122 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11332:com.samsung.android.app.watchmanagerstub/u0a121 (adj 15): bgCount ##31
,D/ActivityThread(12122): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12138 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12138): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12153 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12153): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12170 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ActivityThread(12170): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12187 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11298:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
,D/ActivityThread(12187): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=12205 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11350:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12205): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=12220 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11366:com.samsung.helphub/1000 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12220): Added TimaKeyStore provider
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12235 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11419:com.samsung.android.snote:provider/u0a160 (adj 15): bgCount ##31
,D/ActivityThread(12235): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=12260 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11532:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/ActivityThread(12260): Added TimaKeyStore provider
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12277 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11547:com.android.calendar/u0a164 (adj 15): bgCount ##31
,D/ActivityThread(12277): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3527): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=12298 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 10406:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
,I/ActivityManager( 3527): Killing 11576:com.google.android.gms:car/u0a14 (adj 15): bgCount ##32
,D/ActivityThread(12298): Added TimaKeyStore provider
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  899): Killing 5887:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,I/ActivityManager(  899): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  899): mDVFSHelper.acquire()
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  899): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6869 uid=10191 gids={50191, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6869): Added TimaKeyStore provider
V/ActivityManager(  899): Display changed displayId=0
,D/ActivityManager(  899): post active user change for 0
I/ActivityManager(  899): Displayed com.example.hello/.MainActivity: +516ms
W/jxcore-log( 6869): Initializing JXcore engine
W/jxcore-log( 6869): JXcore engine is ready
W/jxcore-log( 6869): Starting JXcore engine
W/ActivityManager(  899): mDVFSHelper.release()
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  899): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 6925): Added TimaKeyStore provider
,I/ActivityManager(  899): Killing 5942:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,W/jxcore-log( 6869): Platform android
W/jxcore-log( 6869): 
W/jxcore-log( 6869): Process ARCH arm
W/jxcore-log( 6869): 
,I/jxcore-log( 6869): JXcore Cordova bridge is ready!
I/jxcore-log( 6869): 
,W/jxcore-log( 6869): JXcore engine is started
,E/jxcore-log( 6869): >> samsung-SM-G900F
E/jxcore-log( 6869): 
,I/jxcore-log( 6869): Total memory 1787449344
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Free memory 53411840
I/jxcore-log( 6869): 
I/jxcore-log( 6869): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Size 1080 1920
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Screen Brightness 134
I/jxcore-log( 6869): 
,E/jxcore-log( 6869): Dummy Error Log.
E/jxcore-log( 6869): 
,I/jxcore-log( 6869): getBuffer is called!!!!
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6869): 
,I/ActivityManager(  899): Force stopping com.example.hello appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  899): Killing 6869:com.example.hello/u0a191 (adj 0): stop com.example.hello
,W/ActivityManager(  899): Force removing ActivityRecord{21747263 u0 com.example.hello/.MainActivity t361}: app died, no saved state
,W/ActivityManager(  899): mDVFSHelper.acquire()
,I/ActivityManager(  899): Force stopping com.example.hello appid=10191 user=0: pkg removed
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6979 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  899): handle home activity for 0
D/ActivityManager(  899): post active user change for 0
,D/ActivityThread( 6979): Added TimaKeyStore provider
,W/ActivityManager(  899): mDVFSHelper.release()
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7005 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 5910:com.sec.android.automotive.drivelink/u0a98 (adj 15): bgCount ##41
,D/ActivityThread( 7005): Added TimaKeyStore provider
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7021 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 5977:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/ActivityThread( 7021): Added TimaKeyStore provider
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 5991:com.sec.android.provider.logsprovider/u0a19 (adj 15): bgCount ##41
,D/ActivityThread( 7037): Added TimaKeyStore provider
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7053 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 5997:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ActivityThread( 7053): Added TimaKeyStore provider
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7071 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 6026:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): bgCount ##41
,D/ActivityThread( 7071): Added TimaKeyStore provider
,I/ActivityManager(  899): Process com.sec.spp.push:RemoteNotiProcess (pid 7071)(adj 0) has died(121,620)
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7087 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/ActivityThread( 7087): Added TimaKeyStore provider
,E/ActivityThread( 7087): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  899): Process com.samsung.android.sdk.samsunglink (pid 7087)(adj 0) has died(120,621)
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7102 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7102): Added TimaKeyStore provider
,E/ActivityThread( 7102): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  899): Process com.osp.app.signin (pid 7102)(adj 0) has died(120,621)
,I/ActivityManager(  899): Process android.process.acore (pid 1785)(adj 0) has died(129,621)
,W/ActivityManager(  899): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7120 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
,D/ActivityThread( 7120): Added TimaKeyStore provider
,E/ActivityThread( 7120): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  899): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  899): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7138 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/ActivityManager(  899): Killing 6070:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ActivityThread( 7138): Added TimaKeyStore provider
,E/ActivityThread( 7138): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  899): Process com.google.android.googlequicksearchbox:search (pid 1577)(adj 1) has died(143,622)
,W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10707ms
W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 10707ms
,W/ActivityManager(  899): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 20707ms
,I/ActivityManager(  899): Killing 6042:com.samsung.android.magazine.service/u0a117 (adj 15): bgCount ##41
,I/ActivityManager(  899): Process com.samsung.android.intelligenceservice (pid 7138)(adj 0) has died(148,622)


```

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
Device test finished on ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
motorola-Nexus 6: 
--------- beginning of system
I/ActivityManager(  820): Killing 3064:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,--------- beginning of main
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  820): Start proc 3486:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
I/ActivityManager(  820): Killing 3097:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/ActivityManager(  820): Displayed com.example.hello/.MainActivity: +515ms
,I/ActivityManager(  820): Killing 3133:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/jxcore-log( 3486): Initializing JXcore engine
W/jxcore-log( 3486): JXcore engine is ready
,W/jxcore-log( 3486): Starting JXcore engine
,W/jxcore-log( 3486): Platform android
W/jxcore-log( 3486): 
W/jxcore-log( 3486): Process ARCH arm
W/jxcore-log( 3486): 
,I/jxcore-log( 3486): JXcore Cordova bridge is ready!
I/jxcore-log( 3486): 
,W/jxcore-log( 3486): JXcore engine is started
,E/jxcore-log( 3486): >> motorola-Nexus 6
E/jxcore-log( 3486): 
,I/jxcore-log( 3486): Total memory 3113791488
I/jxcore-log( 3486): 
I/jxcore-log( 3486): Free memory 1024299008
I/jxcore-log( 3486): 
,I/jxcore-log( 3486): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3486): 
I/jxcore-log( 3486): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3486): 
I/jxcore-log( 3486): userPath [ 'www' ]
I/jxcore-log( 3486): 
,I/jxcore-log( 3486): Size 1440 2392
I/jxcore-log( 3486): 
,I/jxcore-log( 3486): Screen Brightness 82
I/jxcore-log( 3486): 
E/jxcore-log( 3486): Dummy Error Log.
E/jxcore-log( 3486): 
,I/jxcore-log( 3486): getBuffer is called!!!!
I/jxcore-log( 3486): 
,I/jxcore-log( 3486): ****TEST TOOK:  5084  ms ****
I/jxcore-log( 3486): 
I/jxcore-log( 3486): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3486): 
,I/ActivityManager(  820): Start proc 3561:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/ActivityManager(  820): Start proc 3601:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  820): Killing 2933:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,I/ActivityManager(  820): Killing 3486:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/ActivityManager(  820): Force removing ActivityRecord{fad11e2 u0 com.example.hello/.MainActivity t20}: app died, no saved state
,I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  820): Spurious death for ProcessRecord{175d824e 3486:com.example.hello/u0a272}, curProc for 3486: null
,I/ActivityManager(  820): Start proc 3635:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,--------- beginning of crash
,I/ActivityManager(  820): Start proc 3704:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  820): Killing 2281:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3032:com.google.android.gm/u0a78 (adj 15): empty #18
,I/ActivityManager(  820): Start proc 3728:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  820): Killing 3328:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3745:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  820): Killing 3350:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  820): Process com.google.android.keep (pid 3745) has died
,W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.keep/.notification.AlertService in 1000ms
,I/ActivityManager(  820): Start proc 3775:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  820): Process android.process.acore (pid 1422) has died
W/ActivityManager(  820): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 10704ms
,I/ActivityManager(  820): Start proc 3795:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ActivityManager(  820): Start proc 3818:com.google.android.keep/u0a79 for service com.google.android.keep/.notification.AlertService
,I/ActivityManager(  820): Process com.google.android.keep (pid 3818) has died
W/ActivityManager(  820): Service crashed 2 times, stopping: ServiceRecord{342ec28e u0 com.google.android.keep/.notification.AlertService}


samsung-SM-N9005: 
--------- beginning of system,
I/ActivityManager(  745): Waited long enough for: ServiceRecord{659830a u0 com.google.android.music/.wear.WearMetadataSyncService}
--------- beginning of main
I/ActivityManager(  745): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  745): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  745): mDVFSHelper.acquire()
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  745): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5994 uid=10217 gids={50217, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5994): Added TimaKeyStore provider
V/ActivityManager(  745): Display changed displayId=0
V/ActivityThread( 1451): updateVisibility : ActivityRecord{39b207b6 token=android.os.BinderProxy@398f3977 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager(  745): Activity pause timeout for ActivityRecord{4a15050 u0 com.example.hello/.MainActivity t2}
D/ActivityManager(  745): post active user change for 0
V/ActivityThread( 5994): updateVisibility : ActivityRecord{76ec52f token=android.os.BinderProxy@25af1909 {com.example.hello/com.example.hello.MainActivity}} show : true
W/ActivityManager(  745): mDVFSHelper.release()
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  745): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6073 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityThread( 6073): Added TimaKeyStore provider
W/jxcore-log( 5994): Initializing JXcore engine
W/jxcore-log( 5994): JXcore engine is ready
W/jxcore-log( 5994): Starting JXcore engine
W/ActivityThread( 6073): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 5994): Platform android
W/jxcore-log( 5994): 
W/jxcore-log( 5994): Process ARCH arm
W/jxcore-log( 5994): 
,I/jxcore-log( 5994): JXcore Cordova bridge is ready!
I/jxcore-log( 5994): 
,W/jxcore-log( 5994): JXcore engine is started
,D/ActivityThread( 6104): Added TimaKeyStore provider
,E/jxcore-log( 5994): >> samsung-SM-N9005
E/jxcore-log( 5994): 
,I/jxcore-log( 5994): Total memory 2971471872
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): Free memory 429756416
I/jxcore-log( 5994): 
I/jxcore-log( 5994): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): Size 1080 1920
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): Screen Brightness 162
I/jxcore-log( 5994): 
,E/jxcore-log( 5994): Dummy Error Log.
E/jxcore-log( 5994): 
,I/ActivityManager(  745): Killing 5198:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,I/ActivityManager(  745): Killing 5177:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##42
,I/jxcore-log( 5994): getBuffer is called!!!!
I/jxcore-log( 5994): 
,I/ActivityManager(  745): Waited long enough for: ServiceRecord{26489bc1 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,I/jxcore-log( 5994): ****TEST TOOK:  5084  ms ****
I/jxcore-log( 5994): 
,I/jxcore-log( 5994): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5994): 
,I/ActivityManager(  745): Force stopping com.example.hello appid=10217 user=-1: uninstall pkg
I/ActivityManager(  745): Killing 5994:com.example.hello/u0a217 (adj 0): stop com.example.hello
,I/ActivityManager(  745):   Force finishing activity ActivityRecord{4a15050 u0 com.example.hello/.MainActivity t2}
,W/ActivityManager(  745): Spurious death for ProcessRecord{14d3eb17 5994:com.example.hello/u0a217}, curProc for 5994: null
I/ActivityManager(  745): Force stopping com.example.hello appid=10217 user=0: pkg removed
,I/ActivityManager(  745):   Force finishing activity ActivityRecord{4a15050 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager(  745): Duplicate finish request for ActivityRecord{4a15050 u0 com.example.hello/.MainActivity t2 f}
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6161 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6161): Added TimaKeyStore provider
,V/ActivityThread( 1451): updateVisibility : ActivityRecord{39b207b6 token=android.os.BinderProxy@398f3977 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6187 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5238:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6187): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6204 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5046:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,D/ActivityThread( 6204): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6222 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 4346:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/ActivityThread( 6222): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5081:com.google.android.talk/u0a131 (adj 13): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6246 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6253 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6253): Added TimaKeyStore provider
,D/ActivityThread( 6246): Added TimaKeyStore provider
,E/ActivityThread( 6246): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityThread( 6253): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6280 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6280): Added TimaKeyStore provider
,I/ActivityManager(  745): Process com.google.android.googlequicksearchbox:search (pid 1499)(adj 1) has died(482,1374)
,W/ActivityManager(  745): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  745): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 11000ms
,W/ActivityManager(  745): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20999ms
,E/ActivityThread( 5827): Failed to find provider info for com.samsung.android.provider.filterprovider
,E/ActivityThread( 5827): Failed to find provider info for com.samsung.android.provider.filterprovider


HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager(  908): Killing 3086:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3086
I/ActivityManager(  908): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3909 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  908): Killing 3393:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3393
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3928 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  908): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3946 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  908): Killing 3446:com.htc.lmw/u0a61 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3446
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3966 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 3946): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4042 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  908): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4059 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
I/ActivityManager(  908): Killing 3469:com.android.managedprovisioning/u0a66 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3469
I/ActivityManager(  908): Killing 2095:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2095
I/ActivityManager(  908): Killing 1944:com.google.android.gms/u0a25 (adj 15): empty #17
I/ActivityManager(  908): Recipient 1944
,I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +907ms,
,I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 3610:com.htc.cs.pns/u0a74 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3610
,I/ActivityManager(  908): Killing 3638:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3638
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4118 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 3928): Initializing JXcore engine
W/jxcore-log( 3928): JXcore engine is ready
,W/jxcore-log( 3928): Starting JXcore engine
,W/jxcore-log( 3928): Platform android
W/jxcore-log( 3928): 
W/jxcore-log( 3928): Process ARCH arm
W/jxcore-log( 3928): 
,I/jxcore-log( 3928): JXcore Cordova bridge is ready!
I/jxcore-log( 3928): 
,W/jxcore-log( 3928): JXcore engine is started
,E/jxcore-log( 3928): >> HTC-HTC One_M8
E/jxcore-log( 3928): 
,I/jxcore-log( 3928): Total memory 1912020992
I/jxcore-log( 3928): 
I/jxcore-log( 3928): Free memory 161337344
I/jxcore-log( 3928): 
I/jxcore-log( 3928): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3928): 
I/jxcore-log( 3928): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): userPath [ 'www' ],
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): Size 1080 1776
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): Screen Brightness 142,
I/jxcore-log( 3928): 
E/jxcore-log( 3928): Dummy Error Log.
E/jxcore-log( 3928): 
,I/ActivityManager(  908): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4154 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  908): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4174 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 3661:com.htc.showme/u0a85 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 3661,
,W/ActivityThread( 4154): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  908): Killing 3569:com.htc.sense.mms/u0a67 (adj 15): empty #17
W/ActivityThread( 4174): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  908): Recipient 3569
,I/ActivityManager(  908): Killing 3688:com.htc.feedback/u0a87 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3688
,I/ActivityManager(  908): Killing 3722:com.htc.updater/u0a88 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3722
,I/jxcore-log( 3928): getBuffer is called!!!!
I/jxcore-log( 3928): 
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4269 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  908): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4297 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4326 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 3764:com.htc.android.worldclock/u0a96 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3764,
,I/ActivityManager(  908): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4411 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  908): Killing 3744:com.htc.videocenter/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3744,
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4440 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4478 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 3782:com.htc.tiber2/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3782,
,I/ActivityManager(  908): Killing 3809:com.google.android.configupdater/u0a104 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3809
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4536 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a,
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4572 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
,W/ActivityManager(  908): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4478): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@5f52027 that was originally bound here
E/ActivityThread( 4478): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@5f52027 that was originally bound here
E/ActivityThread( 4478): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4478): ,	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4478): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4478): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4478): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4478): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4478): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4478): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4478): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4478): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4478): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4478): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4478): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  908): Killing 3909:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3909
,W/ActivityManager(  908): Unbind failed: could not find connection for android.os.BinderProxy@1964413e
,I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4623 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4640 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  908): Killing 3946:com.htc.htccupd/u0a13 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 3946,
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4662 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 4042:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4042
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4680 uid=10079 gids={50079, 9997} abi=armeabi-v7a,
I/ActivityManager(  908): Killing 4001:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4001
,I/ActivityManager(  908): Killing 4059:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4059,
,I/ActivityManager(  908): Killing 4093:com.android.smith/1000 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 4093
,I/ActivityManager(  908): Killing 4025:com.android.settings/1000 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 4025,
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4706 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a,
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=4734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 4154:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 4154
,W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/ActivityManager(  908): Killing 4118:com.android.vending/u0a75 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4118
,I/ActivityManager(  908): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4758 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a,
,I/ActivityManager(  908): Killing 4326:com.google.android.youtube/u0a186 (adj 15): empty #17,
,I/ActivityManager(  908): Recipient 4326
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4787 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/jxcore-log( 3928): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 3928): 
I/jxcore-log( 3928): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3928): 
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4807 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  908): Killing 4411:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4411
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{2fda5bbd u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4827 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 4440:com.google.android.partnersetup/u0a28 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4440
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4864 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  908): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
,I/ActivityManager(  908): Killing 3928:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  908): Recipient 3928,
,W/ActivityManager(  908): Force removing ActivityRecord{3e3dda6 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/ActivityManager(  908): Spurious death for ProcessRecord{206f32b0 3928:com.example.hello/u0a380}, curProc for 3928: null
,I/ActivityManager(  908): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4885 uid=10029 gids={50029, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 4478:com.google.android.gm/u0a115 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4478
,I/ActivityManager(  908): Killing 3868:com.htc.backup/u0a118 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3868,
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4907 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityThread( 4907): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  908): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  908): Killing 4536:com.htc.sense.news/u0a77 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4536
,I/ActivityManager(  908): Killing 4572:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4572
,E/ActivityManager(  908): App crashed! Process: com.htc.launcher
,W/ActivityManager(  908):   Force finishing activity com.htc.launcher/.Launcher
,W/ActivityManager(  908): Can't addPackageDependency on system process,
,I/ActivityManager(  908): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0,


```

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on FA55PYS00566 
Device test finished on 7970f88c 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1016): mDVFSHelper.acquire()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5378 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5378): Added TimaKeyStore provider
V/ActivityManager( 1016): Display changed displayId=0
V/ActivityThread( 1474): updateVisibility : ActivityRecord{28d08149 token=android.os.BinderProxy@160e01cf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{b4b3c48 u0 com.example.hello/.MainActivity t22}
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5378): updateVisibility : ActivityRecord{1cd30352 token=android.os.BinderProxy@2a9623b4 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1016): Displayed Component not be shown by security: +615ms (total +689ms)
,W/ActivityManager( 1016): mDVFSHelper.release()
,W/jxcore-log( 5378): Initializing JXcore engine
W/jxcore-log( 5378): JXcore engine is ready
,W/jxcore-log( 5378): Starting JXcore engine
,W/jxcore-log( 5378): Platform android
W/jxcore-log( 5378): 
W/jxcore-log( 5378): Process ARCH arm
W/jxcore-log( 5378): 
,I/jxcore-log( 5378): JXcore Cordova bridge is ready!
I/jxcore-log( 5378): 
,W/jxcore-log( 5378): JXcore engine is started
,E/jxcore-log( 5378): >> samsung-SM-A300FU
E/jxcore-log( 5378): 
,I/jxcore-log( 5378): Total memory 1451114496
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): Free memory 21815296
I/jxcore-log( 5378): 
I/jxcore-log( 5378): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5378): 
I/jxcore-log( 5378): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): userPath [ 'www' ]
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): Size 540 960
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): Screen Brightness 160
I/jxcore-log( 5378): 
,E/jxcore-log( 5378): Dummy Error Log.
E/jxcore-log( 5378): 
,I/jxcore-log( 5378): getBuffer is called!!!!
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 5378): 
,I/jxcore-log( 5378): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5378): 
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 5378:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{b4b3c48 u0 com.example.hello/.MainActivity t22},
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5440 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,D/ActivityThread( 5440): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1016): Killing 4864:com.wssyncmldm/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5461 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,D/ActivityThread( 5461): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 4885:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/ActivityThread( 5479): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5497 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5509 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 5497): Added TimaKeyStore provider
,D/ActivityThread( 5509): Added TimaKeyStore provider,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5528 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a


HTC-HTC One M8s: 
--------- beginning of system
,I/ActivityManager(  924): Recipient 3940
--------- beginning of main
I/ActivityManager(  924): Killing 3063:com.htc.cs.dm/u0a99 (adj 15): empty #17
I/ActivityManager(  924): Recipient 3063
I/ActivityManager(  924): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4599 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityManager(  924): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4624 uid=10035 gids={50035, 9997} abi=arm64-v8a
W/ActivityThread( 4599): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  924): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4663 uid=10076 gids={50076, 9997} abi=arm64-v8a
I/ActivityManager(  924): Killing 3986:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  924): Recipient 3986
I/ActivityManager(  924): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4594 on display 0
I/ActivityManager(  924): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4688 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/ActivityManager(  924): Killing 4013:com.htc.htccupd/u0a13 (adj 15): empty #17
I/ActivityManager(  924): Recipient 4013
I/ActivityManager(  924): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4709 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityThread( 1528): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1528): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1528): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1528): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1528): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1528): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1528): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1528): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1528): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1528): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1528): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1528): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  924): Activity reported stop, but no longer stopping: ActivityRecord{197ae7dd u0 com.htc.launcher/.Launcher t9}
I/ActivityManager(  924): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4736 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  924): Killing 4082:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/ActivityManager(  924): Recipient 4082
I/ActivityManager(  924): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4778 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  924): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4798 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  924): Killing 4103:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  924): Recipient 4103
I/ActivityManager(  924): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4835 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager(  924): Killing 4133:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  924): Recipient 4133
I/ActivityManager(  924): Killing 4156:com.android.smith/1000 (adj 15): empty #17
I/ActivityManager(  924): Recipient 4156
I/ActivityManager(  924): Displayed com.example.hello/.MainActivity: +1s35ms
I/ActivityManager(  924): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  924): Killing 4214:com.google.android.gms:car/u0a24 (adj 15): empty #17
W/jxcore-log( 4709): Initializing JXcore engine
W/jxcore-log( 4709): JXcore engine is ready
W/jxcore-log( 4709): Starting JXcore engine
I/ActivityManager(  924): Recipient 4214
W/jxcore-log( 4709): Platform android
W/jxcore-log( 4709): 
W/jxcore-log( 4709): Process ARCH arm
W/jxcore-log( 4709): 
I/ActivityManager(  924): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4894 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  924): Killing 4177:com.android.vending/u0a72 (adj 15): empty #17
I/jxcore-log( 4709): JXcore Cordova bridge is ready!
I/jxcore-log( 4709): 
W/jxcore-log( 4709): JXcore engine is started
E/jxcore-log( 4709): >> HTC-HTC One M8s
E/jxcore-log( 4709): 
I/jxcore-log( 4709): Total memory 1931808768
I/jxcore-log( 4709): 
I/jxcore-log( 4709): Free memory 94253056
I/jxcore-log( 4709): 
I/jxcore-log( 4709): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4709): 
I/jxcore-log( 4709): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4709): 
I/jxcore-log( 4709): userPath [ 'www' ]
I/jxcore-log( 4709): 
I/jxcore-log( 4709): Size 1080 1776
I/jxcore-log( 4709): 
I/jxcore-log( 4709): Screen Brightness 142
I/jxcore-log( 4709): 
E/jxcore-log( 4709): Dummy Error Log.
E/jxcore-log( 4709): 
I/ActivityManager(  924): Recipient 4177
,I/ActivityManager(  924): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4925 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  924): Killing 3300:com.android.defcontainer/u0a15 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 3300,
,I/jxcore-log( 4709): getBuffer is called!!!!
I/jxcore-log( 4709): 
,I/ActivityManager(  924): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4947 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,I/ActivityManager(  924): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4969 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  924): Killing 4373:com.google.android.youtube/u0a176 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4373
,I/ActivityManager(  924): Waited long enough for: ServiceRecord{39aedb79 u0 com.htc.HTCSpeaker/.NGFService},
,I/ActivityManager(  924): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4061): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  924): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4061): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  924): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5012 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  924): Killing 4452:com.google.android.gm/u0a106 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4452,
,I/ActivityManager(  924): Killing 4494:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4494
,W/ActivityThread( 5012): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  924): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5050 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/ActivityManager(  924): Killing 4624:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4624
,I/ActivityManager(  924): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5101 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  924): Killing 4663:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4663,
,I/ActivityManager(  924): Killing 4736:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4736
,I/ActivityManager(  924): Killing 3729:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 3729
,I/ActivityManager(  924): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5132 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
I/ActivityManager(  924): Killing 4798:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4798,
,I/ActivityManager(  924): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5155 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/ActivityManager(  924): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5181 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  924): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5210 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager(  924): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5234 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  924): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5265 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  924): Killing 4340:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4340
,I/jxcore-log( 4709): ****TEST TOOK:  5154  ms ****
I/jxcore-log( 4709): 
,I/jxcore-log( 4709): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4709): 
,I/ActivityManager(  924): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5306 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  924): Killing 4835:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4835,
,I/ActivityManager(  924): Killing 4871:com.htc.backupreset/1000 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4871
,I/ActivityManager(  924): Killing 4894:com.htc.bgp/u0a11 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4894
,I/ActivityManager(  924): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg,
I/ActivityManager(  924): Killing 4709:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  924): Recipient 4709
,W/ActivityManager(  924): Force removing ActivityRecord{df695ee u0 com.example.hello/.MainActivity t10}: app died, no saved state
,I/ActivityManager(  924): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/ActivityManager(  924): Spurious death for ProcessRecord{35a89be6 4709:com.example.hello/u0a373}, curProc for 4709: null
,I/ActivityManager(  924): Killing 4533:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4533
,W/ActivityThread( 5265): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  924): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5364 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  924): Killing 4925:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,I/ActivityManager(  924): Recipient 4925,
,I/ActivityManager(  924): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5395 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  924): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5407 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  924): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5441 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  924): Killing 4947:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  924): Recipient 4947
,I/ActivityManager(  924): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5465 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,E/ActivityManager(  924): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  924): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5496 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 3400:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432745c0 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  963): Waited long enough for: ServiceRecord{4317cac8 u0 com.lge.slideaside/.MainService}
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3994
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432745c0 stackId=1, 2 tasks}
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{432745c0 stackId=1, 2 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  963): startService SlideAside
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432745c0 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4013 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager( 4013): Timeline: Activity_idle id: android.os.BinderProxy@42807330 time:43204
I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +358ms
W/jxcore-log( 4013): Initializing JXcore engine
W/jxcore-log( 4013): JXcore engine is ready
W/jxcore-log( 4013): Starting JXcore engine
I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3} time:43619
D/ActivityManager(  963): no-history finish of ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{432a5d18 ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4013): Platform android
W/jxcore-log( 4013): 
W/jxcore-log( 4013): Process ARCH arm
W/jxcore-log( 4013): 
,I/jxcore-log( 4013): JXcore Cordova bridge is ready!
I/jxcore-log( 4013): 
,W/jxcore-log( 4013): JXcore engine is started
,E/jxcore-log( 4013): >> LGE-LG-D802
E/jxcore-log( 4013): 
,I/jxcore-log( 4013): Total memory 1943035904
I/jxcore-log( 4013): 
I/jxcore-log( 4013): Free memory 456814592
I/jxcore-log( 4013): 
I/jxcore-log( 4013): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4013): 
,I/jxcore-log( 4013): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4013): 
,I/jxcore-log( 4013): userPath [ 'www' ]
I/jxcore-log( 4013): 
,I/jxcore-log( 4013): Size 1080 1776
I/jxcore-log( 4013): 
,I/jxcore-log( 4013): Screen Brightness 255
I/jxcore-log( 4013): 
,E/jxcore-log( 4013): Dummy Error Log.
E/jxcore-log( 4013): 
,I/jxcore-log( 4013): getBuffer is called!!!!
I/jxcore-log( 4013): 
,I/ActivityManager(  963): Killing 3333:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432745c0 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 4013): ****TEST TOOK:  5038  ms ****
I/jxcore-log( 4013): 
,I/jxcore-log( 4013): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4013): 
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 4013:com.example.hello/u0a311 (adj 0): stop com.example.hello
W/ActivityManager(  963): Force removing ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43136380 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432745c0 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{42c0a130 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4101 uid=10090 gids={50090}
,I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4130 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  963): Killing 3284:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  963): Service ServiceRecord{43279bf0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43237358 3284:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  963): Service ServiceRecord{430f9ad0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43237358 3284:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4158 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  963): Killing 2078:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Delaying start of: ServiceRecord{43254188 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  963): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4174 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  963): Killing 3843:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Killing 3890:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1} time:50318
,I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4195 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  963): Killing 1879:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/ActivityManager( 1485): Timeline: Activity_idle id: android.os.BinderProxy@4280b2f8 time:50378
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Delaying start of: ServiceRecord{43282d98 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager(  963): Process android.process.media (pid 4195) has died.
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4211 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process android.process.media (pid 4211) has died.
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4224 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process com.google.android.gms (pid 1941) has died.
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
,I/ActivityManager(  963): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4241 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10989ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10987ms
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process android.process.media (pid 4224) has died.
,W/ActivityManager(  963): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 20956ms
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4257 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process android.process.media (pid 4257) has died.
,W/ActivityManager(  963): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 83824ms
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4270 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process android.process.media (pid 4270) has died.
,W/ActivityManager(  963): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
,W/ActivityManager(  963): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
,W/ActivityManager(  963): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
W/ActivityManager(  963): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 335296ms
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4283 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Process android.process.media (pid 4283) has died.
,W/ActivityManager(  963): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
,W/ActivityManager(  963): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 1341184ms
,I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4299 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baff60 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c06130 u0 com.lge.launcher2/.Launcher t1}


```

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/503880191f8da65/build_android/android_0_503880191f8da65.apk) to device 4db5c8cc protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_503880191f8da65.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system,
--------- beginning of main
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1018): mDVFSHelper.acquire()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5638 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5638): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5654 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5654): Added TimaKeyStore provider
W/ActivityThread( 5654): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 1018): Displayed Component not be shown by security: +861ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): mDVFSHelper.release()
,W/jxcore-log( 5638): Initializing JXcore engine
W/jxcore-log( 5638): JXcore engine is ready
,W/jxcore-log( 5638): Starting JXcore engine
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 5638): Platform android,
W/jxcore-log( 5638): 
W/jxcore-log( 5638): Process ARCH arm
W/jxcore-log( 5638): 
,I/jxcore-log( 5638): JXcore Cordova bridge is ready!
I/jxcore-log( 5638): 
,W/jxcore-log( 5638): JXcore engine is started
,E/jxcore-log( 5638): >> samsung-SM-A300FU
E/jxcore-log( 5638): 
,I/jxcore-log( 5638): Total memory 1451114496
I/jxcore-log( 5638): 
,I/jxcore-log( 5638): Free memory 19275776
I/jxcore-log( 5638): 
I/jxcore-log( 5638): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5638): 
I/jxcore-log( 5638): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5638): 
,I/jxcore-log( 5638): userPath [ 'www' ]
I/jxcore-log( 5638): 
,I/jxcore-log( 5638): Size 540 960,
I/jxcore-log( 5638): 
,I/jxcore-log( 5638): Screen Brightness 255,
I/jxcore-log( 5638): 
E/jxcore-log( 5638): Dummy Error Log.
E/jxcore-log( 5638): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4930:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5133:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/jxcore-log( 5638): getBuffer is called!!!!
I/jxcore-log( 5638): 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{3aef65f2 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,V/ActivityThread( 5638): updateVisibility : ActivityRecord{2f70e33e token=android.os.BinderProxy@2a6a3cab {com.example.hello/com.example.hello.MainActivity}} show : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,V/ActivityManager( 1018): Display changed displayId=0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/jxcore-log( 5638): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 5638): 
,I/jxcore-log( 5638): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5638): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5745 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,D/ActivityThread( 5745): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 4982:com.google.android.talk/u0a102 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5772 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5772): Added TimaKeyStore provider,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/ActivityManager( 1018): Killing 5167:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5638:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,D/ActivityThread( 5804): Added TimaKeyStore provider
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{4d43449 u0 com.example.hello/.MainActivity t11}
,W/ActivityManager( 1018): Spurious death for ProcessRecord{3715c846 5638:com.example.hello/u0a333}, curProc for 5638: null
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1018): Killing 5230:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Process com.android.bluetooth (pid 2626)(adj 0) has died(57,621)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2465
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2477 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
,I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +243ms
,W/jxcore-log( 2477): Initializing JXcore engine
,W/jxcore-log( 2477): JXcore engine is ready
,W/jxcore-log( 2477): Starting JXcore engine
,W/jxcore-log( 2477): Platform android
W/jxcore-log( 2477): 
,W/jxcore-log( 2477): Process ARCH arm
W/jxcore-log( 2477): 
,I/jxcore-log( 2477): JXcore Cordova bridge is ready!
I/jxcore-log( 2477): 
,W/jxcore-log( 2477): JXcore engine is started
,E/jxcore-log( 2477): >> HTC-HTC Desire 820
E/jxcore-log( 2477): 
,I/jxcore-log( 2477): Total memory 1964650496
I/jxcore-log( 2477): 
I/jxcore-log( 2477): Free memory 758476800
I/jxcore-log( 2477): 
I/jxcore-log( 2477): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2477): 
,I/jxcore-log( 2477): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2477): 
,I/jxcore-log( 2477): userPath [ 'www' ]
I/jxcore-log( 2477): 
,I/jxcore-log( 2477): Size 720 1184
I/jxcore-log( 2477): 
,I/jxcore-log( 2477): Screen Brightness 10
I/jxcore-log( 2477): 
,E/jxcore-log( 2477): Dummy Error Log.
E/jxcore-log( 2477): 
,I/jxcore-log( 2477): getBuffer is called!!!!
I/jxcore-log( 2477): 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4249db40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2522 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2535 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Killing 1673:com.htc.dotmatrix/u0a43 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 1673
,I/ActivityManager(  909): Killing 1283:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 1283
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2549 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  909): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2561 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/ActivityManager(  909): Killing 2116:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2116
,I/ActivityManager(  909): Delay finish: com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2582 uid=10016 gids={50016, 3003, 5012, 2001}
,I/ActivityManager(  909): Killing 2171:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2171
,I/ActivityManager(  909): Killing 2183:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2610 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Recipient 2183
,I/ActivityManager(  909): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2627 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Killing 2077:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2077
,I/ActivityManager(  909): Killing 2270:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2270
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/ActivityManager(  909): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2663 uid=10030 gids={50030}
,I/ActivityManager(  909): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2677 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  909): Killing 2134:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  909): Recipient 2134
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 2290:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2701 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  909): Recipient 2290
,I/ActivityManager(  909): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2714 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Killing 2258:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2258
,I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2727 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  909): Killing 2344:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2344
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2741 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  909): Killing 2051:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  909): Killing 2326:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2326
,I/ActivityManager(  909): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2755 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  909): Recipient 2051
,I/ActivityManager(  909): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2770 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  909): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2786 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  909): Killing 2311:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2311
,I/ActivityManager(  909): Killing 1769:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2801 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  909): Killing 2151:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 1769
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  909): Recipient 2151
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 2535:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Recipient 2535
,I/ActivityManager(  909): Killing 2549:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2549
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2831 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Resuming delayed broadcast
I/jxcore-log( 2477): ****TEST TOOK:  5093  ms ****
I/jxcore-log( 2477): 
I/jxcore-log( 2477): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2477): 
,I/ActivityManager(  909): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2844 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{425f7a90 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=2862 uid=10037 gids={50037, 3002, 3001}
,I/ActivityManager(  909): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2876 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  909): Killing 2582:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2582
,I/ActivityManager(  909): Killing 2610:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2610
,I/ActivityManager(  909): Killing 2561:android.process.media/u0a21 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2894 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Killing 2627:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2627
,I/ActivityManager(  909): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2907 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  909): Killing 2663:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2663
,I/ActivityManager(  909): Recipient 2561
,I/ActivityManager(  909): Killing 2677:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2677
,I/ActivityManager(  909): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=2929 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
I/ActivityManager(  909): Killing 2701:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2701
,I/ActivityManager(  909): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 2714:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2714
,I/ActivityManager(  909): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2953 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  909): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
I/ActivityManager(  909): Killing 2477:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  909): Force removing ActivityRecord{423865a0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  909): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  909): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2979 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  909): Killing 2727:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2727
,I/ActivityManager(  909): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{425f0690 u0 com.htc.autobot/.htcmodeclient.HtcModeService}


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
,--------- beginning of /dev/log/system
I/ActivityManager(  910): Killing 2652:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  910): Recipient 2652
I/ActivityManager(  910): Delay finish: com.android.settings/.NSReceiver
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3026 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  910): Killing 2685:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  910): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3074 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3015
I/ActivityManager(  910): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3086 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  910): Recipient 2685
I/ActivityManager(  910): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3098 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  910): Killing 2667:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  910): Killing 2747:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3130 uid=10041 gids={50041}
,I/ActivityManager(  910): Recipient 2667
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3151 uid=10078 gids={50078}
,I/ActivityManager(  910): Killing 2726:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2726
,I/ActivityManager(  910): Recipient 2747
,I/ActivityManager(  910): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3169 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  910): Killing 2458:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2458
,I/ActivityManager(  910): Displayed com.example.hello/.MainActivity: +319ms
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3185 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  910): Killing 2775:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2775
,I/ActivityManager(  910): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3200 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3215 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 2792:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2792
,I/ActivityManager(  910): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3234 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  910): Killing 2809:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2809
,I/ActivityManager(  910): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3246 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  910): Killing 2869:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  910): Killing 2836:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  910): Recipient 2869
I/ActivityManager(  910): Recipient 2836
,I/ActivityManager(  910): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3258 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,W/jxcore-log( 3086): Initializing JXcore engine
,W/jxcore-log( 3086): JXcore engine is ready
,W/jxcore-log( 3086): Starting JXcore engine
,I/ActivityManager(  910): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Killing 2883:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  910): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3274 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  910): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  910): Recipient 2883
,I/ActivityManager(  910): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3288 uid=10091 gids={50091, 3003, 5012}
,W/jxcore-log( 3086): Platform android
W/jxcore-log( 3086): 
,W/jxcore-log( 3086): Process ARCH arm
W/jxcore-log( 3086): 
,I/jxcore-log( 3086): JXcore Cordova bridge is ready!
I/jxcore-log( 3086): 
,W/jxcore-log( 3086): JXcore engine is started
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Killing 2895:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  910): Killing 2980:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2980
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/jxcore-log( 3086): >> HTC-HTC Desire 820
E/jxcore-log( 3086): 
,I/jxcore-log( 3086): Total memory 1964650496
I/jxcore-log( 3086): 
I/jxcore-log( 3086): Free memory 713629696
I/jxcore-log( 3086): 
,I/jxcore-log( 3086): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3086): 
I/jxcore-log( 3086): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3086): 
,I/ActivityManager(  910): Resuming delayed broadcast
,I/jxcore-log( 3086): userPath [ 'www' ]
I/jxcore-log( 3086): 
,I/jxcore-log( 3086): Size 720 1184
I/jxcore-log( 3086): 
I/jxcore-log( 3086): Screen Brightness 142
I/jxcore-log( 3086): 
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
E/jxcore-log( 3086): Dummy Error Log.
E/jxcore-log( 3086): 
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Recipient 2895
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3313 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Killing 3026:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3334 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  910): Recipient 3026
I/ActivityManager(  910): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
I/jxcore-log( 3086): getBuffer is called!!!!
I/jxcore-log( 3086): 
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Killing 3074:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  910): Recipient 3074
I/ActivityManager(  910): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3351 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3370 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 3098:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3098
,I/ActivityManager(  910): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3392 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  910): Killing 3169:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3169
,I/ActivityManager(  910): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3411 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  910): Killing 2823:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2823
,I/ActivityManager(  910): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Killing 3234:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3234
,I/ActivityManager(  910): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{426320c0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  910): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3434 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/jxcore-log( 3086): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 3086): 
,I/jxcore-log( 3086): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3086): 
,I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3474 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  910): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Killing 3246:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  910): Recipient 3246
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  910): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3502 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  910): Killing 3130:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3130
,I/ActivityManager(  910): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  910): Killing 3086:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  910): Force removing ActivityRecord{4284c4f0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  910): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3527 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3540 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 3151:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3151
,E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
,I/ActivityManager(  910): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3557 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  910): Killing 3274:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3274
,I/ActivityManager(  910): Delay finish: com.htc.backup/.task.restore.PackageInstallReceiver
I/ActivityManager(  910): Delaying start of: ServiceRecord{42682be0 u0 com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3589 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  910): Killing 3288:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3288
,I/ActivityManager(  910): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3601 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  910): Killing 3313:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3313


LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2128
I/ActivityManager(  772): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2147 uid=10001 gids={50001, 3003, 1028, 1015}
I/ActivityManager(  772): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2159 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  772): Killing 1210:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  772): Killing 1571:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #18
,I/ActivityManager(  772): Displayed com.example.hello/.MainActivity: +305ms
,W/jxcore-log( 2159): Initializing JXcore engine
,W/jxcore-log( 2159): JXcore engine is ready
,W/jxcore-log( 2159): Starting JXcore engine
,W/jxcore-log( 2159): Platform android
W/jxcore-log( 2159): 
,W/jxcore-log( 2159): Process ARCH arm
W/jxcore-log( 2159): 
,I/jxcore-log( 2159): JXcore Cordova bridge is ready!
I/jxcore-log( 2159): 
,W/jxcore-log( 2159): JXcore engine is started
,E/jxcore-log( 2159): >> LGE-Nexus 5
E/jxcore-log( 2159): 
,I/jxcore-log( 2159): Total memory 1945137152
I/jxcore-log( 2159): 
I/jxcore-log( 2159): Free memory 913408000
I/jxcore-log( 2159): 
I/jxcore-log( 2159): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2159): 
,I/jxcore-log( 2159): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2159): 
,I/jxcore-log( 2159): userPath [ 'www' ]
I/jxcore-log( 2159): 
,I/jxcore-log( 2159): Size 1080 1776
I/jxcore-log( 2159): 
I/jxcore-log( 2159): Screen Brightness 82
I/jxcore-log( 2159): 
,E/jxcore-log( 2159): Dummy Error Log.
E/jxcore-log( 2159): 
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Killing 1602:com.android.vending/u0a14 (adj 15): empty #17
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
,I/jxcore-log( 2159): getBuffer is called!!!!
I/jxcore-log( 2159): 
I/ActivityManager(  772): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2266 uid=10011 gids={50011, 3003}
,I/ActivityManager(  772): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2282 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  772): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2297 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  772): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  772): Delaying start of: ServiceRecord{42ef4718 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2339 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
I/ActivityManager(  772): Killing 1673:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Killing 1703:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  772): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2367 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  772): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2385 uid=10035 gids={50035, 1028, 3003, 1015}
,I/ActivityManager(  772): Killing 1751:com.google.android.keep/u0a52 (adj 15): empty #17
,W/ActivityManager(  772): No permission grants found for com.quickoffice.android
,I/ActivityManager(  772): Killing 1780:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  772): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  772): Killing 1089:com.android.printspooler/u0a64 (adj 15): empty #17
,I/ActivityManager(  772): Waited long enough for: ServiceRecord{42b9ac88 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Waited long enough for: ServiceRecord{42db3cb8 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/jxcore-log( 2159): ****TEST TOOK:  5021  ms ****
I/jxcore-log( 2159): 
,I/jxcore-log( 2159): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2159): 
,I/ActivityManager(  772): Killing 1834:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/ActivityManager(  772): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  772): Killing 2159:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  772): Force removing ActivityRecord{42f105c0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  772): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  772): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2508 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  772): Resuming delayed broadcast
I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2536 uid=10034 gids={50034}
,I/ActivityManager(  772): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2556 uid=10006 gids={50006, 1028, 1015, 1023}
,I/ActivityManager(  772): Killing 1922:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  772): Service ServiceRecord{42dcc710 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42caafa0 1922:com.google.android.youtube/u0a71} not same as in map: null
,I/ActivityManager(  772): Killing 1686:com.google.android.deskclock/u0a33 (adj 15): empty #17


```


