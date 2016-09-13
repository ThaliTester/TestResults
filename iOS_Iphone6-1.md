#### Test 836273379690449_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/16DBA169-9214-45B0-83A1-DAA6C9183A39/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/16DBA169-9214-45B0-83A1-DAA6C9183A39/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FE8B7367-EFD9-4C73-9CF2-49DC1F105CDC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56627"
,(lldb)     command script import "/tmp/16DBA169-9214-45B0-83A1-DAA6C9183A39/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 14:17:08.625 ThaliTest[489:603099] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3AA12BA-445B-4109-86A3-10C250CF6E00/Library/Cookies/Cookies.binarycookies
,2016-09-13 14:17:09.041 ThaliTest[489:603099] Apache Cordova native platform version 4.1.1 is starting.
2016-09-13 14:17:09.043 ThaliTest[489:603099] Multi-tasking -> Device: YES, App: YES
,2016-09-13 14:17:09.070 ThaliTest[489:603099] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 14:17:09.710 ThaliTest[489:603099] Using UIWebView
,2016-09-13 14:17:09.718 ThaliTest[489:603099] [CDVTimer][handleopenurl] 0.569046ms
,2016-09-13 14:17:09.726 ThaliTest[489:603099] [CDVTimer][intentandnavigationfilter] 7.396996ms
2016-09-13 14:17:09.727 ThaliTest[489:603099] [CDVTimer][gesturehandler] 0.322044ms
2016-09-13 14:17:09.728 ThaliTest[489:603099] [CDVTimer][TotalPluginStartup,] 9.940982ms
,2016-09-13 14:17:16.621 ThaliTest[489:603099] Resetting plugins due to page load.
,2016-09-13 14:17:16.946 ThaliTest[489:603099] Finished load of: file:///var/containers/Bundle/Application/FE8B7367-EFD9-4C73-9CF2-49DC1F105CDC/ThaliTest.app/www/index.html
,2016-09-13 14:17:17.295 ThaliTest[489:603099] JXcore Cordova plugin initializing
2016-09-13 14:17:17.297 ThaliTest[489:603356] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 14:17:24.035 ThaliTest[489:603356] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 14:17:24.035 ThaliTest[489:603356] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 14:17:24.036 ThaliTest[489:603356] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 14:17:24.037 ThaliTest[489:603356] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
