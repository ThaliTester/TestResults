#### Test 503880197c51433_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8973468C-1DE0-4314-875F-531EA79B3E72/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8973468C-1DE0-4314-875F-531EA79B3E72/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/856F726D-0D49-4148-865F-5A535B3945EF/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53720"
,(lldb)     command script import "/tmp/8973468C-1DE0-4314-875F-531EA79B3E72/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 18:14:11.148 HelloWorld[1393:1157223] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76B6A6FF-1AE0-4A91-903A-C6823341F183/Library/Cookies/Cookies.binarycookies
,2015-11-23 18:14:11.532 HelloWorld[1393:1157223] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 18:14:11.533 HelloWorld[1393:1157223] Multi-tasking -> Device: YES, App: YES
,2015-11-23 18:14:11.541 HelloWorld[1393:1157223] Unlimited access to network resources
,2015-11-23 18:14:11.549 HelloWorld[1393:1157223] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 18:14:15.445 HelloWorld[1393:1157223] Resetting plugins due to page load.
,2015-11-23 18:14:15.785 HelloWorld[1393:1157223] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/856F726D-0D49-4148-865F-5A535B3945EF/HelloWorld.app/www/index.html
,2015-11-23 18:14:15.871 HelloWorld[1393:1157223] JXcore Cordova plugin initializing
2015-11-23 18:14:15.873 HelloWorld[1393:1157325] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 204447744
execPath /private/var/mobile/Containers/Bundle/Application/856F726D-0D49-4148-865F-5A535B3945EF/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/85,6F726D-0D49-4148-865F-5A535B3945EF/HelloWorld.app/www/jxcore/
userPath []
2015-11-23 18:14:16.137 HelloWorld[1393:1157325] Native method ScreenInfo not found.
2015-11-23 18:14:16.137 HelloWorld[1393:1157325] Native method ScreenBrightness not found.
Du,mmy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
