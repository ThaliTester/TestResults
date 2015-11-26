#### Test 5065027860a4eba_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E477F1CE-6F8A-4B4D-922D-FE1C60BDFB74/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E477F1CE-6F8A-4B4D-922D-FE1C60BDFB74/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FF9AD2E6-A823-48F1-B073-1A0339F58256/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56361"
,(lldb)     command script import "/tmp/E477F1CE-6F8A-4B4D-922D-FE1C60BDFB74/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 17:31:23.562 ThaliTest[1794:1429932] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6031DD0-BB58-4EE8-AFF1-4BE248BCBDDC/Library/Cookies/Cookies.binarycookies
,2015-11-26 17:31:23.951 ThaliTest[1794:1429932] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 17:31:23.952 ThaliTest[1794:1429932] Multi-tasking -> Device: YES, App: YES
,2015-11-26 17:31:23.960 ThaliTest[1794:1429932] Unlimited access to network resources
,2015-11-26 17:31:23.966 ThaliTest[1794:1429932] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 17:31:27.608 ThaliTest[1794:1429932] Resetting plugins due to page load.
,2015-11-26 17:31:27.941 ThaliTest[1794:1429932] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/FF9AD2E6-A823-48F1-B073-1A0339F58256/ThaliTest.app/www/index.html
,2015-11-26 17:31:28.066 ThaliTest[1794:1429932] JXcore Cordova plugin initializing
,2015-11-26 17:31:28.067 ThaliTest[1794:1430069] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT922
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
