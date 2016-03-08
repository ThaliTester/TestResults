#### Test 6170335145aca32_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AD0D0292-EEB1-4844-9DB5-E233626C3535/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AD0D0292-EEB1-4844-9DB5-E233626C3535/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3AAF45F8-C686-43B9-9546-D5A41B99E432/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49474"
,(lldb)     command script import "/tmp/AD0D0292-EEB1-4844-9DB5-E233626C3535/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 10:02:05.053 HelloWorld[884:1288622] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3BECBF40-5BAD-4A41-AC35-AC7603AE59CA/Library/Cookies/Cookies.binarycookies
,2016-03-08 10:02:05.453 HelloWorld[884:1288622] Apache Cordova native platform version 3.9.2 is starting.
2016-03-08 10:02:05.454 HelloWorld[884:1288622] Multi-tasking -> Device: YES, App: YES
,2016-03-08 10:02:05.457 HelloWorld[884:1288622] Unlimited access to network resources
,2016-03-08 10:02:05.465 HelloWorld[884:1288622] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 10:02:13.659 HelloWorld[884:1288622] Resetting plugins due to page load.
,2016-03-08 10:02:16.609 HelloWorld[884:1288622] Finished load of: file:///var/mobile/Containers/Bundle/Application/3AAF45F8-C686-43B9-9546-D5A41B99E432/HelloWorld.app/www/index.html
,2016-03-08 10:02:16.687 HelloWorld[884:1288622] JXcore Cordova plugin initializing
,2016-03-08 10:02:16.690 HelloWorld[884:1288822] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

Free memory 1440415744

,execPath /private/var/mobile/Containers/Bundle/Application/3AAF45F8-C686-43B9-9546-D5A41B99E432/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/3AAF45F8-C686-43B9-9546-D5A41B99E432/HelloWorld.app/www/jxcore/

userPath [,]

2016-03-08 10:02:16.876 HelloWorld[884:1288822] Native method ScreenInfo not found.
2016-03-08 10:02:16.876 HelloWorld[884:1288822] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5116  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
