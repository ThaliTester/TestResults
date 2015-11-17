#### Test 50388019c82294c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9FB497AB-EA80-4FB9-B5AB-48F181E007F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9FB497AB-EA80-4FB9-B5AB-48F181E007F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019c82294c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A527BD8F-CB51-4546-A212-68FFC202193E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53821"
,(lldb)     command script import "/tmp/9FB497AB-EA80-4FB9-B5AB-48F181E007F9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-17 18:40:48.463 HelloWorld[607:546058] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B3AE36F-EB42-4326-8503-E0EC4D3A2C4D/Library/Cookies/Cookies.binarycookies
,2015-11-17 18:40:48.748 HelloWorld[607:546058] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-17 18:40:48.749 HelloWorld[607:546058] Multi-tasking -> Device: YES, App: YES
,2015-11-17 18:40:48.751 HelloWorld[607:546058] Unlimited access to network resources
,2015-11-17 18:40:48.756 HelloWorld[607:546058] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-17 18:40:52.767 HelloWorld[607:546058] Resetting plugins due to page load.
,2015-11-17 18:40:54.156 HelloWorld[607:546058] Finished load of: file:///var/mobile/Containers/Bundle/Application/A527BD8F-CB51-4546-A212-68FFC202193E/HelloWorld.app/www/index.html
,2015-11-17 18:40:54.223 HelloWorld[607:546058] JXcore Cordova plugin initializing
,2015-11-17 18:40:54.224 HelloWorld[607:546224] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 902086656
execPath /private/var/mobile/Containers/Bundle/Application/A527BD8F-CB51-4546-A212-68FFC202193E/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/A527BD8F-CB51-4546-A212-68FFC202193E/HelloWorld.app/www/jxcore/
userPath []
2015-11-17 18:40:54.404 HelloWorld[607:546224] Native method ScreenInfo not found.
2015-11-17 18:40:54.405 HelloWorld[607:546224] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5099  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
