#### Test 83276082e94149a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9935D846-F10E-4044-A7CD-391D1BEE0495/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9935D846-F10E-4044-A7CD-391D1BEE0495/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C053C9EC-10F3-40DC-B2AE-BFCB73C7B10E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57734"
,(lldb)     command script import "/tmp/9935D846-F10E-4044-A7CD-391D1BEE0495/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 15:32:46.148 ThaliTest[722:873516] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D96B424-D00A-482E-9970-1A8E17879DE5/Library/Cookies/Cookies.binarycookies
,2016-09-15 15:32:46.343 ThaliTest[722:873516] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 15:32:46.344 ThaliTest[722:873516] Multi-tasking -> Device: YES, App: YES
,2016-09-15 15:32:46.361 ThaliTest[722:873516] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 15:32:46.727 ThaliTest[722:873516] Using UIWebView
,2016-09-15 15:32:46.732 ThaliTest[722:873516] [CDVTimer][handleopenurl] 0.261962ms
,2016-09-15 15:32:46.738 ThaliTest[722:873516] [CDVTimer][intentandnavigationfilter] 5.547047ms
2016-09-15 15:32:46.738 ThaliTest[722:873516] [CDVTimer][gesturehandler] 0.238001ms
2016-09-15 15:32:46.739 ThaliTest[722:873516] [CDVTimer][TotalPluginStartup] 7.175982ms
,2016-09-15 15:32:51.728 ThaliTest[722:873516] Resetting plugins due to page load.
,2016-09-15 15:32:52.018 ThaliTest[722:873516] Finished load of: file:///var/containers/Bundle/Application/C053C9EC-10F3-40DC-B2AE-BFCB73C7B10E/ThaliTest.app/www/index.html
,2016-09-15 15:32:52.393 ThaliTest[722:873516] JXcore Cordova plugin initializing
,2016-09-15 15:32:52.394 ThaliTest[722:873699] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 15:32:59.058 ThaliTest[722:873699] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 15:32:59.058 ThaliTest[722:873699] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 15:32:59.058 ThaliTest[722:873699] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 15:32:59.060 ThaliTest[722:873699] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
