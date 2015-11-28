#### Test 50388019809f971_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019809f971/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D4D7F03B-FBFD-4B22-B2A0-185782F0C0AA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D4D7F03B-FBFD-4B22-B2A0-185782F0C0AA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019809f971/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019809f971/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1A6ED7D6-5DEC-47E1-9F11-82ACB21FA318/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57292"
,(lldb)     command script import "/tmp/D4D7F03B-FBFD-4B22-B2A0-185782F0C0AA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-28 12:13:57.396 HelloWorld[1532:2182511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BFA42866-39DA-45E7-B2E9-F9CF046036B9/Library/Cookies/Cookies.binarycookies
,2015-11-28 12:13:57.679 HelloWorld[1532:2182511] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-28 12:13:57.680 HelloWorld[1532:2182511] Multi-tasking -> Device: YES, App: YES
,2015-11-28 12:13:57.683 HelloWorld[1532:2182511] Unlimited access to network resources
,2015-11-28 12:13:57.688 HelloWorld[1532:2182511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-28 12:14:01.740 HelloWorld[1532:2182511] Resetting plugins due to page load.
,2015-11-28 12:14:03.008 HelloWorld[1532:2182511] Finished load of: file:///var/mobile/Containers/Bundle/Application/1A6ED7D6-5DEC-47E1-9F11-82ACB21FA318/HelloWorld.app/www/index.html
,2015-11-28 12:14:03.061 HelloWorld[1532:2182511] JXcore Cordova plugin initializing
,2015-11-28 12:14:03.062 HelloWorld[1532:2182687] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 787546112
execPath /private/var/mobile/Containers/Bundle/Application/1A6ED7D6-5DEC-47E1-9F11-82ACB21FA318/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/1A6ED7D6-5DEC-47E1-9F11-82ACB21FA318/HelloWorld.app/www/jxcore/
,userPath []
2015-11-28 12:14:03.246 HelloWorld[1532:2182687] Native method ScreenInfo not found.
2015-11-28 12:14:03.246 HelloWorld[1532:2182687] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5095  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
