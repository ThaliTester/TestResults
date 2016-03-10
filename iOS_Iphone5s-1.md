#### Test 623445121bdd37c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/08AA1B54-15A3-44E8-99E0-F7BA43A30952/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/08AA1B54-15A3-44E8-99E0-F7BA43A30952/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/623445121bdd37c/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A81C9775-9B68-4714-97BB-B5B47675549B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50309"
,(lldb)     command script import "/tmp/08AA1B54-15A3-44E8-99E0-F7BA43A30952/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-10 07:23:27.420 HelloWorld[1028:1603338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5DD6196D-8C04-4847-A3E8-FC47BE1DAABF/Library/Cookies/Cookies.binarycookies
,2016-03-10 07:23:27.833 HelloWorld[1028:1603338] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-10 07:23:27.835 HelloWorld[1028:1603338] Multi-tasking -> Device: YES, App: YES
,2016-03-10 07:23:27.843 HelloWorld[1028:1603338] Unlimited access to network resources
,2016-03-10 07:23:27.854 HelloWorld[1028:1603338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 07:23:35.953 HelloWorld[1028:1603338] Resetting plugins due to page load.
,2016-03-10 07:23:39.037 HelloWorld[1028:1603338] Finished load of: file:///var/mobile/Containers/Bundle/Application/A81C9775-9B68-4714-97BB-B5B47675549B/HelloWorld.app/www/index.html
,2016-03-10 07:23:39.140 HelloWorld[1028:1603338] JXcore Cordova plugin initializing
2016-03-10 07:23:39.141 HelloWorld[1028:1603548] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
,Total memory 1048576000
Free memory 604880896
execPath /private/var/mobile/Containers/Bundle/Application/A81C9775-9B68-4714-97BB-B5B47675549B/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/A81C9775-9B68-4714-97BB-B5B4767,5549B/HelloWorld.app/www/jxcore/
userPath []
2016-03-10 07:23:39.394 HelloWorld[1028:1603548] Native method ScreenInfo not found.
2016-03-10 07:23:39.394 HelloWorld[1028:1603548] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5125  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
