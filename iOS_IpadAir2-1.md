#### Test 50242285e132180_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/DB50F05D-0045-434E-8E54-8340D04A3C5F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DB50F05D-0045-434E-8E54-8340D04A3C5F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e132180/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/516568D1-C628-4EDA-91C0-C9571D4C8A0E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50200"
,(lldb)     command script import "/tmp/DB50F05D-0045-434E-8E54-8340D04A3C5F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 16:09:56.593 HelloWorld[370:144558] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F2BBAB9B-B068-43AA-973B-DA32D12EE3F7/Library/Cookies/Cookies.binarycookies
,2015-12-07 16:09:56.607 HelloWorld[370:144558] <CATransformLayer: 0x16d4b770> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 16:09:56.608 HelloWorld[370:144558] <CATransformLayer: 0x16d4fe00> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 16:09:56.608 HelloWorld[370:144558] <CATransformLayer: 0x16d50ed0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 16:09:56.918 HelloWorld[370:144558] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 16:09:56.919 HelloWorld[370:144558] Multi-tasking -> Device: YES, App: YES
,2015-12-07 16:09:56.921 HelloWorld[370:144558] Unlimited access to network resources
,2015-12-07 16:09:56.925 HelloWorld[370:144558] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 16:10:05.489 HelloWorld[370:144558] Resetting plugins due to page load.
,2015-12-07 16:10:08.555 HelloWorld[370:144558] Finished load of: file:///var/mobile/Containers/Bundle/Application/516568D1-C628-4EDA-91C0-C9571D4C8A0E/HelloWorld.app/www/index.html
,2015-12-07 16:10:08.602 HelloWorld[370:144558] JXcore Cordova plugin initializing
,2015-12-07 16:10:08.603 HelloWorld[370:144809] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 793493504
,execPath /private/var/mobile/Containers/Bundle/Application/516568D1-C628-4EDA-91C0-C9571D4C8A0E/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/516568D1-C628-4EDA-91C0-C9571D4C8A0E/HelloWorld.app/www/jxcore/
,userPath []
,2015-12-07 16:10:08.803 HelloWorld[370:144809] Native method ScreenInfo not found.
2015-12-07 16:10:08.803 HelloWorld[370:144809] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5125  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
