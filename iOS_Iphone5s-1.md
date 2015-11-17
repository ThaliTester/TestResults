#### Test 503880196ac79ce_iOS_Iphone5s-1 Logs


```[100%] Installed package /Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/17FE714C-A911-4DCF-AD62-58196C622E1C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/17FE714C-A911-4DCF-AD62-58196C622E1C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880196ac79ce/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDBA1908-275B-4E26-BF21-9633B6A382EB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53693"
,(lldb)     command script import "/tmp/17FE714C-A911-4DCF-AD62-58196C622E1C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 18:28:39.660 HelloWorld[669:445964] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E3FEA7DF-CEB4-4F49-8D2F-A829DE996008/Library/Cookies/Cookies.binarycookies
,2015-11-17 18:28:40.045 HelloWorld[669:445964] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 18:28:40.046 HelloWorld[669:445964] Multi-tasking -> Device: YES, App: YES
,2015-11-17 18:28:40.049 HelloWorld[669:445964] Unlimited access to network resources
,2015-11-17 18:28:40.055 HelloWorld[669:445964] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 18:28:43.965 HelloWorld[669:445964] Resetting plugins due to page load.
,2015-11-17 18:28:44.408 HelloWorld[669:445964] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/EDBA1908-275B-4E26-BF21-9633B6A382EB/HelloWorld.app/www/index.html
,2015-11-17 18:28:44.471 HelloWorld[669:445964] JXcore Cordova plugin initializing
,2015-11-17 18:28:44.473 HelloWorld[669:446092] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 244928512
execPath /private/var/mobile/Containers/Bundle/Application/EDBA1908-275B-4E26-BF21-9633B6A382EB/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/EDBA1908-275B-4E26-BF21-9633B6A382EB/HelloWorld.app/www/jxcore/
userPath []
2015-11-17 18:28:44.712 HelloWorld[669:446092] Native method ScreenInfo not found.
2015-11-17 18:28:44.713 HelloWorld[669:446092] Native method ScreenBrightness not found.
Dummy ,Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5120  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
```
