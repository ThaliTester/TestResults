#### Test 83627337ae40023_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8285DB1D-EFCC-4914-9842-3802A621983E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8285DB1D-EFCC-4914-9842-3802A621983E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/35CB5130-3D27-46E9-AE5F-3B780ADB5078/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55814"
,(lldb)     command script import "/tmp/8285DB1D-EFCC-4914-9842-3802A621983E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 22:52:52.248 ThaliTest[532:648924] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CD96CD48-26DA-4E93-B2E0-F6FD47EF03AB/Library/Cookies/Cookies.binarycookies
,2016-09-13 22:52:52.547 ThaliTest[532:648924] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 22:52:52.549 ThaliTest[532:648924] Multi-tasking -> Device: YES, App: YES
,2016-09-13 22:52:52.570 ThaliTest[532:648924] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 22:52:52.958 ThaliTest[532:648924] Using UIWebView
,2016-09-13 22:52:52.967 ThaliTest[532:648924] [CDVTimer][handleopenurl] 0.387967ms
,2016-09-13 22:52:52.973 ThaliTest[532:648924] [CDVTimer][intentandnavigationfilter] 4.984021ms
2016-09-13 22:52:52.973 ThaliTest[532:648924] [CDVTimer][gesturehandler] 0.222981ms
2016-09-13 22:52:52.973 ThaliTest[532:648924] [CDVTimer][TotalPluginStartup] 6.891012ms
,2016-09-13 22:52:58.138 ThaliTest[532:648924] Resetting plugins due to page load.
,2016-09-13 22:52:58.445 ThaliTest[532:648924] Finished load of: file:///var/containers/Bundle/Application/35CB5130-3D27-46E9-AE5F-3B780ADB5078/ThaliTest.app/www/index.html
,2016-09-13 22:52:58.784 ThaliTest[532:648924] JXcore Cordova plugin initializing
,2016-09-13 22:52:58.785 ThaliTest[532:649116] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 22:53:05.528 ThaliTest[532:649116] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 22:53:05.528 ThaliTest[532:649116] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 22:53:05.528 ThaliTest[532:649116] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 22:53:05.530 ThaliTest[532:649116] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
