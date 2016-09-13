#### Test 836273372e7ca3d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/41CFCC58-9685-490A-B979-B4CA05F30687/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/41CFCC58-9685-490A-B979-B4CA05F30687/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE5DB634-E2DA-4597-9FA0-F08BF4D4533A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59922"
,(lldb)     command script import "/tmp/41CFCC58-9685-490A-B979-B4CA05F30687/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 09:16:10.484 ThaliTest[2167:4249070] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CECB6772-28D6-4F86-B625-B6168BE4F0EB/Library/Cookies/Cookies.binarycookies
,2016-09-13 09:16:10.920 ThaliTest[2167:4249070] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 09:16:10.922 ThaliTest[2167:4249070] Multi-tasking -> Device: YES, App: YES
,2016-09-13 09:16:10.941 ThaliTest[2167:4249070] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 09:16:12.992 ThaliTest[2167:4249070] Using UIWebView
,2016-09-13 09:16:12.999 ThaliTest[2167:4249070] [CDVTimer][handleopenurl] 0.500977ms
,2016-09-13 09:16:13.007 ThaliTest[2167:4249070] [CDVTimer][intentandnavigationfilter] 7.519007ms
,2016-09-13 09:16:13.008 ThaliTest[2167:4249070] [CDVTimer][gesturehandler] 0.339031ms
,2016-09-13 09:16:13.008 ThaliTest[2167:4249070] [CDVTimer][TotalPluginStartup] 10.256052ms
,2016-09-13 09:16:19.995 ThaliTest[2167:4249070] Resetting plugins due to page load.
,2016-09-13 09:16:24.253 ThaliTest[2167:4249070] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE5DB634-E2DA-4597-9FA0-F08BF4D4533A/ThaliTest.app/www/index.html
,2016-09-13 09:16:24.446 ThaliTest[2167:4249070] JXcore Cordova plugin initializing
,2016-09-13 09:16:24.447 ThaliTest[2167:4249366] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 09:16:30.584 ThaliTest[2167:4249366] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 09:16:30.584 ThaliTest[2167:4249366] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 09:16:30.585 ThaliTest[2167:4249366] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 09:16:30.586 ThaliTest[2167:4249366] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
