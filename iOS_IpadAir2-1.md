#### Test 61703351926082e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C7203F13-DBBA-4ED9-B608-4196693483A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C7203F13-DBBA-4ED9-B608-4196693483A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351926082e/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/19428CEA-E108-45D8-9CBE-0DE7BE13BC68/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49210"
,(lldb)     command script import "/tmp/C7203F13-DBBA-4ED9-B608-4196693483A4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 08:56:38.766 HelloWorld[901:1326928] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/18243305-22A7-47B6-81D8-CE676B036ABC/Library/Cookies/Cookies.binarycookies
,2016-03-08 08:56:39.109 HelloWorld[901:1326928] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 08:56:39.110 HelloWorld[901:1326928] Multi-tasking -> Device: YES, App: YES
,2016-03-08 08:56:39.113 HelloWorld[901:1326928] Unlimited access to network resources
,2016-03-08 08:56:39.120 HelloWorld[901:1326928] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 08:56:47.715 HelloWorld[901:1326928] Resetting plugins due to page load.
,2016-03-08 08:56:50.876 HelloWorld[901:1326928] Finished load of: file:///var/mobile/Containers/Bundle/Application/19428CEA-E108-45D8-9CBE-0DE7BE13BC68/HelloWorld.app/www/index.html
,2016-03-08 08:56:50.952 HelloWorld[901:1326928] JXcore Cordova plugin initializing
,2016-03-08 08:56:50.953 HelloWorld[901:1327138] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-IpadAir2-1

,Total memory 2084569088

,Free memory 826638336

execPath /private/var/mobile/Containers/Bundle/Application/19428CEA-E108-45D8-9CBE-0DE7BE13BC68/HelloWorld.app/HelloWorld

,process.cwd /var/mobile/Containers/Bundle/Application/19428CEA-E108-45D8-9CBE-0DE7BE13BC68/HelloWorld.app/www/jxcore/

,userPath []

,2016-03-08 08:56:51.143 HelloWorld[901:1327138] Native method ScreenInfo not found.
2016-03-08 08:56:51.143 HelloWorld[901:1327138] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5122  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
