#### Test 50242285d7f7159_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1DA1190A-E66D-43AF-A266-4DCA42848B83/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1DA1190A-E66D-43AF-A266-4DCA42848B83/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/400F1757-C638-4CCA-AF49-3156F12EBEF5/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57821"
,(lldb)     command script import "/tmp/1DA1190A-E66D-43AF-A266-4DCA42848B83/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-15 21:54:07.339 HelloWorld[219:4112] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C29A31C0-272D-4871-A2AD-DE45E8EBE374/Library/Cookies/Cookies.binarycookies
,2015-12-15 21:54:07.884 HelloWorld[219:4112] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 21:54:07.886 HelloWorld[219:4112] Multi-tasking -> Device: YES, App: YES
,2015-12-15 21:54:07.901 HelloWorld[219:4112] Unlimited access to network resources
,2015-12-15 21:54:07.919 HelloWorld[219:4112] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 21:54:17.303 HelloWorld[219:4112] Resetting plugins due to page load.
,2015-12-15 21:54:20.759 HelloWorld[219:4112] Finished load of: file:///var/mobile/Containers/Bundle/Application/400F1757-C638-4CCA-AF49-3156F12EBEF5/HelloWorld.app/www/index.html
,2015-12-15 21:54:20.908 HelloWorld[219:4112] JXcore Cordova plugin initializing
,2015-12-15 21:54:20.910 HelloWorld[219:4333] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1037041664
Free memory 635322368
execPath /private/var/mobile/Containers/Bundle/Application/400F1757-C638-4CCA-AF49-3156F12EBEF5/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/400F1757-C638-4CCA-AF49-3156F12,EBEF5/HelloWorld.app/www/jxcore/
,userPath []
2015-12-15 21:54:21.151 HelloWorld[219:4333] Native method ScreenInfo not found.
2015-12-15 21:54:21.151 HelloWorld[219:4333] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5117  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
