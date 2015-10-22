#### Test 48033789db142f1 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
Star Android tests : performance tests, start tests with undefined devices

Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Test[1]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Star iOs tests : performance tests, start tests with 4 devices
Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Test[1]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}

listening on *:3000

got connection

UT808230 added test : test connectionTable table building and cleanup

got connection

UT418335 added test : test connectionTable table building and cleanup

got connection

UT982978 added test : test connectionTable table building and cleanup

UT808230 is now disconnected!

~ UT808230 test test connectionTable table building and cleanup done!

this.testingCurrently is null

UT982978 is now disconnected!

~ UT982978 test test connectionTable table building and cleanup done!
this.testingCurrently is null


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```
###iOS Logs

```
Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/861FFE4D-B6E2-4D1E-BAA0-2300A9549A07/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/861FFE4D-B6E2-4D1E-BAA0-2300A9549A07/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/94787A89-6859-41F7-872E-CB19325C3C17/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51079"
,(lldb)     command script import "/tmp/861FFE4D-B6E2-4D1E-BAA0-2300A9549A07/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 10:17:41.922 ThaliTest[573:60b] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 10:17:41.926 ThaliTest[573:60b] Multi-tasking -> Device: YES, App: YES
,2015-10-22 10:17:41.933 ThaliTest[573:60b] Unlimited access to network resources
,2015-10-22 10:17:41.939 ThaliTest[573:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 10:17:52.122 ThaliTest[573:60b] Resetting plugins due to page load.
,2015-10-22 10:17:52.940 ThaliTest[573:60b] Finished load of: file:///var/mobile/Applications/94787A89-6859-41F7-872E-CB19325C3C17/ThaliTest.app/www/index.html
,2015-10-22 10:17:53.118 ThaliTest[573:60b] JXcore Cordova plugin initializing
,2015-10-22 10:17:53.121 ThaliTest[573:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Test app app.js loaded
,{"type":"test","name":"setup","id":0}
,LogCallback not set !!!!



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/109A9EBF-9373-4A42-B2A0-82E7F2276E92/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/109A9EBF-9373-4A42-B2A0-82E7F2276E92/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5710F58B-E1DD-4638-A847-D9EFF9AF8F48/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51081"
,(lldb)     command script import "/tmp/109A9EBF-9373-4A42-B2A0-82E7F2276E92/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 10:16:59.198 ThaliTest[1134:941710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/900C827E-0568-43B7-B9A1-F73865FFE4CF/Library/Cookies/Cookies.binarycookies
,2015-10-22 10:16:59.587 ThaliTest[1134:941710] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 10:16:59.588 ThaliTest[1134:941710] Multi-tasking -> Device: YES, App: YES
,2015-10-22 10:16:59.597 ThaliTest[1134:941710] Unlimited access to network resources
,2015-10-22 10:16:59.603 ThaliTest[1134:941710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 10:17:03.036 ThaliTest[1134:941710] Resetting plugins due to page load.
,2015-10-22 10:17:03.391 ThaliTest[1134:941710] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5710F58B-E1DD-4638-A847-D9EFF9AF8F48/ThaliTest.app/www/index.html
,2015-10-22 10:17:03.513 ThaliTest[1134:941710] JXcore Cordova plugin initializing
,2015-10-22 10:17:03.514 ThaliTest[1134:941837] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
We could not set WiFi! - Warning: iOS does not support ToggleWiFi
,toggleWiFi
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Test app app.js loaded
,{"type":"test","name":"setup","id":0}
LogCallback not set !!!!



Iphone5s-1: 
[....] Waiting for iOS device to be connected
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,[....] Using iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,------ Install phase ------
,[  0%] Found iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB, beginning install
,[  5%] Copying /Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app/META-INF/ to device
,2015-10-22 10:14:12.886 ios-deploy[43073:3958846] [ !! ] Error 0xe8000010: The file already exists. AMDeviceSecureTransferPath(0, device, url, options, transfer_callback, 0)



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F4A71DBC-F3F7-43A7-BD9C-6DC67D4AB4F8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F4A71DBC-F3F7-43A7-BD9C-6DC67D4AB4F8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/48033789db142f1/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FC139B9C-0A20-4D02-BB4A-45A4D9564138/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51077"
,(lldb)     command script import "/tmp/F4A71DBC-F3F7-43A7-BD9C-6DC67D4AB4F8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 10:16:41.700 ThaliTest[789:1189372] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/671FDFFF-98EF-45D6-94CB-9B47435791E6/Library/Cookies/Cookies.binarycookies
,2015-10-22 10:16:42.199 ThaliTest[789:1189372] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 10:16:42.201 ThaliTest[789:1189372] Multi-tasking -> Device: YES, App: YES
,2015-10-22 10:16:42.210 ThaliTest[789:1189372] Unlimited access to network resources
,2015-10-22 10:16:42.226 ThaliTest[789:1189372] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 10:16:51.157 ThaliTest[789:1189372] Resetting plugins due to page load.
,2015-10-22 10:16:54.614 ThaliTest[789:1189372] Finished load of: file:///var/mobile/Containers/Bundle/Application/FC139B9C-0A20-4D02-BB4A-45A4D9564138/ThaliTest.app/www/index.html
,2015-10-22 10:16:54.797 ThaliTest[789:1189372] JXcore Cordova plugin initializing
,2015-10-22 10:16:54.798 ThaliTest[789:1189602] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
Warning: iOS does not support ToggleBluetooth
,We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
,Warning: iOS does not support ToggleWiFi
,We could not set WiFi! - Warning: iOS does not support ToggleWiFi
toggleWiFi
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Attempting to connect to the test coordinator server
,Test app app.js loaded
,{"type":"test","name":"setup","id":0}
,LogCallback not set !!!!



server: 
Unexpected exit on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 app:Iphone5s-1 code:253,iOS application timeout
,Unexpected exit on device 17df3859480c382d3b761fa2643dde395ced1bd8 app:Iphone5-1 code:null,Unexpected exit on device 2a65f58f9902a701b5c9a55b2befb18672927474 app:Iphone6-1 code:null,Unexpected exit on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe app:IpadAir2-1 code:null


```



#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
Star Android tests : performance tests, start tests with undefined devices

Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Test[1]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Star iOs tests : performance tests, start tests with 4 devices
Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}
Test[1]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"20","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"10"}

listening on *:3000

got connection

UT808230 added test : test connectionTable table building and cleanup

got connection

UT418335 added test : test connectionTable table building and cleanup

got connection

UT982978 added test : test connectionTable table building and cleanup

UT808230 is now disconnected!

~ UT808230 test test connectionTable table building and cleanup done!

this.testingCurrently is null

UT982978 is now disconnected!

~ UT982978 test test connectionTable table building and cleanup done!
this.testingCurrently is null


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

