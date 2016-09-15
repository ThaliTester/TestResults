#### Test 836273372ac050d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8A458276-4F55-4134-A0FB-98D8FF28067C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8A458276-4F55-4134-A0FB-98D8FF28067C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FE042FF1-6B47-4E9A-84CA-8D767922EC8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51908"
,(lldb)     command script import "/tmp/8A458276-4F55-4134-A0FB-98D8FF28067C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 08:47:59.222 ThaliTest[2395:4512623] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/439BD120-67AB-4EEC-8E04-B5EE3DBDBF33/Library/Cookies/Cookies.binarycookies
,2016-09-15 08:47:59.655 ThaliTest[2395:4512623] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 08:47:59.657 ThaliTest[2395:4512623] Multi-tasking -> Device: YES, App: YES
,2016-09-15 08:47:59.676 ThaliTest[2395:4512623] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 08:48:01.834 ThaliTest[2395:4512623] Using UIWebView
,2016-09-15 08:48:01.842 ThaliTest[2395:4512623] [CDVTimer][handleopenurl] 0.400007ms
,2016-09-15 08:48:01.849 ThaliTest[2395:4512623] [CDVTimer][intentandnavigationfilter] 6.601989ms
,2016-09-15 08:48:01.849 ThaliTest[2395:4512623] [CDVTimer][gesturehandler] 0.299990ms
,2016-09-15 08:48:01.850 ThaliTest[2395:4512623] [CDVTimer][TotalPluginStartup] 8.799016ms
,2016-09-15 08:48:08.771 ThaliTest[2395:4512623] Resetting plugins due to page load.
,2016-09-15 08:48:13.012 ThaliTest[2395:4512623] Finished load of: file:///var/mobile/Containers/Bundle/Application/FE042FF1-6B47-4E9A-84CA-8D767922EC8A/ThaliTest.app/www/index.html
,2016-09-15 08:48:13.227 ThaliTest[2395:4512623] JXcore Cordova plugin initializing
,2016-09-15 08:48:13.228 ThaliTest[2395:4512933] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 08:48:19.437 ThaliTest[2395:4512933] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 08:48:19.437 ThaliTest[2395:4512933] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 08:48:19.438 ThaliTest[2395:4512933] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 08:48:19.439 ThaliTest[2395:4512933] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
