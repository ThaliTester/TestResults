#### Test 502422852e23b2c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/11FF6CC9-98C0-4A88-A7AD-424E0F94F4A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/11FF6CC9-98C0-4A88-A7AD-424E0F94F4A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/64E60572-17A6-4A96-B8B4-6C449A60A2BF/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49934"
,(lldb)     command script import "/tmp/11FF6CC9-98C0-4A88-A7AD-424E0F94F4A5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:06:08.095 HelloWorld[340:135826] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5064FCDC-423A-42B4-A3F6-37D56C39A38D/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:06:08.109 HelloWorld[340:135826] <CATransformLayer: 0x146701f0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 15:06:08.109 HelloWorld[340:135826] <CATransformLayer: 0x14673e70> - changing property ,masksToBounds in transform-only layer, will have no effect
2015-12-07 15:06:08.110 HelloWorld[340:135826] <CATransformLayer: 0x14674fe0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 15:06:08.403 HelloWorld[340:135826] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:06:08.403 HelloWorld[340:135826] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:06:08.410 HelloWorld[340:135826] Unlimited access to network resources
,2015-12-07 15:06:08.416 HelloWorld[340:135826] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:06:16.802 HelloWorld[340:135826] Resetting plugins due to page load.
,2015-12-07 15:06:19.834 HelloWorld[340:135826] Finished load of: file:///var/mobile/Containers/Bundle/Application/64E60572-17A6-4A96-B8B4-6C449A60A2BF/HelloWorld.app/www/index.html
,2015-12-07 15:06:19.884 HelloWorld[340:135826] JXcore Cordova plugin initializing
2015-12-07 15:06:19.885 HelloWorld[340:136129] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 826671104
,execPath /private/var/mobile/Containers/Bundle/Application/64E60572-17A6-4A96-B8B4-6C449A60A2BF/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/64E60572-17A6-4A96-B8B4-6C449A60A2BF/HelloWorld.app/www/jxcore/
,userPath []
,2015-12-07 15:06:20.078 HelloWorld[340:136129] Native method ScreenInfo not found.
2015-12-07 15:06:20.078 HelloWorld[340:136129] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
