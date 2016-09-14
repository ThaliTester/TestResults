#### Test 836273377282b4e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/57F32D31-250A-4DFB-8791-B13F540377E3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/57F32D31-250A-4DFB-8791-B13F540377E3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D5790FC2-1B09-4BC2-862F-2260852DD90F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56147"
,(lldb)     command script import "/tmp/57F32D31-250A-4DFB-8791-B13F540377E3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 17:59:11.638 ThaliTest[2320:4427836] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15AF1E7B-F1C9-4BEA-87BC-E2EAF6D19875/Library/Cookies/Cookies.binarycookies
,2016-09-14 17:59:12.029 ThaliTest[2320:4427836] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 17:59:12.030 ThaliTest[2320:4427836] Multi-tasking -> Device: YES, App: YES
,2016-09-14 17:59:12.050 ThaliTest[2320:4427836] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 17:59:13.959 ThaliTest[2320:4427836] Using UIWebView
,2016-09-14 17:59:13.966 ThaliTest[2320:4427836] [CDVTimer][handleopenurl] 0.531018ms
,2016-09-14 17:59:13.973 ThaliTest[2320:4427836] [CDVTimer][intentandnavigationfilter] 6.654978ms
,2016-09-14 17:59:13.974 ThaliTest[2320:4427836] [CDVTimer][gesturehandler] 0.308990ms
,2016-09-14 17:59:13.974 ThaliTest[2320:4427836] [CDVTimer][TotalPluginStartup] 9.186983ms
,2016-09-14 17:59:20.341 ThaliTest[2320:4427836] Resetting plugins due to page load.
,2016-09-14 17:59:23.872 ThaliTest[2320:4427836] Finished load of: file:///var/mobile/Containers/Bundle/Application/D5790FC2-1B09-4BC2-862F-2260852DD90F/ThaliTest.app/www/index.html
,2016-09-14 17:59:24.136 ThaliTest[2320:4427836] JXcore Cordova plugin initializing
,2016-09-14 17:59:24.137 ThaliTest[2320:4428103] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 17:59:30.262 ThaliTest[2320:4428103] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 17:59:30.262 ThaliTest[2320:4428103] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-14 17:59:30.262 ThaliTest[2320:4428103] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 17:59:30.264 ThaliTest[2320:4428103] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
