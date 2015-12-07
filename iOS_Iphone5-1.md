#### Test 50242285e132180_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F452CC57-F929-46C8-8DBE-1DB8062407D3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F452CC57-F929-46C8-8DBE-1DB8062407D3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41185268-6351-44E6-B67C-F6A8D1579C45/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50197"
,(lldb)     command script import "/tmp/F452CC57-F929-46C8-8DBE-1DB8062407D3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 16:09:57.789 HelloWorld[368:181092] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E277FD3E-70C6-4462-B925-3A9949198501/Library/Cookies/Cookies.binarycookies
,2015-12-07 16:09:57.911 HelloWorld[368:181092] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 16:09:57.913 HelloWorld[368:181092] Multi-tasking -> Device: YES, App: YES
,2015-12-07 16:09:57.919 HelloWorld[368:181092] Unlimited access to network resources
,2015-12-07 16:09:57.930 HelloWorld[368:181092] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 16:10:08.183 HelloWorld[368:181092] Resetting plugins due to page load.
,2015-12-07 16:10:11.879 HelloWorld[368:181092] Finished load of: file:///var/mobile/Containers/Bundle/Application/41185268-6351-44E6-B67C-F6A8D1579C45/HelloWorld.app/www/index.html
,2015-12-07 16:10:11.962 HelloWorld[368:181092] JXcore Cordova plugin initializing
2015-12-07 16:10:11.963 HelloWorld[368:181264] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1064304640
Free memory 390086656
execPath /private/var/mobile/Containers/Bundle/Application/41185268-6351-44E6-B67C-F6A8D1579C45/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/41185268-6351-44E6-B67C-F6A8D1579C45/HelloWorld.app/www/jxcore/
,userPath []
2015-12-07 16:10:12.443 HelloWorld[368:181264] Native method ScreenInfo not found.
2015-12-07 16:10:12.444 HelloWorld[368:181264] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5236  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
