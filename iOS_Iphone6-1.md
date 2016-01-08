#### Test 5024228542a63d7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D8A2E8DF-6F4A-43BB-84FF-7BB74728CE0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D8A2E8DF-6F4A-43BB-84FF-7BB74728CE0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5024228542a63d7/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/760F49AF-DF7A-4D33-A398-5B14171EC015/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50847"
,(lldb)     command script import "/tmp/D8A2E8DF-6F4A-43BB-84FF-7BB74728CE0B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 19:08:34.930 HelloWorld[1557:3269300] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/86D3FBFD-ADF1-422A-BCD0-C86932977713/Library/Cookies/Cookies.binarycookies
,2016-01-08 19:08:35.310 HelloWorld[1557:3269300] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 19:08:35.312 HelloWorld[1557:3269300] Multi-tasking -> Device: YES, App: YES
,2016-01-08 19:08:35.321 HelloWorld[1557:3269300] Unlimited access to network resources
,2016-01-08 19:08:35.335 HelloWorld[1557:3269300] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 19:08:44.182 HelloWorld[1557:3269300] Resetting plugins due to page load.
,2016-01-08 19:08:47.236 HelloWorld[1557:3269300] Finished load of: file:///var/mobile/Containers/Bundle/Application/760F49AF-DF7A-4D33-A398-5B14171EC015/HelloWorld.app/www/index.html
,2016-01-08 19:08:47.319 HelloWorld[1557:3269300] JXcore Cordova plugin initializing
,2016-01-08 19:08:47.320 HelloWorld[1557:3269498] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone6-1

Total memory 1037041664

Free memory 599769088

execPath /private/var/mobile/Containers/Bundle/Application/760F49AF-DF7A-4D33-A398-5B14171EC015/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/760F49AF-DF7A-4D33-A398-5B14171EC015/HelloWorld.app/www/jxcore/

userPath []

2016-01-08 19:08:47.512 HelloWorld[1557:3269498] Native method ScreenInfo not found.
2016-01-08 19:08:47.513 HelloWorld[1557:3269498] Native method ScreenBrightness not found.,
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5112  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
