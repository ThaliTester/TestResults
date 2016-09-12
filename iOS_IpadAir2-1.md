#### Test 8362733705cfec3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/06D8ABFC-4293-4F73-AC0A-C45DC0ED9788/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/06D8ABFC-4293-4F73-AC0A-C45DC0ED9788/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15A2789C-843E-4AF0-A98D-CFC614F12F9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56688"
,(lldb)     command script import "/tmp/06D8ABFC-4293-4F73-AC0A-C45DC0ED9788/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:55:23.425 ThaliTest[2111:4143175] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DEF60A18-7F4D-41F3-AF03-B7F13339025B/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:55:23.671 ThaliTest[2111:4143175] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:55:23.672 ThaliTest[2111:4143175] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:55:23.685 ThaliTest[2111:4143175] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:55:24.519 ThaliTest[2111:4143175] Using UIWebView
,2016-09-12 13:55:24.521 ThaliTest[2111:4143175] [CDVTimer][handleopenurl] 0.117958ms
,2016-09-12 13:55:24.523 ThaliTest[2111:4143175] [CDVTimer][intentandnavigationfilter] 1.918018ms
2016-09-12 13:55:24.523 ThaliTest[2111:4143175] [CDVTimer][gesturehandler] 0.084996ms
2016-09-12 13:55:24.523 ThaliTest[2111:4143175] [CDVTimer][TotalPluginS,tartup] 2.590954ms
,2016-09-12 13:55:27.647 ThaliTest[2111:4143175] Resetting plugins due to page load.
,2016-09-12 13:55:29.096 ThaliTest[2111:4143175] Finished load of: file:///var/mobile/Containers/Bundle/Application/15A2789C-843E-4AF0-A98D-CFC614F12F9C/ThaliTest.app/www/index.html
,2016-09-12 13:55:29.233 ThaliTest[2111:4143175] JXcore Cordova plugin initializing
2016-09-12 13:55:29.234 ThaliTest[2111:4143365] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 13:55:35.086 ThaliTest[2111:4143365] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-12 13:55:35.086 ThaliTest[2111:4143365] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-12 13:55:35.086 ThaliTest[2111:4143365] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-12 13:55:35.088 ThaliTest[2111:4143365] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
