#### Test 502422852e23b2c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/13DDBC2B-F0E2-4C56-9926-68F9B2238EE8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/13DDBC2B-F0E2-4C56-9926-68F9B2238EE8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422852e23b2c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/02A6016F-04B2-4A8C-B0A9-C3BC97867567/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49931"
,(lldb)     command script import "/tmp/13DDBC2B-F0E2-4C56-9926-68F9B2238EE8/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:06:09.061 HelloWorld[354:172795] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EA579005-F8C6-4AF3-833D-7FF1B16D788D/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:06:09.556 HelloWorld[354:172795] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:06:09.557 HelloWorld[354:172795] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:06:09.564 HelloWorld[354:172795] Unlimited access to network resources
,2015-12-07 15:06:09.574 HelloWorld[354:172795] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:06:19.197 HelloWorld[354:172795] Resetting plugins due to page load.
,2015-12-07 15:06:22.207 HelloWorld[354:172795] Finished load of: file:///var/mobile/Containers/Bundle/Application/02A6016F-04B2-4A8C-B0A9-C3BC97867567/HelloWorld.app/www/index.html
,2015-12-07 15:06:22.294 HelloWorld[354:172795] JXcore Cordova plugin initializing
,2015-12-07 15:06:22.296 HelloWorld[354:173094] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1064304640
Free memory 388014080
execPath /private/var/mobile/Containers/Bundle/Application/02A6016F-04B2-4A8C-B0A9-C3BC97867567/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/02A6016F-04,B2-4A8C-B0A9-C3BC97867567/HelloWorld.app/www/jxcore/
,userPath []
,2015-12-07 15:06:22.765 HelloWorld[354:173094] Native method ScreenInfo not found.
2015-12-07 15:06:22.765 HelloWorld[354:173094] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5230  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
