#### Test 50388019193a02f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F1F47686-7834-4616-977B-5F224FC43836/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F1F47686-7834-4616-977B-5F224FC43836/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/F206CD96-C4C9-467B-A09A-83E05FF6E86D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59638"
,(lldb)     command script import "/tmp/F1F47686-7834-4616-977B-5F224FC43836/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:45:20.624 HelloWorld[1118:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-02 18:45:20.627 HelloWorld[1118:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:45:20.636 HelloWorld[1118:60b] Unlimited access to network resources
,2015-12-02 18:45:20.641 HelloWorld[1118:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:45:30.432 HelloWorld[1118:60b] Resetting plugins due to page load.
,2015-12-02 18:45:31.204 HelloWorld[1118:60b] Finished load of: file:///var/mobile/Applications/F206CD96-C4C9-467B-A09A-83E05FF6E86D/HelloWorld.app/www/index.html
,2015-12-02 18:45:31.269 HelloWorld[1118:60b] JXcore Cordova plugin initializing
,2015-12-02 18:45:31.271 HelloWorld[1118:6607] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 553959424
execPath /private/var/mobile/Applications/F206CD96-C4C9-467B-A09A-83E05FF6E86D/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/F206CD96-C4C9-467B-A09A-83E05FF6E86D/HelloWor,ld.app/www/jxcore/
userPath []
,2015-12-02 18:45:31.712 HelloWorld[1118:6607] Native method ScreenInfo not found.
,2015-12-02 18:45:31.715 HelloWorld[1118:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5230  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
