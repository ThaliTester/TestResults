#### Test 83627337140e0c5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B9F0051C-808A-4327-AE1B-E482EE1C7014/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B9F0051C-808A-4327-AE1B-E482EE1C7014/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337140e0c5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D935A93-CD14-4FC2-B9C5-91A5729DBBA6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59958"
,(lldb)     command script import "/tmp/B9F0051C-808A-4327-AE1B-E482EE1C7014/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:04:38.933 ThaliTest[1847:3473669] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/056843D4-13FB-40BB-8D32-0509B80E9DBC/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:04:39.170 ThaliTest[1847:3473669] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:04:39.171 ThaliTest[1847:3473669] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:04:39.185 ThaliTest[1847:3473669] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:04:39.979 ThaliTest[1847:3473669] Using UIWebView
,2016-09-07 09:04:39.981 ThaliTest[1847:3473669] [CDVTimer][handleopenurl] 0.114024ms
,2016-09-07 09:04:39.983 ThaliTest[1847:3473669] [CDVTimer][intentandnavigationfilter] 1.869023ms
,2016-09-07 09:04:39.983 ThaliTest[1847:3473669] [CDVTimer][gesturehandler] 0.083029ms
2016-09-07 09:04:39.983 ThaliTest[1847:3473669] [CDVTimer][TotalPluginStartup] 2.566993ms
,2016-09-07 09:04:42.957 ThaliTest[1847:3473669] Resetting plugins due to page load.
,2016-09-07 09:04:44.364 ThaliTest[1847:3473669] Finished load of: file:///var/mobile/Containers/Bundle/Application/1D935A93-CD14-4FC2-B9C5-91A5729DBBA6/ThaliTest.app/www/index.html
,2016-09-07 09:04:44.497 ThaliTest[1847:3473669] JXcore Cordova plugin initializing
,2016-09-07 09:04:44.497 ThaliTest[1847:3473863] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:04:50.392 ThaliTest[1847:3473863] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 09:04:50.393 ThaliTest[1847:3473863] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:04:50.393 ThaliTest[1847:3473863] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 09:04:50.394 ThaliTest[1847:3473863] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
