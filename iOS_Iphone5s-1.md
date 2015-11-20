#### Test 50388019aa1a16d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A295E1B9-8ABD-4E19-95A5-530EC04743E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A295E1B9-8ABD-4E19-95A5-530EC04743E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4100734A-6B34-4701-8FB0-9E1DDAB9143A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51009"
,(lldb)     command script import "/tmp/A295E1B9-8ABD-4E19-95A5-530EC04743E0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 12:48:11.025 HelloWorld[1000:774640] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB25BB04-7A5A-4A55-8A96-F9ED60D05EDA/Library/Cookies/Cookies.binarycookies
,2015-11-20 12:48:11.411 HelloWorld[1000:774640] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 12:48:11.412 HelloWorld[1000:774640] Multi-tasking -> Device: YES, App: YES
,2015-11-20 12:48:11.421 HelloWorld[1000:774640] Unlimited access to network resources
,2015-11-20 12:48:11.429 HelloWorld[1000:774640] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 12:48:15.261 HelloWorld[1000:774640] Resetting plugins due to page load.
,2015-11-20 12:48:15.473 HelloWorld[1000:774640] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/4100734A-6B34-4701-8FB0-9E1DDAB9143A/HelloWorld.app/www/index.html
,2015-11-20 12:48:15.525 HelloWorld[1000:774640] JXcore Cordova plugin initializing
2015-11-20 12:48:15.525 HelloWorld[1000:774774] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 213753856
execPath /private/var/mobile/Containers/Bundle/Application/4100734A-6B34-4701-8FB0-9E1DDAB9143A/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/4100734A-6B34-4701-8FB0-9E1DDAB9143A/HelloWorld.app/www/jxcore/
,userPath []
2015-11-20 12:48:15.771 HelloWorld[1000:774774] Native method ScreenInfo not found.
2015-11-20 12:48:15.772 HelloWorld[1000:774774] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
