#### Test 50242285e132180_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6CE0F407-04BA-489A-ACC6-3DBF35BCE78F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6CE0F407-04BA-489A-ACC6-3DBF35BCE78F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/68368C5A-D411-4F65-A08B-FE6C3FB0AABA/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50201"
,(lldb)     command script import "/tmp/6CE0F407-04BA-489A-ACC6-3DBF35BCE78F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 16:09:54.520 HelloWorld[405:151910] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A62FF0FC-9F3A-4F79-8B5F-9CD59AB1D151/Library/Cookies/Cookies.binarycookies
,2015-12-07 16:09:54.902 HelloWorld[405:151910] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 16:09:54.904 HelloWorld[405:151910] Multi-tasking -> Device: YES, App: YES
,2015-12-07 16:09:54.908 HelloWorld[405:151910] Unlimited access to network resources
,2015-12-07 16:09:54.919 HelloWorld[405:151910] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 16:10:03.814 HelloWorld[405:151910] Resetting plugins due to page load.
,2015-12-07 16:10:06.856 HelloWorld[405:151910] Finished load of: file:///var/mobile/Containers/Bundle/Application/68368C5A-D411-4F65-A08B-FE6C3FB0AABA/HelloWorld.app/www/index.html
,2015-12-07 16:10:06.951 HelloWorld[405:151910] JXcore Cordova plugin initializing
2015-12-07 16:10:06.952 HelloWorld[405:152127] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1037041664
Free memory 593264640
execPath /private/var/mobile/Containers/Bundle/Application/68368C5A-D411-4F65-A08B-FE6C3FB0AABA/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/68368C5A-D411-4F65-A08B-FE6C3FB0AABA/HelloWorld.app/www/jxcore/
userPath []
2015-12-07 16:10:07.166 HelloWorld[405:152127] Native method ScreenInfo not found.
2015-12-07 16:10:07.166 HelloWorld[405:152127] Native method ScreenBrightness not found.
Dummy Error Log,.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5123  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
