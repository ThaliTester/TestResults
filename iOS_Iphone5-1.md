#### Test 61248225a3bd1fe_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E899D84B-0DF1-40D1-B269-384688AF731B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/E899D84B-0DF1-40D1-B269-384688AF731B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61248225a3bd1fe/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E677D5FA-4740-4EE5-A6A5-F0D73D33CAEC/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49477"
,(lldb)     command script import "/tmp/E899D84B-0DF1-40D1-B269-384688AF731B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-01 15:31:43.542 HelloWorld[364:401192] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05A83EC5-A779-4DC3-9579-8B745A9F0787/Library/Cookies/Cookies.binarycookies
,2016-03-01 15:31:44.032 HelloWorld[364:401192] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-01 15:31:44.034 HelloWorld[364:401192] Multi-tasking -> Device: YES, App: YES
,2016-03-01 15:31:44.041 HelloWorld[364:401192] Unlimited access to network resources
,2016-03-01 15:31:44.054 HelloWorld[364:401192] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-01 15:31:53.654 HelloWorld[364:401192] Resetting plugins due to page load.
,2016-03-01 15:31:57.115 HelloWorld[364:401192] Finished load of: file:///var/mobile/Containers/Bundle/Application/E677D5FA-4740-4EE5-A6A5-F0D73D33CAEC/HelloWorld.app/www/index.html
,2016-03-01 15:31:57.200 HelloWorld[364:401192] JXcore Cordova plugin initializing
,2016-03-01 15:31:57.202 HelloWorld[364:401344] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1064304640
Free memory 431583232
execPath /private/var/mobile/Containers/Bundle/Application/E677D5FA-4740-4EE5-A6A5-F0D73D33CAEC/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/E677D5FA-4740-4EE5-A6A5-F0D73D33CAEC/HelloWorld.app/www/jxcore/
userPath []
,2016-03-01 15:31:57.685 HelloWorld[364:401344] Native method ScreenInfo not found.
2016-03-01 15:31:57.686 HelloWorld[364:401344] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5249  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
