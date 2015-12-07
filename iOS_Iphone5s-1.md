#### Test 502422852e23b2c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E7B46ECD-ADAB-4020-AD3E-9D38DEAF05F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E7B46ECD-ADAB-4020-AD3E-9D38DEAF05F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/391D01C7-1216-48A1-8FF4-4555D67C8D3F/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49939"
,(lldb)     command script import "/tmp/E7B46ECD-ADAB-4020-AD3E-9D38DEAF05F4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:06:11.733 HelloWorld[382:148093] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5968323A-535C-415C-961B-893659AABEB8/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:06:12.120 HelloWorld[382:148093] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:06:12.122 HelloWorld[382:148093] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:06:12.131 HelloWorld[382:148093] Unlimited access to network resources
,2015-12-07 15:06:12.144 HelloWorld[382:148093] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:06:20.395 HelloWorld[382:148093] Resetting plugins due to page load.
,2015-12-07 15:06:23.801 HelloWorld[382:148093] Finished load of: file:///var/mobile/Containers/Bundle/Application/391D01C7-1216-48A1-8FF4-4555D67C8D3F/HelloWorld.app/www/index.html
,2015-12-07 15:06:23.913 HelloWorld[382:148093] JXcore Cordova plugin initializing
,2015-12-07 15:06:23.914 HelloWorld[382:148330] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1048576000
Free memory 948240384
execPath /private/var/mobile/Containers/Bundle/Application/391D01C7-1216-48A1-8FF4-4555D67C8D3F/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/391D01C7-1,216-48A1-8FF4-4555D67C8D3F/HelloWorld.app/www/jxcore/
userPath []
2015-12-07 15:06:24.169 HelloWorld[382:148330] Native method ScreenInfo not found.
2015-12-07 15:06:24.169 HelloWorld[382:148330] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5129  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
