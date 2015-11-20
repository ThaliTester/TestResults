#### Test 50388019aa1a16d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0D47D048-8AA2-422F-9162-AA8A6658E227/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0D47D048-8AA2-422F-9162-AA8A6658E227/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019aa1a16d/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0148F463-63BF-4803-B247-9D11251D5913/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51005"
,(lldb)     command script import "/tmp/0D47D048-8AA2-422F-9162-AA8A6658E227/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 12:48:06.487 HelloWorld[828:947906] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB5BCA11-B2D1-4BD3-B55B-2707CDDF4D8E/Library/Cookies/Cookies.binarycookies
,2015-11-20 12:48:06.763 HelloWorld[828:947906] Apache Cordova native platform version 3.9.2 is starting.
2015-11-20 12:48:06.763 HelloWorld[828:947906] Multi-tasking -> Device: YES, App: YES
,2015-11-20 12:48:06.765 HelloWorld[828:947906] Unlimited access to network resources
,2015-11-20 12:48:06.771 HelloWorld[828:947906] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 12:48:10.803 HelloWorld[828:947906] Resetting plugins due to page load.
,2015-11-20 12:48:12.248 HelloWorld[828:947906] Finished load of: file:///var/mobile/Containers/Bundle/Application/0148F463-63BF-4803-B247-9D11251D5913/HelloWorld.app/www/index.html
,2015-11-20 12:48:12.304 HelloWorld[828:947906] JXcore Cordova plugin initializing
,2015-11-20 12:48:12.305 HelloWorld[828:948053] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 810975232
execPath /private/var/mobile/Containers/Bundle/Application/0148F463-63BF-4803-B247-9D11251D5913/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/0148F463-63BF-4803-B247-9D11251D5913/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-20 12:48:12.484 HelloWorld[828:948053] Native method ScreenInfo not found.
2015-11-20 12:48:12.484 HelloWorld[828:948053] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5096  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
