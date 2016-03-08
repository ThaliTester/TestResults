#### Test 6170335145aca32_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/51B8D953-9021-40FB-967C-6AF8A5D6B816/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/51B8D953-9021-40FB-967C-6AF8A5D6B816/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7708790-999C-4C00-A60E-6972F940643E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49473"
,(lldb)     command script import "/tmp/51B8D953-9021-40FB-967C-6AF8A5D6B816/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 10:02:06.886 HelloWorld[917:1335005] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69884A2D-C756-4655-9EE3-742612D94E68/Library/Cookies/Cookies.binarycookies
,2016-03-08 10:02:07.208 HelloWorld[917:1335005] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 10:02:07.209 HelloWorld[917:1335005] Multi-tasking -> Device: YES, App: YES
,2016-03-08 10:02:07.211 HelloWorld[917:1335005] Unlimited access to network resources
,2016-03-08 10:02:07.217 HelloWorld[917:1335005] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 10:02:16.171 HelloWorld[917:1335005] Resetting plugins due to page load.
,2016-03-08 10:02:19.570 HelloWorld[917:1335005] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7708790-999C-4C00-A60E-6972F940643E/HelloWorld.app/www/index.html
,2016-03-08 10:02:19.644 HelloWorld[917:1335005] JXcore Cordova plugin initializing
,2016-03-08 10:02:19.645 HelloWorld[917:1335217] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,>> Apple-IpadAir2-1

,Total memory 2084569088

,Free memory 859783168

,execPath /private/var/mobile/Containers/Bundle/Application/A7708790-999C-4C00-A60E-6972F940643E/HelloWorld.app/HelloWorld

,process.cwd /var/mobile/Containers/Bundle/Application/A7708790-999C-4C00-A60E-6972F940643E/HelloWorld.app/www/jxcore/

,userPath []

,2016-03-08 10:02:19.828 HelloWorld[917:1335217] Native method ScreenInfo not found.
,2016-03-08 10:02:19.828 HelloWorld[917:1335217] Native method ScreenBrightness not found.
,Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5124  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
