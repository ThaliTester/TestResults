#### Test 502422852e23b2c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0D903159-A289-49BB-9527-8A81A8775D8D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0D903159-A289-49BB-9527-8A81A8775D8D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24843471-DA3A-4E32-9417-DEF48B414493/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49935"
,(lldb)     command script import "/tmp/0D903159-A289-49BB-9527-8A81A8775D8D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:06:05.808 HelloWorld[388:144861] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7893876C-66A9-4CA3-8E06-1C6151F63D94/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:06:06.084 HelloWorld[388:144861] Apache Cordova native platform version 3.9.2 is starting.
2015-12-07 15:06:06.085 HelloWorld[388:144861] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:06:06.092 HelloWorld[388:144861] Unlimited access to network resources
,2015-12-07 15:06:06.098 HelloWorld[388:144861] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:06:14.629 HelloWorld[388:144861] Resetting plugins due to page load.
,2015-12-07 15:06:17.501 HelloWorld[388:144861] Finished load of: file:///var/mobile/Containers/Bundle/Application/24843471-DA3A-4E32-9417-DEF48B414493/HelloWorld.app/www/index.html
,2015-12-07 15:06:17.623 HelloWorld[388:144861] JXcore Cordova plugin initializing
2015-12-07 15:06:17.624 HelloWorld[388:145190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1037041664
Free memory 558055424
execPath /private/var/mobile/Containers/Bundle/Application/24843471-DA3A-4E32-9417-DEF48B414493/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/24843471-DA,3A-4E32-9417-DEF48B414493/HelloWorld.app/www/jxcore/
userPath []
2015-12-07 15:06:17.846 HelloWorld[388:145190] Native method ScreenInfo not found.
2015-12-07 15:06:17.846 HelloWorld[388:145190] Native method ScreenBrightness not found.
Dummy Error Log,.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5114  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
