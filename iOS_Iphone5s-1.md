#### Test 5038801932cd575_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9D866444-B8B7-4B5E-9C0A-9319B1198067/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9D866444-B8B7-4B5E-9C0A-9319B1198067/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5038801932cd575/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C475A174-B6EA-422A-8799-587D9764EB8A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54017"
,(lldb)     command script import "/tmp/9D866444-B8B7-4B5E-9C0A-9319B1198067/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 22:44:32.657 HelloWorld[1418:1178714] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1879315D-6915-4600-8483-F96B6FF02402/Library/Cookies/Cookies.binarycookies
,2015-11-23 22:44:33.016 HelloWorld[1418:1178714] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 22:44:33.017 HelloWorld[1418:1178714] Multi-tasking -> Device: YES, App: YES
,2015-11-23 22:44:33.020 HelloWorld[1418:1178714] Unlimited access to network resources
,2015-11-23 22:44:33.026 HelloWorld[1418:1178714] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 22:44:36.987 HelloWorld[1418:1178714] Resetting plugins due to page load.
,2015-11-23 22:44:37.444 HelloWorld[1418:1178714] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/C475A174-B6EA-422A-8799-587D9764EB8A/HelloWorld.app/www/index.html
,2015-11-23 22:44:37.507 HelloWorld[1418:1178714] JXcore Cordova plugin initializing
2015-11-23 22:44:37.508 HelloWorld[1418:1178824] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 209924096
execPath /private/var/mobile/Containers/Bundle/Application/C475A174-B6EA-422A-8799-587D9764EB8A/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/C4,75A174-B6EA-422A-8799-587D9764EB8A/HelloWorld.app/www/jxcore/
,userPath []
2015-11-23 22:44:37.745 HelloWorld[1418:1178824] Native method ScreenInfo not found.
2015-11-23 22:44:37.745 HelloWorld[1418:1178824] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5122  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
