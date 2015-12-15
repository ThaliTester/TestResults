#### Test 50242285d7f7159_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B2E393F8-B25B-4B88-A059-BF11BB6C3D5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
Executing commands in '/tmp/B2E393F8-B25B-4B88-A059-BF11BB6C3D5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285d7f7159/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0840DFB4-2A0B-435A-9115-9DC869F03E8E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57820"
,(lldb)     command script import "/tmp/B2E393F8-B25B-4B88-A059-BF11BB6C3D5A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 21:54:09.717 HelloWorld[195:3898] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DE7AB62A-ED70-40C6-8CD3-A9037792D2FB/Library/Cookies/Cookies.binarycookies
,2015-12-15 21:54:10.271 HelloWorld[195:3898] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 21:54:10.272 HelloWorld[195:3898] Multi-tasking -> Device: YES, App: YES
,2015-12-15 21:54:10.285 HelloWorld[195:3898] Unlimited access to network resources
,2015-12-15 21:54:10.297 HelloWorld[195:3898] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 21:54:19.662 HelloWorld[195:3898] Resetting plugins due to page load.
,2015-12-15 21:54:23.023 HelloWorld[195:3898] Finished load of: file:///var/mobile/Containers/Bundle/Application/0840DFB4-2A0B-435A-9115-9DC869F03E8E/HelloWorld.app/www/index.html
,2015-12-15 21:54:23.144 HelloWorld[195:3898] JXcore Cordova plugin initializing
,2015-12-15 21:54:23.145 HelloWorld[195:4142] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 841859072
,execPath /private/var/mobile/Containers/Bundle/Application/0840DFB4-2A0B-435A-9115-9DC869F03E8E/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/0840DFB4-2A0B-435A-9115-9DC869F03E8E/HelloWorld.app/www/jxcore/
,userPath []
,2015-12-15 21:54:23.355 HelloWorld[195:4142] Native method ScreenInfo not found.
2015-12-15 21:54:23.356 HelloWorld[195:4142] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5126  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
