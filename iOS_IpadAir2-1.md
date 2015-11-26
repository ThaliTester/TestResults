#### Test 5065027860a4eba_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C30AA722-8DDF-4AF0-826B-B3B43191D0C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C30AA722-8DDF-4AF0-826B-B3B43191D0C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24AE08C9-3874-401E-81C1-A1AD310DC08E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56359"
,(lldb)     command script import "/tmp/C30AA722-8DDF-4AF0-826B-B3B43191D0C2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 17:30:36.174 ThaliTest[1391:1909695] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E67F2CA-0925-4FE9-9C49-0DF89D814BAD/Library/Cookies/Cookies.binarycookies
,2015-11-26 17:30:36.457 ThaliTest[1391:1909695] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 17:30:36.458 ThaliTest[1391:1909695] Multi-tasking -> Device: YES, App: YES
,2015-11-26 17:30:36.464 ThaliTest[1391:1909695] Unlimited access to network resources
,2015-11-26 17:30:36.470 ThaliTest[1391:1909695] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 17:30:40.720 ThaliTest[1391:1909695] Resetting plugins due to page load.
,2015-11-26 17:30:42.159 ThaliTest[1391:1909695] Finished load of: file:///var/mobile/Containers/Bundle/Application/24AE08C9-3874-401E-81C1-A1AD310DC08E/ThaliTest.app/www/index.html
,2015-11-26 17:30:42.307 ThaliTest[1391:1909695] JXcore Cordova plugin initializing
,2015-11-26 17:30:42.308 ThaliTest[1391:1909908] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-IpadAir2-1_PT3189
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
