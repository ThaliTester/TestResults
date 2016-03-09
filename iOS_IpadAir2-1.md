#### Test 61703351436c7c0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/08D08EA1-082B-4D01-93B3-974CC8A947FD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/08D08EA1-082B-4D01-93B3-974CC8A947FD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351436c7c0/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/541D0CC6-D373-436D-9060-BE294D22BC5D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49862"
,(lldb)     command script import "/tmp/08D08EA1-082B-4D01-93B3-974CC8A947FD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 15:19:45.683 HelloWorld[981:1505255] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0203F392-181D-4065-AFDD-617E2701CAB9/Library/Cookies/Cookies.binarycookies
,2016-03-09 15:19:45.940 HelloWorld[981:1505255] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-09 15:19:45.941 HelloWorld[981:1505255] Multi-tasking -> Device: YES, App: YES
,2016-03-09 15:19:45.943 HelloWorld[981:1505255] Unlimited access to network resources
,2016-03-09 15:19:45.948 HelloWorld[981:1505255] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 15:19:50.429 HelloWorld[981:1505255] Resetting plugins due to page load.
,2016-03-09 15:19:52.024 HelloWorld[981:1505255] Finished load of: file:///var/mobile/Containers/Bundle/Application/541D0CC6-D373-436D-9060-BE294D22BC5D/HelloWorld.app/www/index.html
,2016-03-09 15:19:52.073 HelloWorld[981:1505255] JXcore Cordova plugin initializing
,2016-03-09 15:19:52.074 HelloWorld[981:1505424] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-IpadAir2-1

Total memory 2084569088

Free memory 913866752

execPath /private/var/mobile/Containers/Bundle/Application/541D0CC6-D373-436D-9060-BE294D22BC5D/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/54,1D0CC6-D373-436D-9060-BE294D22BC5D/HelloWorld.app/www/jxcore/

,userPath []

2016-03-09 15:19:52.259 HelloWorld[981:1505424] Native method ScreenInfo not found.
2016-03-09 15:19:52.259 HelloWorld[981:1505424] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5117  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
