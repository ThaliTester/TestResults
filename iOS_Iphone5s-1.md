#### Test 50242285576d0b0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6B5B8969-46C7-4AF9-8B20-F061D21F6DC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6B5B8969-46C7-4AF9-8B20-F061D21F6DC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285576d0b0/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/78832DCE-4426-4C09-BE31-450114512650/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49227"
,(lldb)     command script import "/tmp/6B5B8969-46C7-4AF9-8B20-F061D21F6DC8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-06 15:07:47.258 HelloWorld[292:14310] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C3EEDA5-924E-4C08-9F67-5C609B5CC220/Library/Cookies/Cookies.binarycookies
,2015-12-06 15:07:47.766 HelloWorld[292:14310] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-06 15:07:47.768 HelloWorld[292:14310] Multi-tasking -> Device: YES, App: YES
,2015-12-06 15:07:47.777 HelloWorld[292:14310] Unlimited access to network resources
,2015-12-06 15:07:47.794 HelloWorld[292:14310] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-06 15:07:56.981 HelloWorld[292:14310] Resetting plugins due to page load.
,2015-12-06 15:08:00.432 HelloWorld[292:14310] Finished load of: file:///var/mobile/Containers/Bundle/Application/78832DCE-4426-4C09-BE31-450114512650/HelloWorld.app/www/index.html
,2015-12-06 15:08:00.534 HelloWorld[292:14310] JXcore Cordova plugin initializing
2015-12-06 15:08:00.535 HelloWorld[292:14509] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1048576000
Free memory 800440320
execPath /private/var/mobile/Containers/Bundle/Application/78832DCE-4426-4C09-BE31-450114512650/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/78832DCE-4426-4C09-BE31-450114512650/HelloWorld.app/www/jxcore/
,userPath []
2015-12-06 15:08:00.786 HelloWorld[292:14509] Native method ScreenInfo not found.
2015-12-06 15:08:00.786 HelloWorld[292:14509] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5121  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
