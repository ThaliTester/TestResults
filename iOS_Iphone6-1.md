#### Test 836273372e7ca3d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0C097523-2410-4E8A-A863-998CCC42BEB1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0C097523-2410-4E8A-A863-998CCC42BEB1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E40DA96B-2F44-4257-88D2-A32056EAC7C6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59918"
,(lldb)     command script import "/tmp/0C097523-2410-4E8A-A863-998CCC42BEB1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 09:16:01.975 ThaliTest[450:574104] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52129473-8A42-405B-B38B-F6A756250EA7/Library/Cookies/Cookies.binarycookies
,2016-09-13 09:16:02.267 ThaliTest[450:574104] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 09:16:02.269 ThaliTest[450:574104] Multi-tasking -> Device: YES, App: YES
,2016-09-13 09:16:02.291 ThaliTest[450:574104] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 09:16:02.745 ThaliTest[450:574104] Using UIWebView
,2016-09-13 09:16:02.752 ThaliTest[450:574104] [CDVTimer][handleopenurl] 0.572979ms
,2016-09-13 09:16:02.759 ThaliTest[450:574104] [CDVTimer][intentandnavigationfilter] 7.075012ms
2016-09-13 09:16:02.760 ThaliTest[450:574104] [CDVTimer][gesturehandler] 0.303984ms
2016-09-13 09:16:02.760 ThaliTest[450:574104] [CDVTimer][TotalPluginStartup] 9.492993ms
,2016-09-13 09:16:08.046 ThaliTest[450:574104] Resetting plugins due to page load.
,2016-09-13 09:16:08.373 ThaliTest[450:574104] Finished load of: file:///var/containers/Bundle/Application/E40DA96B-2F44-4257-88D2-A32056EAC7C6/ThaliTest.app/www/index.html
,2016-09-13 09:16:08.714 ThaliTest[450:574104] JXcore Cordova plugin initializing
,2016-09-13 09:16:08.714 ThaliTest[450:574300] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 09:16:15.466 ThaliTest[450:574300] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 09:16:15.466 ThaliTest[450:574300] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 09:16:15.466 ThaliTest[450:574300,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 09:16:15.468 ThaliTest[450:574300] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
