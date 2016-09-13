#### Test 8362733700cd7fa_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/595A6761-8ECE-4DD0-8926-FC6E733DE0F5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/595A6761-8ECE-4DD0-8926-FC6E733DE0F5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/77C02C29-69C8-44ED-B717-5303B0E80290/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54104"
,(lldb)     command script import "/tmp/595A6761-8ECE-4DD0-8926-FC6E733DE0F5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 12:55:22.679 ThaliTest[2202:4270613] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D42E67F3-B529-4861-B5D0-53C2614255C8/Library/Cookies/Cookies.binarycookies
,2016-09-13 12:55:22.923 ThaliTest[2202:4270613] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 12:55:22.924 ThaliTest[2202:4270613] Multi-tasking -> Device: YES, App: YES
,2016-09-13 12:55:22.938 ThaliTest[2202:4270613] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 12:55:23.779 ThaliTest[2202:4270613] Using UIWebView
,2016-09-13 12:55:23.781 ThaliTest[2202:4270613] [CDVTimer][handleopenurl] 0.114024ms
,2016-09-13 12:55:23.783 ThaliTest[2202:4270613] [CDVTimer][intentandnavigationfilter] 1.833975ms
2016-09-13 12:55:23.783 ThaliTest[2202:4270613] [CDVTimer][gesturehandler] 0.081003ms
2016-09-13 12:55:23.783 ThaliTest[2202:4270613] [CDVTimer][TotalPluginS,tartup] 2.471983ms
,2016-09-13 12:55:26.955 ThaliTest[2202:4270613] Resetting plugins due to page load.
,2016-09-13 12:55:28.427 ThaliTest[2202:4270613] Finished load of: file:///var/mobile/Containers/Bundle/Application/77C02C29-69C8-44ED-B717-5303B0E80290/ThaliTest.app/www/index.html
,2016-09-13 12:55:28.565 ThaliTest[2202:4270613] JXcore Cordova plugin initializing
,2016-09-13 12:55:28.566 ThaliTest[2202:4270800] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 12:55:34.451 ThaliTest[2202:4270800] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 12:55:34.452 ThaliTest[2202:4270800] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 12:55:34.452 ThaliTest[2202:4270800] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 12:55:34.453 ThaliTest[2202:4270800] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
