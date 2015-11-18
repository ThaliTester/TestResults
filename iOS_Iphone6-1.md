#### Test 50388019f4ce509_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F7FF08CE-9E1A-4ADB-B1D9-50FD0CD325C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F7FF08CE-9E1A-4ADB-B1D9-50FD0CD325C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019f4ce509/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC1AAA40-6FF9-4455-8D60-240D008122D2/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49312"
,(lldb)     command script import "/tmp/F7FF08CE-9E1A-4ADB-B1D9-50FD0CD325C5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-18 09:10:40.358 HelloWorld[793:490572] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6C9B14A3-9BBD-431A-9269-71CCE33CBD35/Library/Cookies/Cookies.binarycookies
,2015-11-18 09:10:40.719 HelloWorld[793:490572] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-18 09:10:40.720 HelloWorld[793:490572] Multi-tasking -> Device: YES, App: YES
,2015-11-18 09:10:40.723 HelloWorld[793:490572] Unlimited access to network resources
,2015-11-18 09:10:40.727 HelloWorld[793:490572] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-18 09:10:44.223 HelloWorld[793:490572] Resetting plugins due to page load.
,2015-11-18 09:10:44.545 HelloWorld[793:490572] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/EC1AAA40-6FF9-4455-8D60-240D008122D2/HelloWorld.app/www/index.html
,2015-11-18 09:10:44.580 HelloWorld[793:490572] JXcore Cordova plugin initializing
2015-11-18 09:10:44.581 HelloWorld[793:490695] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
Free memory 108040192
execPath /private/var/mobile/Containers/Bundle/Application/EC1AAA40-6FF9-4455-8D60-240D008122D2/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/EC1AAA40-6FF9-4455-8D60-240D008122D2/HelloWorld.app/www/jxcore/
,userPath []
2015-11-18 09:10:44.779 HelloWorld[793:490695] Native method ScreenInfo not found.
2015-11-18 09:10:44.780 HelloWorld[793:490695] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
