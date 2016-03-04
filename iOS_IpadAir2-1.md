#### Test 61703351a2a4153_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/696B7A7A-9C5F-45E5-B3F9-94CB1E12186C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/696B7A7A-9C5F-45E5-B3F9-94CB1E12186C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61703351a2a4153/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB1EE7AA-EAFF-4A5E-B6C1-B5DEFF822052/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49728"
,(lldb)     command script import "/tmp/696B7A7A-9C5F-45E5-B3F9-94CB1E12186C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 13:20:20.084 HelloWorld[656:782386] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68F223FF-B3A2-4AFD-9756-BB304BA92781/Library/Cookies/Cookies.binarycookies
,2016-03-04 13:20:20.401 HelloWorld[656:782386] Apache Cordova native platform version 3.9.2 is starting.
,2016-03-04 13:20:20.402 HelloWorld[656:782386] Multi-tasking -> Device: YES, App: YES
,2016-03-04 13:20:20.410 HelloWorld[656:782386] Unlimited access to network resources
,2016-03-04 13:20:20.417 HelloWorld[656:782386] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 13:20:29.109 HelloWorld[656:782386] Resetting plugins due to page load.
,2016-03-04 13:20:32.321 HelloWorld[656:782386] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB1EE7AA-EAFF-4A5E-B6C1-B5DEFF822052/HelloWorld.app/www/index.html
,2016-03-04 13:20:32.398 HelloWorld[656:782386] JXcore Cordova plugin initializing
,2016-03-04 13:20:32.399 HelloWorld[656:782611] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,>> Apple-IpadAir2-1

,Total memory 2084569088

Free memory 858226688

execPath /private/var/mobile/Containers/Bundle/Application/FB1EE7AA-EAFF-4A5E-B6C1-B5DEFF822052/HelloWorld.app/HelloWorld

,process.cwd /var/mobile/Containers/Bundle/Application/FB1EE7AA-EAFF-4A5E-B6C1-B5DEFF822052/HelloWorld.app/www/jxcore/

,userPath []

,2016-03-04 13:20:32.583 HelloWorld[656:782611] Native method ScreenInfo not found.
2016-03-04 13:20:32.583 HelloWorld[656:782611] Native method ScreenBrightness not found.
Dummy Error Log.

,getBuffer is called!!!!

,Warning: iOS does not support ToggleBluetooth

,Warning: iOS does not support ToggleWiFi

,****TEST TOOK:  5116  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
