#### Test 50242285e707819_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/900590E1-5659-4D7F-87E4-04C69F5B23F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/900590E1-5659-4D7F-87E4-04C69F5B23F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e707819/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8D7D2B5B-D7EE-4981-987E-14A81947A344/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50075"
,(lldb)     command script import "/tmp/900590E1-5659-4D7F-87E4-04C69F5B23F9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2015-12-07 15:34:09.472 HelloWorld[356:139788] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4BDE9ACB-C80E-411E-A83D-58CAE62EA33A/Library/Cookies/Cookies.binarycookies
,2015-12-07 15:34:09.485 HelloWorld[356:139788] <CATransformLayer: 0x15634fb0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-07 15:34:09.486 HelloWorld[356:139788] <CATransformLayer: 0x156360b0> - changing property ,masksToBounds in transform-only layer, will have no effect
2015-12-07 15:34:09.486 HelloWorld[356:139788] <CATransformLayer: 0x15637180> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-07 15:34:09.760 HelloWorld[356:139788] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 15:34:09.761 HelloWorld[356:139788] Multi-tasking -> Device: YES, App: YES
,2015-12-07 15:34:09.763 HelloWorld[356:139788] Unlimited access to network resources
,2015-12-07 15:34:09.768 HelloWorld[356:139788] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 15:34:18.188 HelloWorld[356:139788] Resetting plugins due to page load.
,2015-12-07 15:34:21.219 HelloWorld[356:139788] Finished load of: file:///var/mobile/Containers/Bundle/Application/8D7D2B5B-D7EE-4981-987E-14A81947A344/HelloWorld.app/www/index.html
,2015-12-07 15:34:21.271 HelloWorld[356:139788] JXcore Cordova plugin initializing
,2015-12-07 15:34:21.271 HelloWorld[356:140057] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 810221568
execPath /private/var/mobile/Containers/Bundle/Application/8D7D2B5B-D7EE-4981-987E-14A81947A344/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/8D7D2B5B-D7EE-4981-987E-14A81947A344/HelloWorld.app/www/jxcore/
,userPath []
2015-12-07 15:34:21.463 HelloWorld[356:140057] Native method ScreenInfo not found.
2015-12-07 15:34:21.463 HelloWorld[356:140057] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5116  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
