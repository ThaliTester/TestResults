#### Test 50242285d7f7159_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/72422023-D257-4E2C-8429-DD3875AD104C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/72422023-D257-4E2C-8429-DD3875AD104C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A41A7874-DF4B-4A24-B429-9E63963470AB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57822"
,(lldb)     command script import "/tmp/72422023-D257-4E2C-8429-DD3875AD104C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 21:54:08.146 HelloWorld[209:4344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30EF5A7C-2864-4454-9E86-C5B18F10765F/Library/Cookies/Cookies.binarycookies
,2015-12-15 21:54:08.681 HelloWorld[209:4344] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 21:54:08.682 HelloWorld[209:4344] Multi-tasking -> Device: YES, App: YES
,2015-12-15 21:54:08.698 HelloWorld[209:4344] Unlimited access to network resources
,2015-12-15 21:54:08.718 HelloWorld[209:4344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 21:54:17.840 HelloWorld[209:4344] Resetting plugins due to page load.
,2015-12-15 21:54:21.042 HelloWorld[209:4344] Finished load of: file:///var/mobile/Containers/Bundle/Application/A41A7874-DF4B-4A24-B429-9E63963470AB/HelloWorld.app/www/index.html
,2015-12-15 21:54:21.142 HelloWorld[209:4344] JXcore Cordova plugin initializing
,2015-12-15 21:54:21.146 HelloWorld[209:4559] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1048576000
Free memory 833126400
execPath /private/var/mobile/Containers/Bundle/Application/A41A7874-DF4B-4A24-B429-9E63963470AB/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/A41A7874-DF4B-4A24-B429-9E63963470AB/HelloWorld.app/www/jxcore/
userPath []
2015-12-15 21:54:21.413 HelloWorld[209:4559] Native method ScreenInfo not found.
2015-12-15 21:54:21.413 HelloWorld[209:4559] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5136  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
