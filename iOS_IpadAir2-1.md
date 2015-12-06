#### Test 502422853393492_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/849A76E0-EC1F-4526-88D8-BE9CF2DBDF94/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/849A76E0-EC1F-4526-88D8-BE9CF2DBDF94/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/502422853393492/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/22C0DAC9-4E2E-45B6-A2F1-9BEA98C08BB2/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49363"
,(lldb)     command script import "/tmp/849A76E0-EC1F-4526-88D8-BE9CF2DBDF94/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-06 15:57:53.763 HelloWorld[267:8650] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EA62E605-6168-41C4-AB2A-A6765BD52B13/Library/Cookies/Cookies.binarycookies
,2015-12-06 15:57:53.829 HelloWorld[267:8650] <CATransformLayer: 0x1457e0a0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-06 15:57:53.830 HelloWorld[267:8650] <CATransformLayer: 0x1458f9c0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-06 15:57:53.830 HelloWorld[267:8650] <CATransformLayer: 0x14590b30> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-06 15:57:54.280 HelloWorld[267:8650] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-06 15:57:54.282 HelloWorld[267:8650] Multi-tasking -> Device: YES, App: YES
,2015-12-06 15:57:54.289 HelloWorld[267:8650] Unlimited access to network resources
,2015-12-06 15:57:54.297 HelloWorld[267:8650] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-06 15:58:02.571 HelloWorld[267:8650] Resetting plugins due to page load.
,2015-12-06 15:58:05.717 HelloWorld[267:8650] Finished load of: file:///var/mobile/Containers/Bundle/Application/22C0DAC9-4E2E-45B6-A2F1-9BEA98C08BB2/HelloWorld.app/www/index.html
,2015-12-06 15:58:05.768 HelloWorld[267:8650] JXcore Cordova plugin initializing
,2015-12-06 15:58:05.768 HelloWorld[267:8891] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 708198400
,execPath /private/var/mobile/Containers/Bundle/Application/22C0DAC9-4E2E-45B6-A2F1-9BEA98C08BB2/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/22C0DAC9-4E2E-45B6-A2F1-9BEA98C08BB2/HelloWorld.app/www/jxcore/
,userPath []
2015-12-06 15:58:05.962 HelloWorld[267:8891] Native method ScreenInfo not found.
2015-12-06 15:58:05.962 HelloWorld[267:8891] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5113  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
