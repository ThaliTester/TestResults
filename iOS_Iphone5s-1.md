#### Test 5065027860a4eba_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6E952FC1-1DCB-48FC-AF8B-135D7FD0B59A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6E952FC1-1DCB-48FC-AF8B-135D7FD0B59A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860a4eba/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F23BBFC1-B18A-4B0A-B3C4-8A6FA080EA6B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56365"
,(lldb)     command script import "/tmp/6E952FC1-1DCB-48FC-AF8B-135D7FD0B59A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 17:31:24.753 ThaliTest[1747:1508373] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/27EA59F5-8DE0-49BC-A559-3CD906A14729/Library/Cookies/Cookies.binarycookies
,2015-11-26 17:31:25.162 ThaliTest[1747:1508373] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 17:31:25.164 ThaliTest[1747:1508373] Multi-tasking -> Device: YES, App: YES
,2015-11-26 17:31:25.173 ThaliTest[1747:1508373] Unlimited access to network resources
,2015-11-26 17:31:25.181 ThaliTest[1747:1508373] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 17:31:28.562 ThaliTest[1747:1508373] Resetting plugins due to page load.
,2015-11-26 17:31:28.997 ThaliTest[1747:1508373] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F23BBFC1-B18A-4B0A-B3C4-8A6FA080EA6B/ThaliTest.app/www/index.html
,2015-11-26 17:31:29.148 ThaliTest[1747:1508373] JXcore Cordova plugin initializing
2015-11-26 17:31:29.149 ThaliTest[1747:1508494] JXcore instance initializing
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone5s-1_PT4415
,check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded

```
