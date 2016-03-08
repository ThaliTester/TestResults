#### Test 6170335145aca32_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9A59613F-C65C-4EF8-9F49-0883B12E9C2D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9A59613F-C65C-4EF8-9F49-0883B12E9C2D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6170335145aca32/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50BADA82-5CFD-48CB-8A8E-0246E3C9EB14/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49470"
,(lldb)     command script import "/tmp/9A59613F-C65C-4EF8-9F49-0883B12E9C2D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-08 10:02:09.123 HelloWorld[712:1420028] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1C857350-767B-4FEA-9003-F55B26285D77/Library/Cookies/Cookies.binarycookies
,2016-03-08 10:02:09.640 HelloWorld[712:1420028] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-08 10:02:09.642 HelloWorld[712:1420028] Multi-tasking -> Device: YES, App: YES
,2016-03-08 10:02:09.648 HelloWorld[712:1420028] Unlimited access to network resources
,2016-03-08 10:02:09.659 HelloWorld[712:1420028] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-08 10:02:19.234 HelloWorld[712:1420028] Resetting plugins due to page load.
,2016-03-08 10:02:22.794 HelloWorld[712:1420028] Finished load of: file:///var/mobile/Containers/Bundle/Application/50BADA82-5CFD-48CB-8A8E-0246E3C9EB14/HelloWorld.app/www/index.html
,2016-03-08 10:02:22.872 HelloWorld[712:1420028] JXcore Cordova plugin initializing
,2016-03-08 10:02:22.877 HelloWorld[712:1420195] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-Iphone5-1

Total memory 1064304640

Free memory 448929792

execPath /private/var/mobile/Containers/Bundle/Application/50BADA82-5CFD-48CB-8A8E-0246E3C9EB14/HelloWorld.app/HelloWorld

process.cwd /var/mobile/Containers/Bundle/Application/50BADA82-5CFD-48CB-8A8E-0246E3C9EB14/HelloWorld.app/www/jxcore/

,userPath []

2016-03-08 10:02:23.316 HelloWorld[712:1420195] Native method ScreenInfo not found.
2016-03-08 10:02:23.317 HelloWorld[712:1420195] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5237  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
