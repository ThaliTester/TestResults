#### Test 503880197c51433_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/42176E6E-19E7-4410-932B-59D27EEBA70E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/42176E6E-19E7-4410-932B-59D27EEBA70E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/503880197c51433/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC659CD7-ABE8-44C5-95B3-CC1A0880ADC8/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53719"
,(lldb)     command script import "/tmp/42176E6E-19E7-4410-932B-59D27EEBA70E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-23 18:14:11.771 HelloWorld[1442:1094773] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ABE0EABF-D965-4337-B3F2-D1196A540F10/Library/Cookies/Cookies.binarycookies
,2015-11-23 18:14:12.116 HelloWorld[1442:1094773] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-23 18:14:12.117 HelloWorld[1442:1094773] Multi-tasking -> Device: YES, App: YES
,2015-11-23 18:14:12.125 HelloWorld[1442:1094773] Unlimited access to network resources
,2015-11-23 18:14:12.131 HelloWorld[1442:1094773] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-23 18:14:15.787 HelloWorld[1442:1094773] Resetting plugins due to page load.
,2015-11-23 18:14:16.162 HelloWorld[1442:1094773] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/AC659CD7-ABE8-44C5-95B3-CC1A0880ADC8/HelloWorld.app/www/index.html
,2015-11-23 18:14:16.196 HelloWorld[1442:1094773] JXcore Cordova plugin initializing
2015-11-23 18:14:16.197 HelloWorld[1442:1094894] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
,Free memory 147853312
execPath /private/var/mobile/Containers/Bundle/Application/AC659CD7-ABE8-44C5-95B3-CC1A0880ADC8/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/AC659CD7-ABE8-44C5-95B3-CC1A0880ADC8/HelloWorld.,app/www/jxcore/
userPath []
2015-11-23 18:14:16.399 HelloWorld[1442:1094894] Native method ScreenInfo not found.
2015-11-23 18:14:16.400 HelloWorld[1442:1094894] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5106  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
