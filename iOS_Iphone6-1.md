#### Test 8504691131acdd6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/813017EE-365E-4CA3-BFF7-C9B3286BA53F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/813017EE-365E-4CA3-BFF7-C9B3286BA53F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D753EE71-8AAB-4EBB-9C54-8677C2C62EE1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64742"
,(lldb)     command script import "/tmp/813017EE-365E-4CA3-BFF7-C9B3286BA53F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 12:16:12.067 ThaliTest[798:983429] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3BB8775-890C-4868-8B7B-4493A5F449F6/Library/Cookies/Cookies.binarycookies
,2016-09-16 12:16:12.358 ThaliTest[798:983429] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 12:16:12.360 ThaliTest[798:983429] Multi-tasking -> Device: YES, App: YES
,2016-09-16 12:16:12.384 ThaliTest[798:983429] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 12:16:12.875 ThaliTest[798:983429] Using UIWebView
,2016-09-16 12:16:12.882 ThaliTest[798:983429] [CDVTimer][handleopenurl] 0.361025ms
,2016-09-16 12:16:12.890 ThaliTest[798:983429] [CDVTimer][intentandnavigationfilter] 7.187963ms
2016-09-16 12:16:12.891 ThaliTest[798:983429] [CDVTimer][gesturehandler] 0.346959ms
2016-09-16 12:16:12.891 ThaliTest[798:983429] [CDVTimer][TotalPluginStartup] 9.624004ms
,2016-09-16 12:16:18.110 ThaliTest[798:983429] Resetting plugins due to page load.
,2016-09-16 12:16:18.540 ThaliTest[798:983429] Finished load of: file:///var/containers/Bundle/Application/D753EE71-8AAB-4EBB-9C54-8677C2C62EE1/ThaliTest.app/www/index.html
,2016-09-16 12:16:18.936 ThaliTest[798:983429] JXcore Cordova plugin initializing
,2016-09-16 12:16:18.936 ThaliTest[798:983616] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 12:16:25.650 ThaliTest[798:983616] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 12:16:25.650 ThaliTest[798:983616] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 12:16:25.650 ThaliTest[798:983616,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 12:16:25.652 ThaliTest[798:983616] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 12:16:26.042 ThaliTest[798:983616] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003762006759643555
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
