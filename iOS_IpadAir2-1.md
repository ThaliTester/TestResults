#### Test 83627337ae40023_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C57337D8-E207-4825-9D3D-311C435D4344/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C57337D8-E207-4825-9D3D-311C435D4344/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9FA88E4A-DF04-4169-BDD1-3B6740BCE8BE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55812"
,(lldb)     command script import "/tmp/C57337D8-E207-4825-9D3D-311C435D4344/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 22:52:57.748 ThaliTest[2253:4324777] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2A5DF96D-17E9-4E59-BC86-444DCFDA7D45/Library/Cookies/Cookies.binarycookies
,2016-09-13 22:52:58.205 ThaliTest[2253:4324777] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 22:52:58.206 ThaliTest[2253:4324777] Multi-tasking -> Device: YES, App: YES
,2016-09-13 22:52:58.225 ThaliTest[2253:4324777] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 22:53:00.102 ThaliTest[2253:4324777] Using UIWebView
,2016-09-13 22:53:00.106 ThaliTest[2253:4324777] [CDVTimer][handleopenurl] 0.249982ms
,2016-09-13 22:53:00.112 ThaliTest[2253:4324777] [CDVTimer][intentandnavigationfilter] 4.793048ms
,2016-09-13 22:53:00.112 ThaliTest[2253:4324777] [CDVTimer][gesturehandler] 0.232995ms
,2016-09-13 22:53:00.113 ThaliTest[2253:4324777] [CDVTimer][TotalPluginStartup] 6.419003ms
,2016-09-13 22:53:06.838 ThaliTest[2253:4324777] Resetting plugins due to page load.
,2016-09-13 22:53:10.710 ThaliTest[2253:4324777] Finished load of: file:///var/mobile/Containers/Bundle/Application/9FA88E4A-DF04-4169-BDD1-3B6740BCE8BE/ThaliTest.app/www/index.html
,2016-09-13 22:53:10.916 ThaliTest[2253:4324777] JXcore Cordova plugin initializing
,2016-09-13 22:53:10.916 ThaliTest[2253:4325036] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 22:53:17.074 ThaliTest[2253:4325036] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 22:53:17.074 ThaliTest[2253:4325036] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 22:53:17.075 ThaliTest[2253:4325036] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 22:53:17.076 ThaliTest[2253:4325036] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
