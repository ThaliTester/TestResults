#### Test 50388019b17f598_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019b17f598/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F9B8BAC2-DC00-4032-AA15-FFD4A0529D0B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F9B8BAC2-DC00-4032-AA15-FFD4A0529D0B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019b17f598/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019b17f598/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B7A992D-D1FF-4F35-A85F-D32524333DA1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54917"
,(lldb)     command script import "/tmp/F9B8BAC2-DC00-4032-AA15-FFD4A0529D0B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 18:24:24.293 HelloWorld[1237:1607725] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8C9BA9D4-EE81-43D2-AA49-57E79D5D540F/Library/Cookies/Cookies.binarycookies
,2015-11-24 18:24:24.564 HelloWorld[1237:1607725] Apache Cordova native platform version 3.9.2 is starting.
2015-11-24 18:24:24.565 HelloWorld[1237:1607725] Multi-tasking -> Device: YES, App: YES
,2015-11-24 18:24:24.567 HelloWorld[1237:1607725] Unlimited access to network resources
,2015-11-24 18:24:24.572 HelloWorld[1237:1607725] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 18:24:28.625 HelloWorld[1237:1607725] Resetting plugins due to page load.
,2015-11-24 18:24:29.871 HelloWorld[1237:1607725] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B7A992D-D1FF-4F35-A85F-D32524333DA1/HelloWorld.app/www/index.html
,2015-11-24 18:24:29.924 HelloWorld[1237:1607725] JXcore Cordova plugin initializing
,2015-11-24 18:24:29.925 HelloWorld[1237:1607887] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 792625152
execPath /private/var/mobile/Containers/Bundle/Application/2B7A992D-D1FF-4F35-A85F-D32524333DA1/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/2B7A992D-D1FF-4F35-A85F-D325243,33DA1/HelloWorld.app/www/jxcore/
,userPath []
2015-11-24 18:24:30.103 HelloWorld[1237:1607887] Native method ScreenInfo not found.
2015-11-24 18:24:30.103 HelloWorld[1237:1607887] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5095  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
