#### Test 50242285feafdeb_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/75C47AC9-2807-4F32-BEC1-C44EA891D3A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/75C47AC9-2807-4F32-BEC1-C44EA891D3A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285feafdeb/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/005FD181-4090-4BA5-A1E8-C7C1E56D7FB5/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52955"
,(lldb)     command script import "/tmp/75C47AC9-2807-4F32-BEC1-C44EA891D3A9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 23:46:14.489 HelloWorld[1771:3727384] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B15929D3-7DE0-4BFE-ACCB-604F7F8EFDA9/Library/Cookies/Cookies.binarycookies
,2016-01-11 23:46:14.729 HelloWorld[1771:3727384] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 23:46:14.729 HelloWorld[1771:3727384] Multi-tasking -> Device: YES, App: YES
,2016-01-11 23:46:14.732 HelloWorld[1771:3727384] Unlimited access to network resources
,2016-01-11 23:46:14.738 HelloWorld[1771:3727384] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 23:46:18.935 HelloWorld[1771:3727384] Resetting plugins due to page load.
,2016-01-11 23:46:20.413 HelloWorld[1771:3727384] Finished load of: file:///var/mobile/Containers/Bundle/Application/005FD181-4090-4BA5-A1E8-C7C1E56D7FB5/HelloWorld.app/www/index.html
,2016-01-11 23:46:20.469 HelloWorld[1771:3727384] JXcore Cordova plugin initializing
2016-01-11 23:46:20.470 HelloWorld[1771:3727500] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

Free memory 633929728

execPath /private/var/mobile/Containers/Bundle/Application/005FD181-4090-4BA5-A1E8-C7C1E56D7FB5/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/005,FD181-4090-4BA5-A1E8-C7C1E56D7FB5/HelloWorld.app/www/jxcore/

userPath []

2016-01-11 23:46:20.643 HelloWorld[1771:3727500] Native method ScreenInfo not found.
2016-01-11 23:46:20.643 HelloWorld[1771:3727500] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

Warning: iOS does not support ToggleWiFi

****TEST TOOK:  5101  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
