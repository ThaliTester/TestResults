#### Test 503880190437b9b_iOS_Iphone5s-1 Logs


```[100%] Installed package /Users/thali/Github/CI/builder/builds/503880190437b9b/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A6356C8C-106C-46C6-A2C3-08CFB7643334/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A6356C8C-106C-46C6-A2C3-08CFB7643334/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880190437b9b/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880190437b9b/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/463C8799-0C30-412F-9A30-536B6CA407CC/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53290"
,(lldb)     command script import "/tmp/A6356C8C-106C-46C6-A2C3-08CFB7643334/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 17:59:29.440 HelloWorld[641:441556] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2C4BA0B-38DE-433A-9ABC-FB29C2757801/Library/Cookies/Cookies.binarycookies
,2015-11-17 17:59:29.801 HelloWorld[641:441556] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 17:59:29.802 HelloWorld[641:441556] Multi-tasking -> Device: YES, App: YES
,2015-11-17 17:59:29.805 HelloWorld[641:441556] Unlimited access to network resources
,2015-11-17 17:59:29.811 HelloWorld[641:441556] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 17:59:33.664 HelloWorld[641:441556] Resetting plugins due to page load.
,2015-11-17 17:59:34.016 HelloWorld[641:441556] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/463C8799-0C30-412F-9A30-536B6CA407CC/HelloWorld.app/www/index.html
,2015-11-17 17:59:34.122 HelloWorld[641:441556] JXcore Cordova plugin initializing
2015-11-17 17:59:34.123 HelloWorld[641:441668] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1047695360
Free memory 248856576
execPath /private/var/mobile/Containers/Bundle/Application/463C8799-0C30-412F-9A30-536B6CA407CC/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/463C8799-0C30-412F-9A30,-536B6CA407CC/HelloWorld.app/www/jxcore/
userPath []
2015-11-17 17:59:34.381 HelloWorld[641:441668] Native method ScreenInfo not found.
2015-11-17 17:59:34.382 HelloWorld[641:441668] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
```
