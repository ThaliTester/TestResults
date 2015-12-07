#### Test 50242285e707819_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F8937B59-A29D-4628-A533-EFF03E4E08A1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F8937B59-A29D-4628-A533-EFF03E4E08A1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E5CC221-3761-489E-AF08-E78ADF5DFEB1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50074"
,(lldb)     command script import "/tmp/F8937B59-A29D-4628-A533-EFF03E4E08A1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 15:34:06.848 HelloWorld[391:151312] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0C26C2B1-A90C-41E0-A880-7AC30084197C/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:34:07.249 HelloWorld[391:151312] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:34:07.250 HelloWorld[391:151312] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:34:07.254 HelloWorld[391:151312] Unlimited access to network resources
,2015-12-07 15:34:07.266 HelloWorld[391:151312] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:34:15.810 HelloWorld[391:151312] Resetting plugins due to page load.
,2015-12-07 15:34:18.620 HelloWorld[391:151312] Finished load of: file:///var/mobile/Containers/Bundle/Application/4E5CC221-3761-489E-AF08-E78ADF5DFEB1/HelloWorld.app/www/index.html
,2015-12-07 15:34:18.759 HelloWorld[391:151312] JXcore Cordova plugin initializing
,2015-12-07 15:34:18.761 HelloWorld[391:151490] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1048576000
Free memory 916094976
execPath /private/var/mobile/Containers/Bundle/Application/4E5CC221-3761-489E-AF08-E78ADF5DFEB1/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/4E5CC221-3,761-489E-AF08-E78ADF5DFEB1/HelloWorld.app/www/jxcore/
userPath []
2015-12-07 15:34:19.005 HelloWorld[391:151490] Native method ScreenInfo not found.
2015-12-07 15:34:19.005 HelloWorld[391:151490] Native method ScreenBrightness not found.
Dummy Error Lo,g.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5121  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
