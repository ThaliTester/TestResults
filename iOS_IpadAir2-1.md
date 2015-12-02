#### Test 50388019193a02f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1FD39593-B34D-45A3-87AF-35FA603321A8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1FD39593-B34D-45A3-87AF-35FA603321A8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019193a02f/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/013BDA87-E5DB-4E57-8F1A-9244796FBDA7/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59635"
,(lldb)     command script import "/tmp/1FD39593-B34D-45A3-87AF-35FA603321A8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-02 18:44:36.335 HelloWorld[1801:2846461] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4787AC96-7407-42E8-831A-D9D7560607C4/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:44:36.612 HelloWorld[1801:2846461] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:44:36.613 HelloWorld[1801:2846461] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:44:36.616 HelloWorld[1801:2846461] Unlimited access to network resources
,2015-12-02 18:44:36.620 HelloWorld[1801:2846461] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:44:40.756 HelloWorld[1801:2846461] Resetting plugins due to page load.
,2015-12-02 18:44:42.007 HelloWorld[1801:2846461] Finished load of: file:///var/mobile/Containers/Bundle/Application/013BDA87-E5DB-4E57-8F1A-9244796FBDA7/HelloWorld.app/www/index.html
,2015-12-02 18:44:42.065 HelloWorld[1801:2846461] JXcore Cordova plugin initializing
,2015-12-02 18:44:42.066 HelloWorld[1801:2846634] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 742096896
execPath /private/var/mobile/Containers/Bundle/Application/013BDA87-E5DB-4E57-8F1A-9244796FBDA7/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/013BDA87-E5DB-4E57-8F1A-9244796FBDA7/HelloWorld.app/www/jxcore/
userPath []
2015-12-02 18:44:42.246 HelloWorld[1801:2846634] Native method ScreenInfo not found.
2015-12-02 18:44:42.246 HelloWorld[1801:2846634] Native method ScreenBrightness not found.
Dummy Erro,r Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5103  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
