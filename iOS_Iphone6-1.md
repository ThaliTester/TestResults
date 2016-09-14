#### Test 85046911e91e24b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3CB8F716-3D46-40FD-BF14-EF80914D0E48/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3CB8F716-3D46-40FD-BF14-EF80914D0E48/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FD0E7556-5D19-4B64-85D7-269F8A81B9D6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51923"
,(lldb)     command script import "/tmp/3CB8F716-3D46-40FD-BF14-EF80914D0E48/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 17:16:38.013 ThaliTest[585:746668] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF44A021-90C5-4EDD-902E-D588E8D9567C/Library/Cookies/Cookies.binarycookies
,2016-09-14 17:16:38.328 ThaliTest[585:746668] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 17:16:38.330 ThaliTest[585:746668] Multi-tasking -> Device: YES, App: YES
,2016-09-14 17:16:38.352 ThaliTest[585:746668] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 17:16:38.751 ThaliTest[585:746668] Using UIWebView
,2016-09-14 17:16:38.758 ThaliTest[585:746668] [CDVTimer][handleopenurl] 0.383019ms
,2016-09-14 17:16:38.766 ThaliTest[585:746668] [CDVTimer][intentandnavigationfilter] 7.304966ms
2016-09-14 17:16:38.766 ThaliTest[585:746668] [CDVTimer][gesturehandler] 0.363052ms
2016-09-14 17:16:38.767 ThaliTest[585:746668] [CDVTimer][TotalPluginStartup,] 9.733021ms
,2016-09-14 17:16:44.231 ThaliTest[585:746668] Resetting plugins due to page load.
,2016-09-14 17:16:44.445 ThaliTest[585:746668] Finished load of: file:///var/containers/Bundle/Application/FD0E7556-5D19-4B64-85D7-269F8A81B9D6/ThaliTest.app/www/index.html
,2016-09-14 17:16:44.811 ThaliTest[585:746668] JXcore Cordova plugin initializing
,2016-09-14 17:16:44.812 ThaliTest[585:746873] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 17:16:51.591 ThaliTest[585:746873] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 17:16:51.591 ThaliTest[585:746873] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 17:16:51.592 ThaliTest[585:746873] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 17:16:51.594 ThaliTest[585:746873] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-14 17:16:51.987 ThaliTest[585:746873] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003809988498687744
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
