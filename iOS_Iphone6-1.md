#### Test 61248225a3bd1fe_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BAB97A1F-AA38-4F9F-AFD4-B40E7C5236E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
Executing commands in '/tmp/BAB97A1F-AA38-4F9F-AFD4-B40E7C5236E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FF600575-659A-4ADD-B1F4-EBA6537DE2B5/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49475"
,(lldb)     command script import "/tmp/BAB97A1F-AA38-4F9F-AFD4-B40E7C5236E9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-01 15:31:40.423 HelloWorld[408:383523] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2E2038C3-6B1B-48CD-B90A-B3AF4B9B5837/Library/Cookies/Cookies.binarycookies
,2016-03-01 15:31:40.969 HelloWorld[408:383523] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-01 15:31:40.971 HelloWorld[408:383523] Multi-tasking -> Device: YES, App: YES
,2016-03-01 15:31:40.991 HelloWorld[408:383523] Unlimited access to network resources
,2016-03-01 15:31:41.015 HelloWorld[408:383523] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-01 15:31:50.324 HelloWorld[408:383523] Resetting plugins due to page load.
,2016-03-01 15:31:53.096 HelloWorld[408:383523] Finished load of: file:///var/mobile/Containers/Bundle/Application/FF600575-659A-4ADD-B1F4-EBA6537DE2B5/HelloWorld.app/www/index.html
,2016-03-01 15:31:53.259 HelloWorld[408:383523] JXcore Cordova plugin initializing
,2016-03-01 15:31:53.261 HelloWorld[408:383790] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1037041664
Free memory 706297856
execPath /private/var/mobile/Containers/Bundle/Application/FF600575-659A-4ADD-B1F4-EBA6537DE2B5/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/FF600575-65,9A-4ADD-B1F4-EBA6537DE2B5/HelloWorld.app/www/jxcore/
userPath []
2016-03-01 15:31:53.509 HelloWorld[408:383790] Native method ScreenInfo not found.
2016-03-01 15:31:53.510 HelloWorld[408:383790] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5123  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
