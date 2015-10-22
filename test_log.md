#### Test 480337895cdc0dc Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
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

UT166453 added test : test connectionTable table building and cleanup

got connection

UT76056 added test : test connectionTable table building and cleanup

got connection

UT95621 added test : test connectionTable table building and cleanup

UT166453 is now disconnected!

~ UT166453 test test connectionTable table building and cleanup done!
this.testingCurrently is null

UT95621 is now disconnected!
~ UT95621 test test connectionTable table building and cleanup done!
this.testingCurrently is null


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```
###iOS Logs

```
Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B11C7406-B949-4F00-9CA1-19CF634233CD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B11C7406-B949-4F00-9CA1-19CF634233CD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/3F2E4D4A-200B-4146-BFE2-8844CB4EAD3A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51437"
,(lldb)     command script import "/tmp/B11C7406-B949-4F00-9CA1-19CF634233CD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 12:32:15.002 ThaliTest[583:60b] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 12:32:15.006 ThaliTest[583:60b] Multi-tasking -> Device: YES, App: YES
,2015-10-22 12:32:15.013 ThaliTest[583:60b] Unlimited access to network resources
,2015-10-22 12:32:15.019 ThaliTest[583:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 12:32:25.147 ThaliTest[583:60b] Resetting plugins due to page load.
,2015-10-22 12:32:25.964 ThaliTest[583:60b] Finished load of: file:///var/mobile/Applications/3F2E4D4A-200B-4146-BFE2-8844CB4EAD3A/ThaliTest.app/www/index.html
,2015-10-22 12:32:26.146 ThaliTest[583:60b] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2015-10-22 12:32:26.149 ThaliTest[583:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Turning radios to true
,Warning: iOS does not support ToggleBluetooth
We could not set Bluetooth! - Warning: iOS does not support ToggleBluetooth
,toggleBluetooth - 
Warning: iOS does not support ToggleWiFi
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
[100%] Installed package /Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F4B8A8BA-994D-46C7-9969-71586DE9B361/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F4B8A8BA-994D-46C7-9969-71586DE9B361/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/26F33428-A845-467B-A31E-1E83C49FAC7E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51445"
,(lldb)     command script import "/tmp/F4B8A8BA-994D-46C7-9969-71586DE9B361/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 12:31:28.411 ThaliTest[1149:953454] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5DA454B4-4B2B-4379-8177-022113318D66/Library/Cookies/Cookies.binarycookies
,2015-10-22 12:31:28.807 ThaliTest[1149:953454] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 12:31:28.808 ThaliTest[1149:953454] Multi-tasking -> Device: YES, App: YES
,2015-10-22 12:31:28.816 ThaliTest[1149:953454] Unlimited access to network resources
,2015-10-22 12:31:28.823 ThaliTest[1149:953454] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 12:31:32.610 ThaliTest[1149:953454] Resetting plugins due to page load.
,2015-10-22 12:31:33.064 ThaliTest[1149:953454] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/26F33428-A845-467B-A31E-1E83C49FAC7E/ThaliTest.app/www/index.html
,2015-10-22 12:31:33.263 ThaliTest[1149:953454] JXcore Cordova plugin initializing
2015-10-22 12:31:33.264 ThaliTest[1149:953592] JXcore instance initializing
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
toggleBluetooth - 
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



Iphone5s-1: 
[....] Waiting for iOS device to be connected
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,[....] Using iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,------ Install phase ------
,[  0%] Found iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB, beginning install
,[  5%] Copying /Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app/META-INF/ to device
,2015-10-22 12:28:42.011 ios-deploy[48607:4016187] [ !! ] Error 0xe8000010: The file already exists. AMDeviceSecureTransferPath(0, device, url, options, transfer_callback, 0)



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E99618F7-1C59-4B8A-BBB5-477A130C77C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E99618F7-1C59-4B8A-BBB5-477A130C77C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/480337895cdc0dc/build_ios/ThaliBuild/ThaliTest/platforms/ios/build/device/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59FF728B-D296-42C4-A9E2-FBDAA700F8E5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51435"
,(lldb)     command script import "/tmp/E99618F7-1C59-4B8A-BBB5-477A130C77C2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-22 12:31:10.584 ThaliTest[800:1204491] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EDC98FA7-52CD-4286-80E7-3074885905E4/Library/Cookies/Cookies.binarycookies
,2015-10-22 12:31:11.046 ThaliTest[800:1204491] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-22 12:31:11.048 ThaliTest[800:1204491] Multi-tasking -> Device: YES, App: YES
,2015-10-22 12:31:11.057 ThaliTest[800:1204491] Unlimited access to network resources
,2015-10-22 12:31:11.069 ThaliTest[800:1204491] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-22 12:31:19.741 ThaliTest[800:1204491] Resetting plugins due to page load.
,2015-10-22 12:31:22.841 ThaliTest[800:1204491] Finished load of: file:///var/mobile/Containers/Bundle/Application/59FF728B-D296-42C4-A9E2-FBDAA700F8E5/ThaliTest.app/www/index.html
,2015-10-22 12:31:23.017 ThaliTest[800:1204491] JXcore Cordova plugin initializing
,2015-10-22 12:31:23.018 ThaliTest[800:1204730] JXcore instance initializing
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
LogCallback not set !!!!



server: 
Unexpected exit on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 app:Iphone5s-1 code:253,iOS application timeout
,Unexpected exit on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe app:IpadAir2-1 code:null,Unexpected exit on device 17df3859480c382d3b761fa2643dde395ced1bd8 app:Iphone5-1 code:null,Unexpected exit on device 2a65f58f9902a701b5c9a55b2befb18672927474 app:Iphone6-1 code:null


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

UT166453 added test : test connectionTable table building and cleanup

got connection

UT76056 added test : test connectionTable table building and cleanup

got connection

UT95621 added test : test connectionTable table building and cleanup

UT166453 is now disconnected!

~ UT166453 test test connectionTable table building and cleanup done!
this.testingCurrently is null

UT95621 is now disconnected!
~ UT95621 test test connectionTable table building and cleanup done!
this.testingCurrently is null


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

