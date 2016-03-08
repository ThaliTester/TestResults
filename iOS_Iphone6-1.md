#### Test 617033519c823d7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/617033519c823d7/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B81B0D31-D3DC-4619-82C9-0BAF42A5D2C9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B81B0D31-D3DC-4619-82C9-0BAF42A5D2C9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/617033519c823d7/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/617033519c823d7/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/447EEEA3-06F2-4898-831C-1057F4B527B7/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49353"
,(lldb)     command script import "/tmp/B81B0D31-D3DC-4619-82C9-0BAF42A5D2C9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 09:41:23.496 HelloWorld[877:1286122] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4DD0B294-D531-46D3-A33F-8EC45ED6FB15/Library/Cookies/Cookies.binarycookies
,2016-03-08 09:41:23.876 HelloWorld[877:1286122] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 09:41:23.877 HelloWorld[877:1286122] Multi-tasking -> Device: YES, App: YES
,2016-03-08 09:41:23.882 HelloWorld[877:1286122] Unlimited access to network resources
,2016-03-08 09:41:23.895 HelloWorld[877:1286122] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 09:41:32.377 HelloWorld[877:1286122] Resetting plugins due to page load.
,2016-03-08 09:41:35.336 HelloWorld[877:1286122] Finished load of: file:///var/mobile/Containers/Bundle/Application/447EEEA3-06F2-4898-831C-1057F4B527B7/HelloWorld.app/www/index.html
,2016-03-08 09:41:35.412 HelloWorld[877:1286122] JXcore Cordova plugin initializing
,2016-03-08 09:41:35.417 HelloWorld[877:1286328] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

,Total memory 1037041664

Free memory 1468678144

execPath /private/var/mobile/Containers/Bundle/Application/447EEEA3-06F2-4898-831C-1057F4B527B7/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/447EEEA3-06F2-4898-831C-,1057F4B527B7/HelloWorld.app/www/jxcore/

userPath []

2016-03-08 09:41:35.609 HelloWorld[877:1286328] Native method ScreenInfo not found.
2016-03-08 09:41:35.609 HelloWorld[877:1286328] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5111  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
