#### Test 50242285e707819_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/199DDA51-61E2-4094-8B87-82ABEF3D791F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/199DDA51-61E2-4094-8B87-82ABEF3D791F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DA2D2601-BAAD-44BC-8A0E-D89EF4E11005/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50078"
,(lldb)     command script import "/tmp/199DDA51-61E2-4094-8B87-82ABEF3D791F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:34:07.480 HelloWorld[398:148092] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9523710-3AC9-4741-81B3-34AF10BA7C15/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:34:07.886 HelloWorld[398:148092] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:34:07.888 HelloWorld[398:148092] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:34:07.891 HelloWorld[398:148092] Unlimited access to network resources
,2015-12-07 15:34:07.901 HelloWorld[398:148092] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:34:16.545 HelloWorld[398:148092] Resetting plugins due to page load.
,2015-12-07 15:34:19.603 HelloWorld[398:148092] Finished load of: file:///var/mobile/Containers/Bundle/Application/DA2D2601-BAAD-44BC-8A0E-D89EF4E11005/HelloWorld.app/www/index.html
,2015-12-07 15:34:19.682 HelloWorld[398:148092] JXcore Cordova plugin initializing
,2015-12-07 15:34:19.684 HelloWorld[398:148290] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1037041664
Free memory 549224448
execPath /private/var/mobile/Containers/Bundle/Application/DA2D2601-BAAD-44BC-8A0E-D89EF4E11005/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/DA2D2601-BA,AD-44BC-8A0E-D89EF4E11005/HelloWorld.app/www/jxcore/
userPath []
2015-12-07 15:34:19.897 HelloWorld[398:148290] Native method ScreenInfo not found.
2015-12-07 15:34:19.897 HelloWorld[398:148290] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5123  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
