#### Test 61703351436c7c0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6E2F8AAC-486E-4F46-BA5C-FBF239E28E6E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6E2F8AAC-486E-4F46-BA5C-FBF239E28E6E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D133BC3-5944-49E4-8824-459593276903/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49864"
,(lldb)     command script import "/tmp/6E2F8AAC-486E-4F46-BA5C-FBF239E28E6E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 15:19:49.298 HelloWorld[950:1460739] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65AB420A-DF91-41EC-8A2E-C1D0A172071D/Library/Cookies/Cookies.binarycookies
,2016-03-09 15:19:49.658 HelloWorld[950:1460739] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-09 15:19:49.660 HelloWorld[950:1460739] Multi-tasking -> Device: YES, App: YES
,2016-03-09 15:19:49.663 HelloWorld[950:1460739] Unlimited access to network resources
,2016-03-09 15:19:49.672 HelloWorld[950:1460739] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 15:19:58.577 HelloWorld[950:1460739] Resetting plugins due to page load.
,2016-03-09 15:20:01.813 HelloWorld[950:1460739] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D133BC3-5944-49E4-8824-459593276903/HelloWorld.app/www/index.html
,2016-03-09 15:20:01.870 HelloWorld[950:1460739] JXcore Cordova plugin initializing
2016-03-09 15:20:01.870 HelloWorld[950:1460923] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

Free memory 1447821312

execPath /private/var/mobile/Containers/Bundle/Application/0D133BC3-5944-49E4-8824-459593276903/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/0D,133BC3-5944-49E4-8824-459593276903/HelloWorld.app/www/jxcore/

userPath []

2016-03-09 15:20:02.063 HelloWorld[950:1460923] Native method ScreenInfo not found.
2016-03-09 15:20:02.063 HelloWorld[950:1460923] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5119  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
